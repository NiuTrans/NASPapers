# Title 
S2DNAS:Transforming Static CNN Model for Dynamic Inference via Neural Architecture Search
## Author 
Zhihang Yuan, Bingzhe Wu, Zheng Liang, Shiwan Zhao, Weichen Bi, Guangyu Sun
## Abstract 
Recently, dynamic inference has emerged as a promising way to reduce the computational cost of deep convolutional neural network (CNN). In contrast to static methods (e.g. weight pruning), dynamic inference adaptively adjusts the inference process according to each input sample, which can considerably reduce the computational cost on "easy" samples while maintaining the overall model performance. In this paper, we introduce a general framework, S2DNAS, which can transform various static CNN models to support dynamic inference via neural architecture search. To this end, based on a given CNN model, we first generate a CNN architecture space in which each architecture is a multi-stage CNN generated from the given model using some predefined transformations. Then, we propose a reinforcement learning based approach to automatically search for the optimal CNN architecture in the generated space. At last, with the searched multi-stage network, we can perform dynamic inference by adaptively choosing a stage to evaluate for each sample. Unlike previous works that introduce irregular computations or complex controllers in the inference or re-design a CNN model from scratch, our method can generalize to most of the popular CNN architectures and the searched dynamic network can be directly deployed using existing deep learning frameworks in various hardware devices.
## Bib
@article{DBLP:journals/corr/abs-1911-07033,
  author    = {Zhihang Yuan and
               Bingzhe Wu and
               Zheng Liang and
               Shiwan Zhao and
               Weichen Bi and
               Guangyu Sun},
  title     = {{S2DNAS:} Transforming Static {CNN} Model for Dynamic Inference via
               Neural Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1911.07033},
  year      = {2019},
  url       = {http://arxiv.org/abs/1911.07033},
  archivePrefix = {arXiv},
  eprint    = {1911.07033},
  timestamp = {Sun, 05 Jan 2020 18:29:40 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1911-07033.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}