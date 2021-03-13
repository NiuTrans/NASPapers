# Title
Zero-Cost Proxies for Lightweight NAS

## Author
Mohamed S Abdelfattah, Abhinav Mehrotra, Łukasz Dudziak, Nicholas Donald Lane

## Abstract
Neural Architecture Search (NAS) is quickly becoming the standard methodology to design neural network models. However, NAS is typically compute-intensive because multiple models need to be evaluated before choosing the best one. To reduce the computational power and time needed, a proxy task is often used for evaluating each model instead of full training. In this paper, we evaluate conventional reduced-training proxies and quantify how well they preserve ranking between multiple models during search when compared with the rankings produced by final trained accuracy. We propose a series of zero-cost proxies, based on recent pruning literature, that use just a single minibatch of training data to compute a model's score. Our zero-cost proxies use 3 orders of magnitude less computation but can match and even outperform conventional proxies. For example, Spearman's rank correlation coefficient between final validation accuracy and our best zero-cost proxy on NAS-Bench-201 is 0.82, compared to 0.61 for EcoNAS (a recently proposed reduced-training proxy). Finally, we use these zero-cost proxies to enhance existing NAS search algorithms such as random search, reinforcement learning, evolutionary search and predictor-based search. For all search methodologies and across three different NAS datasets, we are able to significantly improve sample efficiency, and thereby decrease computation, by using our zero-cost proxies. For example on NAS-Bench-101, we achieved the same accuracy 4x quicker than the best previous result.

## Bib
@inproceedings{
abdelfattah2021zerocost,
title={Zero-Cost Proxies for Lightweight {\{}NAS{\}}},
author={Mohamed S Abdelfattah and Abhinav Mehrotra and {\L}ukasz Dudziak and Nicholas Donald Lane},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=0cmMMy8J5q}
}