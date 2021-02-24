# Title
SNAS: stochastic neural architecture search

## Venue
ICLR

## Author
Sirui Xie, Hehui Zheng, Chunxiao Liu, Liang Lin

## Abstract
We propose Stochastic Neural Architecture Search (SNAS), an economical end-to-end solution to Neural Architecture Search (NAS) that trains neural operation parameters and architecture distribution parameters in same round of back-propagation, while maintaining the completeness and differentiability of the NAS pipeline. In this work, NAS is reformulated as an optimization problem on parameters of a joint distribution for the search space in a cell. To leverage the gradient information in generic differentiable loss for architecture search, a novel search gradient is proposed. We prove that this search gradient optimizes the same objective as reinforcement-learning-based NAS, but assigns credits to structural decisions more efficiently. This credit assignment is further augmented with locally decomposable reward to enforce a resource-efficient constraint. In experiments on CIFAR-10, SNAS takes less epochs to find a cell architecture with state-of-the-art accuracy than non-differentiable evolution-based and reinforcement-learning-based NAS, which is also transferable to ImageNet. It is also shown that child networks of SNAS can maintain the validation accuracy in searching, with which attention-based NAS requires parameter retraining to compete, exhibiting potentials to stride towards efficient NAS on big datasets.

## Bib
@inproceedings{
xie2018snas,
title={{SNAS}: stochastic neural architecture search},
author={Sirui Xie and Hehui Zheng and Chunxiao Liu and Liang Lin},
booktitle={International Conference on Learning Representations},
year={2019},
url={https://openreview.net/forum?id=rylqooRqK7},
}