# Title 
Breaking the Curse of Space Explosion: Towards Efficient NAS with Curriculum Search
## Author 
Yong Guo, Yaofo Chen, Yin Zheng, Peilin Zhao, Jian Chen, Junzhou Huang, Mingkui Tan
## Abstract 
Neural architecture search (NAS) has become an important approach to automatically find effective architectures. To cover all possible good architectures, we need to search in an extremely large search space with billions of candidate architectures. More critically, given a large search space, we may face a very challenging issue of space explosion. However, due to the limitation of computational resources, we can only sample a very small proportion of the architectures, which provides insufficient information for the training. As a result, existing methods may often produce suboptimal architectures. To alleviate this issue, we propose a curriculum search method that starts from a small search space and gradually incorporates the learned knowledge to guide the search in a large space. With the proposed search strategy, our Curriculum Neural Architecture Search (CNAS) method significantly improves the search efficiency and finds better architectures than existing NAS methods. Extensive experiments on CIFAR-10 and ImageNet demonstrate the effectiveness of the proposed method.
## Bib
@article{DBLP:journals/corr/abs-2007-07197,
  author    = {Yong Guo and
               Yaofo Chen and
               Yin Zheng and
               Peilin Zhao and
               Jian Chen and
               Junzhou Huang and
               Mingkui Tan},
  title     = {Breaking the Curse of Space Explosion: Towards Efficient {NAS} with
               Curriculum Search},
  journal   = {CoRR},
  volume    = {abs/2007.07197},
  year      = {2020},
  url       = {https://arxiv.org/abs/2007.07197},
  archivePrefix = {arXiv},
  eprint    = {2007.07197},
  timestamp = {Tue, 21 Jul 2020 12:53:33 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2007-07197.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}