# Title
Progressive Differentiable Architecture Search: Bridging the Depth Gap Between Search and Evaluation

## Author
Xin Chen, Lingxi Xie, Jun Wu, Qi Tian

## Abstract
Recently, differentiable search methods have made major progress in reducing the computational costs of neural architecture search. However, these approaches often report lower accuracy in evaluating the searched architecture or transferring it to another dataset. This is arguably due to the large gap between the architecture depths in search and evaluation scenarios. In this paper, we present an efficient algorithm which allows the depth of searched architectures to grow gradually during the training procedure. This brings two issues, namely, heavier computational overheads and weaker search stability, which we solve using search space approximation and regularization, respectively. With a significantly reduced search time ( 7 hours on a single GPU), our approach achieves state-of-the-art performance on both the proxy dataset (CIFAR10 or CIFAR100) and the target dataset (ImageNet). Code is available at https://github.com/chenxin061/pdarts

## Bib
@InProceedings{Chen_2019_ICCV,
author = {Chen, Xin and Xie, Lingxi and Wu, Jun and Tian, Qi},
title = {Progressive Differentiable Architecture Search: Bridging the Depth Gap Between Search and Evaluation},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}