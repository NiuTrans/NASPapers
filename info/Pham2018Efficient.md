# Title 
Efficient Neural Architecture Search via Parameter Sharing
## Author 
Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean
## Abstract 
We propose Efficient Neural Architecture Search (ENAS), a fast and inexpensive approach for automatic model design. In ENAS, a controller learns to discover neural network architectures by searching for an optimal subgraph within a large computational graph. The controller is trained with policy gradient to select a subgraph that maximizes the expected reward on the validation set. Meanwhile the model corresponding to the selected subgraph is trained to minimize a canonical cross entropy loss. Thanks to parameter sharing between child models, ENAS is fast: it delivers strong empirical performances using much fewer GPU-hours than all existing automatic model design approaches, and notably, 1000x less expensive than standard Neural Architecture Search. On the Penn Treebank dataset, ENAS discovers a novel architecture that achieves a test perplexity of 55.8, establishing a new state-of-the-art among all methods without post-training processing. On the CIFAR-10 dataset, ENAS designs novel architectures that achieve a test error of 2.89%, which is on par with NASNet (Zoph et al., 2018), whose test error is 2.65%.
## Bib
@article{DBLP:journals/corr/abs-1802-03268,
  author    = {Hieu Pham and
               Melody Y. Guan and
               Barret Zoph and
               Quoc V. Le and
               Jeff Dean},
  title     = {Efficient Neural Architecture Search via Parameter Sharing},
  journal   = {CoRR},
  volume    = {abs/1802.03268},
  year      = {2018},
  url       = {http://arxiv.org/abs/1802.03268},
  archivePrefix = {arXiv},
  eprint    = {1802.03268},
  timestamp = {Mon, 13 Aug 2018 16:47:58 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1802-03268.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}