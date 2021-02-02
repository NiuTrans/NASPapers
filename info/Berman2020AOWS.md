# Title 
AOWS: Adaptive and optimal network width search with latency constraints
## Author 
Maxim Berman, Leonid Pishchulin, Ning Xu, Matthew B. Blaschko, Gerard Medioni
## Abstract 
Neural architecture search (NAS) approaches aim at automatically finding novel CNN architectures that fit computational constraints while maintaining a good performance on the target platform. We introduce a novel efficient one-shot NAS approach to optimally search for channel numbers, given latency constraints on a specific hardware. We first show that we can use a black-box approach to estimate a realistic latency model for a specific inference platform, without the need for low-level access to the inference computation. Then, we design a pairwise MRF to score any channel configuration and use dynamic programming to efficiently decode the best performing configuration, yielding an optimal solution for the network width search. Finally, we propose an adaptive channel configuration sampling scheme to gradually specialize the training phase to the target computational constraints. Experiments on ImageNet classification show that our approach can find networks fitting the resource constraints on different target platforms while improving accuracy over the state-of-the-art efficient networks.
## Bib
@article{DBLP:journals/corr/abs-2005-10481,
  author    = {Maxim Berman and
               Leonid Pishchulin and
               Ning Xu and
               Matthew B. Blaschko and
               G{\'{e}}rard G. Medioni},
  title     = {{AOWS:} Adaptive and optimal network width search with latency constraints},
  journal   = {CoRR},
  volume    = {abs/2005.10481},
  year      = {2020},
  url       = {https://arxiv.org/abs/2005.10481},
  archivePrefix = {arXiv},
  eprint    = {2005.10481},
  timestamp = {Fri, 22 May 2020 16:21:29 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2005-10481.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}