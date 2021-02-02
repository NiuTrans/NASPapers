# Title 
IRLAS: Inverse Reinforcement Learning for Architecture Search
## Author 
Minghao Guo, Zhao Zhong, Wei Wu, Dahua Lin, Junjie Yan
## Abstract 
In this paper, we propose an inverse reinforcement learning method for architecture search (IRLAS), which trains an agent to learn to search network structures that are topologically inspired by human-designed network. Most existing architecture search approaches totally neglect the topological characteristics of architectures, which results in complicated architecture with a high inference latency. Motivated by the fact that human-designed networks are elegant in topology with a fast inference speed, we propose a mirror stimuli function inspired by biological cognition theory to extract the abstract topological knowledge of an expert human-design network (ResNeXt). To avoid raising a too strong prior over the search space, we introduce inverse reinforcement learning to train the mirror stimuli function and exploit it as a heuristic guidance for architecture search, easily generalized to different architecture search algorithms. On CIFAR-10, the best architecture searched by our proposed IRLAS achieves 2.60% error rate. For ImageNet mobile setting, our model achieves a state-of-the-art top-1 accuracy 75.28%, while being 2~4x faster than most auto-generated architectures. A fast version of this model achieves 10% faster than MobileNetV2, while maintaining a higher accuracy.
## Bib
@article{DBLP:journals/corr/abs-1812-05285,
  author    = {Minghao Guo and
               Zhao Zhong and
               Wei Wu and
               Dahua Lin and
               Junjie Yan},
  title     = {{IRLAS:} Inverse Reinforcement Learning for Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1812.05285},
  year      = {2018},
  url       = {http://arxiv.org/abs/1812.05285},
  archivePrefix = {arXiv},
  eprint    = {1812.05285},
  timestamp = {Tue, 01 Jan 2019 15:01:25 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1812-05285.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}