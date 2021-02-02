# Title 
AutoGAN: Neural Architecture Search for Generative Adversarial Networks
## Author 
Xinyu Gong, Shiyu Chang, Yifan Jiang, Zhangyang Wang
## Abstract 
Neural architecture search (NAS) has witnessed prevailing success in image classification and (very recently) segmentation tasks. In this paper, we present the first preliminary study on introducing the NAS algorithm to generative adversarial networks (GANs), dubbed AutoGAN. The marriage of NAS and GANs faces its unique challenges. We define the search space for the generator architectural variations and use an RNN controller to guide the search, with parameter sharing and dynamic-resetting to accelerate the process. Inception score is adopted as the reward, and a multi-level search strategy is introduced to perform NAS in a progressive way. Experiments validate the effectiveness of AutoGAN on the task of unconditional image generation. Specifically, our discovered architectures achieve highly competitive performance compared to current state-of-the-art hand-crafted GANs, e.g., setting new state-of-the-art FID scores of 12.42 on CIFAR-10, and 31.01 on STL-10, respectively. We also conclude with a discussion of the current limitations and future potential of AutoGAN. The code is available at [this https URL](https://github.com/TAMU-VITA/AutoGAN)
## Bib
@article{DBLP:journals/corr/abs-1908-03835,
  author    = {Xinyu Gong and
               Shiyu Chang and
               Yifan Jiang and
               Zhangyang Wang},
  title     = {AutoGAN: Neural Architecture Search for Generative Adversarial Networks},
  journal   = {CoRR},
  volume    = {abs/1908.03835},
  year      = {2019},
  url       = {http://arxiv.org/abs/1908.03835},
  archivePrefix = {arXiv},
  eprint    = {1908.03835},
  timestamp = {Mon, 19 Aug 2019 13:21:03 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1908-03835.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}