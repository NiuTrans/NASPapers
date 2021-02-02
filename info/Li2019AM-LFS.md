# Title 
AM-LFS: AutoML for Loss Function Search     
## Author 
Chuming Li, Yuan Xin, Chen Lin, Minghao Guo, Wei Wu, Wanli Ouyang, Junjie Yan
## Abstract 
Designing an effective loss function plays an important role in visual analysis. Most existing loss function designs rely on hand-crafted heuristics that require domain experts to explore the large design space, which is usually sub-optimal and time-consuming. In this paper, we propose AutoML for Loss Function Search (AM-LFS) which leverages REINFORCE to search loss functions during the training process. The key contribution of this work is the design of search space which can guarantee the generalization and transferability on different vision tasks by including a bunch of existing prevailing loss functions in a unified formulation. We also propose an efficient optimization framework which can dynamically optimize the parameters of loss function's distribution during training. Extensive experimental results on four benchmark datasets show that, without any tricks, our method outperforms existing hand-crafted loss functions in various computer vision tasks.
## Bib
@article{DBLP:journals/corr/abs-1905-07375,
  author    = {Chuming Li and
               Chen Lin and
               Minghao Guo and
               Wei Wu and
               Wanli Ouyang and
               Junjie Yan},
  title     = {{AM-LFS:} AutoML for Loss Function Search},
  journal   = {CoRR},
  volume    = {abs/1905.07375},
  year      = {2019},
  url       = {http://arxiv.org/abs/1905.07375},
  archivePrefix = {arXiv},
  eprint    = {1905.07375},
  timestamp = {Tue, 28 May 2019 12:48:08 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1905-07375.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}