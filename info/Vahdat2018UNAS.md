# Title 
UNAS: Differentiable Architecture Search Meets Reinforcement Learning
## Author 
Arash Vahdat, Arun Mallya, Ming-Yu Liu, Jan Kautz
## Abstract 
Neural architecture search (NAS) aims to discover network architectures with desired properties such as high accuracy or low latency. Recently, differentiable NAS (DNAS) has demonstrated promising results while maintaining a search cost orders of magnitude lower than reinforcement learning (RL) based NAS. However, DNAS models can only optimize differentiable loss functions in search, and they require an accurate differentiable approximation of non-differentiable criteria. In this work, we present UNAS, a unified framework for NAS, that encapsulates recent DNAS and RL-based approaches under one framework. Our framework brings the best of both worlds, and it enables us to search for architectures with both differentiable and non-differentiable criteria in one unified framework while maintaining a low search cost. Further, we introduce a new objective function for search based on the generalization gap that prevents the selection of architectures prone to overfitting. We present extensive experiments on the CIFAR-10, CIFAR-100, and ImageNet datasets and we perform search in two fundamentally different search spaces. We show that UNAS obtains the state-of-the-art average accuracy on all three datasets when compared to the architectures searched in the DARTS space. Moreover, we show that UNAS can find an efficient and accurate architecture in the ProxylessNAS search space, that outperforms existing MobileNetV2 based architectures. The source code is available at [this https URL](https://github.com/NVlabs/unas) .
## Bib
@article{DBLP:journals/corr/abs-1912-07651,
  author    = {Arash Vahdat and
               Arun Mallya and
               Ming{-}Yu Liu and
               Jan Kautz},
  title     = {{UNAS:} Differentiable Architecture Search Meets Reinforcement Learning},
  journal   = {CoRR},
  volume    = {abs/1912.07651},
  year      = {2019},
  url       = {http://arxiv.org/abs/1912.07651},
  archivePrefix = {arXiv},
  eprint    = {1912.07651},
  timestamp = {Fri, 03 Jan 2020 16:10:45 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1912-07651.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}