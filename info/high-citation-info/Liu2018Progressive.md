# Title
Progressive Neural Architecture Search

## Venue
ECCV

## Author
Chenxi Liu, Barret Zoph, Maxim Neumann, Jonathon Shlens, Wei Hua, Li-Jia Li, Li Fei-Fei, Alan Yuille, Jonathan Huang, Kevin Murphy

## Abstract
We propose a new method for learning the structure of convolutional neural networks (CNNs) that is more efficient than recent state-of-the-art methods based on reinforcement learning and evolutionary algorithms. Our approach uses a sequential model-based optimization (SMBO) strategy, in which we search for structures in order of increasing complexity, while simultaneously learning a surrogate model to guide the search through structure space. Direct comparison under the same search space shows that our method is up to 5 times more efficient than the RL method of Zoph et al. (2018) in terms of number of models evaluated, and 8 times faster in terms of total compute. The structures we discover in this way achieve state of the art classification accuracies on CIFAR-10 and ImageNet.

## Bib
@InProceedings{Liu_2018_ECCV,
author = {Liu, Chenxi and Zoph, Barret and Neumann, Maxim and Shlens, Jonathon and Hua, Wei and Li, Li-Jia and Fei-Fei, Li and Yuille, Alan and Huang, Jonathan and Murphy, Kevin},
title = {Progressive Neural Architecture Search},
booktitle = {Proceedings of the European Conference on Computer Vision (ECCV)},
month = {September},
year = {2018}
}