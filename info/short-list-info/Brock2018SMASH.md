# Title
SMASH: One-Shot Model Architecture Search through HyperNetworks

## Venue
ICLR

## Author
Andrew Brock, Theo Lim, J.M. Ritchie, Nick Weston

## Key Words
- meta-learning
- architecture search
- deep learning
- computer vision

## Abstract
Designing architectures for deep neural networks requires expert knowledge and substantial computation time. We propose a technique to accelerate architecture selection by learning an auxiliary HyperNet that generates the weights of a main model conditioned on that model's architecture. By comparing the relative validation performance of networks with HyperNet-generated weights, we can effectively search over a wide range of architectures at the cost of a single training run. To facilitate this search, we develop a flexible mechanism based on memory read-writes that allows us to define a wide range of network connectivity patterns, with ResNet, DenseNet, and FractalNet blocks as special cases. We validate our method (SMASH) on CIFAR-10 and CIFAR-100, STL-10, ModelNet10, and Imagenet32x32, achieving competitive performance with similarly-sized hand-designed networks.

## Bib
@inproceedings{
brock2018smash,
title={{SMASH}: One-Shot Model Architecture Search through HyperNetworks},
author={Andrew Brock and Theo Lim and J.M. Ritchie and Nick Weston},
booktitle={International Conference on Learning Representations},
year={2018},
url={https://openreview.net/forum?id=rydeCEhs-},
}