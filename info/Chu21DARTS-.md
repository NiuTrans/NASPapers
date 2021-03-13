# Title
DARTS-: Robustly Stepping out of Performance Collapse Without Indicators

## Author
Xiangxiang Chu, Xiaoxing Wang, Bo Zhang, Shun Lu, Xiaolin Wei, Junchi Yan

## Abstract
Despite the fast development of differentiable architecture search (DARTS), it suffers from a standing instability issue regarding searching performance, which extremely limits its application. Existing robustifying methods draw clues from the outcome instead of finding out the causing factor. Various indicators such as Hessian eigenvalues are proposed as a signal of performance collapse, and the searching should be stopped once an indicator reaches a preset threshold.
However, these methods tend to easily reject good architectures if thresholds are inappropriately set, let alone the searching is intrinsically noisy. In this paper, we undertake a more subtle and direct approach to resolve the collapse. 
We first demonstrate that skip connections with a learnable architectural coefficient can easily recover from a disadvantageous state and become dominant.  We conjecture that skip connections profit too much from this privilege, hence causing the collapse for the derived model. Therefore, we propose to factor out this benefit with an auxiliary skip connection, ensuring a fairer competition for all operations. Extensive experiments on various datasets verify that our approach can substantially improve the robustness of DARTS. Our code is available at https://github.com/Meituan-AutoML/DARTS-

## Bib
@inproceedings{
chu2021darts,
title={{\{}DARTS{\}}-: Robustly Stepping out of Performance Collapse Without Indicators},
author={Xiangxiang Chu and Xiaoxing Wang and Bo Zhang and Shun Lu and Xiaolin Wei and Junchi Yan},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=KLH36ELmwIB}
}