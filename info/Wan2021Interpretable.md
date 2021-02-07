# Title
Interpretable Neural Architecture Search via Bayesian Optimisation with Weisfeiler-Lehman Kernels

## Author
Xingchen Wan, Binxin Ru, Xiaowen Dong, Michael Osborne

## Abstract
Current neural architecture search (NAS) strategies focus only on finding a single, good, architecture. They offer little insight into why a specific network is performing well, or how we should modify the architecture if we want further improvements. We propose a Bayesian optimisation (BO) approach for NAS that combines the Weisfeiler-Lehman graph kernel with a Gaussian process surrogate. Our method not only optimises the architecture in a highly data-efficient manner, but also affords interpretability by discovering useful network features and their corresponding impact on the network performance. Moreover, our method is capable of capturing the topological structures of the architectures and is scalable to large graphs, thus making the high-dimensional and graph-like search spaces amenable to BO. We demonstrate empirically that our surrogate model is capable of identifying useful motifs which can guide the generation of new architectures. We finally show that our method outperforms existing NAS approaches to achieve the state of the art on both closed- and open-domain search spaces.

## Bib
@inproceedings{
wan2021interpretable,
title={Interpretable Neural Architecture Search via Bayesian Optimisation with Weisfeiler-Lehman Kernels},
author={Xingchen Wan and Binxin Ru and Xiaowen Dong and Michael Osborne},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=j9Rv7qdXjd}
}