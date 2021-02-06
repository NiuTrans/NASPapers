# Title
Rapid Neural Architecture Search by Learning to Generate Graphs from Datasets

## Author
Hayeon Lee, Eunyoung Hyung, Sung Ju Hwang

## Abstract
Despite the success of recent Neural Architecture Search (NAS) methods on various tasks which have shown to output networks that largely outperform human-designed networks, conventional NAS methods have mostly tackled the optimization of searching for the network architecture for a single task (dataset), which does not generalize well across multiple tasks (datasets). Moreover, since such task-specific methods search for a neural architecture from scratch for every given task, they incur a large computational cost, which is problematic when the time and monetary budget are limited. In this paper, we propose an efficient NAS framework that is trained once on a database consisting of datasets and pretrained networks and can rapidly search a neural architecture for a novel dataset. The proposed MetaD2A (Meta Dataset-to-Architecture) model can stochastically generate graphs (architectures) from a given set (dataset) via a cross-modal latent space learned with amortized meta-learning. Moreover, we also propose a meta-performance predictor to estimate and select the best architecture from those sampled from MetaD2A. The experimental results demonstrate that our model meta-learned on subsets of ImageNet-1K and architectures from NAS-Bench 201 search space successfully generalizes to multiple benchmark datasets including CIFAR-10 and CIFAR-100, with the search time of less than 30 GPU seconds on CIFAR-10. We believe that the MetaD2A proposes a new research direction for rapid NAS as well as ways to utilize the knowledge from rich databases of datasets and architectures accumulated over the past years.

## Bib
@inproceedings{
lee2021rapid,
title={Rapid Neural Architecture Search by Learning to Generate Graphs from Datasets},
author={Hayeon Lee and Eunyoung Hyung and Sung Ju Hwang},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=rkQuFUmUOg3}
}