# Title 
Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells
## Author 
Vladimir Nekrasov, Hao Chen, Chunhua Shen, Ian Reid
## Abstract 
Automated design of neural network architectures tailored for a specific task is an extremely promising, albeit inherently difficult, avenue to explore. While most results in this domain have been achieved on image classification and language modelling problems, here we concentrate on dense per-pixel tasks, in particular, semantic image segmentation using fully convolutional networks. In contrast to the aforementioned areas, the design choices of a fully convolutional network require several changes, ranging from the sort of operations that need to be used---e.g., dilated convolutions---to a solving of a more difficult optimisation problem. In this work, we are particularly interested in searching for high-performance compact segmentation architectures, able to run in real-time using limited resources. To achieve that, we intentionally over-parameterise the architecture during the training time via a set of auxiliary cells that provide an intermediate supervisory signal and can be omitted during the evaluation phase. The design of the auxiliary cell is emitted by a controller, a neural network with the fixed structure trained using reinforcement learning. More crucially, we demonstrate how to efficiently search for these architectures within limited time and computational budgets. In particular, we rely on a progressive strategy that terminates non-promising architectures from being further trained, and on Polyak averaging coupled with knowledge distillation to speed-up the convergence. Quantitatively, in 8 GPU-days our approach discovers a set of architectures performing on-par with state-of-the-art among compact models on the semantic segmentation, pose estimation and depth prediction tasks. Code will be made available here: [this https URL](https://github.com/drsleep/nas-segm-pytorch)
## Bib
@article{DBLP:journals/corr/abs-1810-10804,
  author    = {Vladimir Nekrasov and
               Hao Chen and
               Chunhua Shen and
               Ian D. Reid},
  title     = {Fast Neural Architecture Search of Compact Semantic Segmentation Models
               via Auxiliary Cells},
  journal   = {CoRR},
  volume    = {abs/1810.10804},
  year      = {2018},
  url       = {http://arxiv.org/abs/1810.10804},
  archivePrefix = {arXiv},
  eprint    = {1810.10804},
  timestamp = {Fri, 10 Jan 2020 11:12:28 +0100},
  biburl    ={https://dblp.org/rec/journals/corr/abs-1810-10804.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}