# Title
BATS: Binary ArchitecTure Search

## Author
Adrian Bulat, Brais Martinez, Georgios Tzimiropoulos

## Abstract
This paper proposes Binary ArchitecTure Search (BATS), a framework that drastically reduces the accuracy gap between binary neural networks and their real-valued counterparts by means of Neural Architecture Search (NAS). We show that directly applying NAS to the binary domain provides very poor results. To alleviate this, we describe, to our knowledge, for the first time, the 3 key ingredients for successfully applying NAS to the binary domain. Specifically, we (1) introduce and design a novel binary-oriented search space, (2) propose a new mechanism for controlling and stabilising the resulting searched topologies, (3) propose and validate a series of new search strategies for binary networks that lead to faster convergence and lower search times. Experimental results demonstrate the effectiveness of the proposed approach and the necessity of searching in the binary space directly. Moreover, (4) we set a new state-of-the-art for binary neural networks on CIFAR10, CIFAR100 and ImageNet datasets. Code will be made available.

## Bib
@article{bulat2020bats,
  title={Bats: Binary architecture search},
  author={Bulat, Adrian and Martinez, Brais and Tzimiropoulos, Georgios},
  journal={arXiv preprint arXiv:2003.01711},
  year={2020}
}