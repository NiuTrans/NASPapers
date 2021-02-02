# Title 
Efficient Architecture Search by Network Transformation
## Author 
Han Cai, Tianyao Chen, Weinan Zhang, Yong Yu, Jun Wang
## Abstract 
Techniques for automatically designing deep neural network architectures such as reinforcement learning based approaches have recently shown promising results. However, their success is based on vast computational resources (e.g. hundreds of GPUs), making them difficult to be widely used. A noticeable limitation is that they still design and train each network from scratch during the exploration of the architecture space, which is highly inefficient. In this paper, we propose a new framework toward efficient architecture search by exploring the architecture space based on the current network and reusing its weights. We employ a reinforcement learning agent as the meta-controller, whose action is to grow the network depth or layer width with function-preserving transformations. As such, the previously validated networks can be reused for further exploration, thus saves a large amount of computational cost. We apply our method to explore the architecture space of the plain convolutional neural networks (no skip-connections, branching etc.) on image benchmark datasets (CIFAR-10, SVHN) with restricted computational resources (5 GPUs). Our method can design highly competitive networks that outperform existing networks using the same design scheme. On CIFAR-10, our model without skip-connections achieves 4.23\% test error rate, exceeding a vast majority of modern architectures and approaching DenseNet. Furthermore, by applying our method to explore the DenseNet architecture space, we are able to achieve more accurate networks with fewer parameters.
## Bib
@article{DBLP:journals/corr/CaiCZYW17,
  author    = {Han Cai and
               Tianyao Chen and
               Weinan Zhang and
               Yong Yu and
               Jun Wang},
  title     = {Reinforcement Learning for Architecture Search by Network Transformation},
  journal   = {CoRR},
  volume    = {abs/1707.04873},
  year      = {2017},
  url       = {http://arxiv.org/abs/1707.04873},
  archivePrefix = {arXiv},
  eprint    = {1707.04873},
  timestamp = {Sun, 21 Apr 2019 10:04:41 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/CaiCZYW17.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}