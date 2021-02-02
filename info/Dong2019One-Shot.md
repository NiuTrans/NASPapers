# Title
One-Shot Neural Architecture Search via Self-Evaluated Template Network

## Author
Xuanyi Dong, Yi Yang

## Abstract
Neural architecture search (NAS) aims to automate the search procedure of architecture instead of manual design. Even if recent NAS approaches finish the search within days, lengthy training is still required for a specific architecture candidate to get the parameters for its accurate evaluation. Recently one-shot NAS methods are proposed to largely squeeze the tedious training process by sharing parameters across candidates. In this way, the parameters for each candidate can be directly extracted from the shared parameters instead of training them from scratch. However, they have no sense of which candidate will perform better until evaluation so that the candidates to evaluate are randomly sampled and the top-1 candidate is considered the best. In this paper, we propose a Self-Evaluated Template Network (SETN) to improve the quality of the architecture candidates for evaluation so that it is more likely to cover competitive candidates. SETN consists of two components: (1) an evaluator, which learns to indicate the probability of each individual architecture being likely to have a lower validation loss. The candidates for evaluation can thus be selectively sampled according to this evaluator. (2) a template network, which shares parameters among all candidates to amortize the training cost of generated candidates. In experiments, the architecture found by SETN achieves the state-of-the-art performance on CIFAR and ImageNet benchmarks within comparable computation costs.

## Bib
@InProceedings{Dong_2019_ICCV,
author = {Dong, Xuanyi and Yang, Yi},
title = {One-Shot Neural Architecture Search via Self-Evaluated Template Network},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}