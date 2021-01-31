# Title
Resource Constrained Neural Network Architecture Search: Will a Submodularity Assumption Help?

## Author
Yunyang Xiong, Ronak Mehta, Vikas Singh

## Abstract
The design of neural network architectures is frequently either based on human expertise using trial/error and empirical feedback or tackled via large scale reinforcement learning strategies performed over distinct discrete architecture choices. In the latter case, the optimization is often non-differentiable and also not very amenable to derivative-free optimization methods. Most methods in use today require sizable computational resources. And if we want networks that additionally satisfy resource constraints, the above challenges are exacerbated because the search must now balance accuracy with certain budget constraints on resources. We formulate this problem as the optimization of a set function -- we find that the empirical behavior of this set function often (but not always) satisfies marginal gain and monotonicity principles -- properties central to the idea of submodularity. Based on this observation, we adapt algorithms within discrete optimization to obtain heuristic schemes for neural network architecture search, where we have resource constraints on the architecture. This simple scheme when applied on CIFAR-100 and ImageNet, identifies resource-constrained architectures with quantifiably better performance than current state-of-the-art models designed for mobile devices. Specifically, we find high-performing architectures with fewer parameters and computations by a search method that is much faster.


## Bib
@InProceedings{Xiong_2019_ICCV,
author = {Xiong, Yunyang and Mehta, Ronak and Singh, Vikas},
title = {Resource Constrained Neural Network Architecture Search: Will a Submodularity Assumption Help?},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}