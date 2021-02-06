# Title
Sample-Efficient Automated Deep Reinforcement Learning

## Author
Jörg K.H. Franke, Gregor Koehler, André Biedenkapp, Frank Hutter

## Abstract
Despite significant progress in challenging problems across various domains, applying state-of-the-art deep reinforcement learning (RL) algorithms remains challenging due to their sensitivity to the choice of hyperparameters. This sensitivity can partly be attributed to the non-stationarity of the RL problem, potentially requiring different hyperparameter settings at various stages of the learning process. Additionally, in the RL setting, hyperparameter optimization (HPO) requires a large number of environment interactions, hindering the transfer of the successes in RL to real-world applications. In this work, we tackle the issues of sample-efficient and dynamic HPO in RL. We propose a population-based automated RL (AutoRL) framework to meta-optimize arbitrary off-policy RL algorithms. In this framework, we optimize the hyperparameters and also the neural architecture while simultaneously training the agent. By sharing the collected experience across the population, we substantially increase the sample efficiency of the meta-optimization. We demonstrate the capabilities of our sample-efficient AutoRL approach in a case study with the popular TD3 algorithm in the MuJoCo benchmark suite, where we reduce the number of environment interactions needed for meta-optimization by up to an order of magnitude compared to population-based training.

## Bib
@inproceedings{
franke2021sampleefficient,
title={Sample-Efficient Automated Deep Reinforcement Learning},
author={J{\"o}rg K.H. Franke and Gregor Koehler and Andr{\'e} Biedenkapp and Frank Hutter},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=hSjxQ3B7GWq}
}