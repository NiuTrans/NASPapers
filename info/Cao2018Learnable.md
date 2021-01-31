# Title
Learnable Embedding Space for Efficient Neural Architecture Compression

## Author
Shengcao Cao, Xiaofang Wang, Kris M. Kitani

## Abstract
We propose a method to incrementally learn an embedding space over the domain of network architectures, to enable the careful selection of architectures for evaluation during compressed architecture search. Given a teacher network, we search for a compressed network architecture by using Bayesian Optimization (BO) with a kernel function defined over our proposed embedding space to select architectures for evaluation. We demonstrate that our search algorithm can significantly outperform various baseline methods, such as random search and reinforcement learning (Ashok et al., 2018). The compressed architectures found by our method are also better than the state-of-the-art manually-designed compact architecture ShuffleNet (Zhang et al., 2018). We also demonstrate that the learned embedding space can be transferred to new settings for architecture search, such as a larger teacher network or a teacher network in a different architecture family, without any training.

## Bib
@inproceedings{
cao2018learnable,
title={Learnable Embedding Space for Efficient Neural Architecture Compression},
author={Shengcao Cao and Xiaofang Wang and Kris M. Kitani},
booktitle={International Conference on Learning Representations},
year={2019},
url={https://openreview.net/forum?id=S1xLN3C9YX},
}