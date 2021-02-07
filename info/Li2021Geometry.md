# Title
Geometry-Aware Gradient Algorithms for Neural Architecture Search

## Author
Liam Li, Mikhail Khodak, Nina Balcan, Ameet Talwalkar

## Abstract
Recent state-of-the-art methods for neural architecture search (NAS) exploit gradient-based optimization by relaxing the problem into continuous optimization over architectures and shared-weights, a noisy process that remains poorly understood. We argue for the study of single-level empirical risk minimization to understand NAS with weight-sharing, reducing the design of NAS methods to devising optimizers and regularizers that can quickly obtain high-quality solutions to this problem. Invoking the theory of mirror descent, we present a geometry-aware framework that exploits the underlying structure of this optimization to return sparse architectural parameters, leading to simple yet novel algorithms that enjoy fast convergence guarantees and achieve state-of-the-art accuracy on the latest NAS benchmarks in computer vision. Notably, we exceed the best published results for both CIFAR and ImageNet on both the DARTS search space and NAS-Bench-201; on the latter we achieve near-oracle-optimal performance on CIFAR-10 and CIFAR-100. Together, our theory and experiments demonstrate a principled way to co-design optimizers and continuous relaxations of discrete NAS search spaces.

## Bib
@inproceedings{
li2021geometryaware,
title={Geometry-Aware Gradient Algorithms for Neural Architecture Search},
author={Liam Li and Mikhail Khodak and Nina Balcan and Ameet Talwalkar},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=MuSYkd1hxRP}
}