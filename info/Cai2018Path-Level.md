# Title 
Path-Level Network Transformation for Efficient Architecture Search
## Author 
Han Cai, Jiacheng Yang, Weinan Zhang, Song Han, Yong Yu

## Abstract 
We introduce a new function-preserving transformation for efficient neural architecture search. This network transformation allows reusing previously trained networks and existing successful architectures that improves sample efficiency. We aim to address the limitation of current network transformation operations that can only perform layer-level architecture modifications, such as adding (pruning) filters or inserting (removing) a layer, which fails to change the topology of connection paths. Our proposed path-level transformation operations enable the meta-controller to modify the path topology of the given network while keeping the merits of reusing weights, and thus allow efficiently designing effective structures with complex path topologies like Inception models. We further propose a bidirectional tree-structured reinforcement learning meta-controller to explore a simple yet highly expressive tree-structured architecture space that can be viewed as a generalization of multi-branch architectures. We experimented on the image classification datasets with limited computational resources (about 200 GPU-hours), where we observed improved parameter efficiency and better test results (97.70% test accuracy on CIFAR-10 with 14.3M parameters and 74.6% top-1 accuracy on ImageNet in the mobile setting), demonstrating the effectiveness and transferability of our designed architectures.
## Bib
@article{DBLP:journals/corr/abs-1806-02639,
  author    = {Han Cai and
               Jiacheng Yang and
               Weinan Zhang and
               Song Han and
               Yong Yu},
  title     = {Path-Level Network Transformation for Efficient Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1806.02639},
  year      = {2018},
  url       = {http://arxiv.org/abs/1806.02639},
  archivePrefix = {arXiv},
  eprint    = {1806.02639},
  timestamp = {Tue, 24 Nov 2020 14:44:01 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1806-02639.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}