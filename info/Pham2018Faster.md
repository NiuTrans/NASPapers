# Title 
Faster Discovery of Neural Architectures by Searching for Paths in a Large Model
## Author 
Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean
## Abstract 
We propose Efficient Neural Architecture Search (ENAS), a faster and less expensive approach to automated model design than previous methods. In ENAS, a controller learns to discover neural network architectures by searching for an optimal path within a larger model. The controller is trained with policy gradient to select a path that maximizes the expected reward on the validation set. Meanwhile the model corresponding to the selected path is trained to minimize the cross entropy loss. On the Penn Treebank dataset, ENAS can discover a novel architecture thats achieves a test perplexity of 57.8, which is state-of-the-art among automatic model design methods on Penn Treebank. On the CIFAR-10 dataset, ENAS can design novel architectures that achieve a test error of 2.89%, close to the 2.65% achieved by standard NAS (Zoph et al., 2017). Most importantly, our experiments show that ENAS is more than 10x faster and 100x less resource-demanding than NAS.
TL;DR: An approach that speeds up neural architecture search by 10x, whilst using 100x less computing resource.
## Bib
@misc{
pham2018faster,
title={Faster Discovery of Neural Architectures by Searching for Paths in a Large Model},
author={Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean},
year={2018},
url={https://openreview.net/forum?id=ByQZjx-0-},
}