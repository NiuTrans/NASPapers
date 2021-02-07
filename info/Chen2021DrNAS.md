# Title
DrNAS: Dirichlet Neural Architecture Search

## Author
Xiangning Chen, Ruochen Wang, Minhao Cheng, Xiaocheng Tang, Cho-Jui Hsieh

## Abstract
This paper proposes a novel differentiable architecture search method by formulating it into a distribution learning problem. We treat the continuously relaxed architecture mixing weight as random variables, modeled by Dirichlet distribution. With recently developed pathwise derivatives, the Dirichlet parameters can be easily optimized with gradient-based optimizer in an end-to-end manner. This formulation improves the generalization ability and induces stochasticity that naturally encourages exploration in the search space. Furthermore, to alleviate the large memory consumption of differentiable NAS, we propose a simple yet effective progressive learning scheme that enables searching directly on large-scale tasks, eliminating the gap between search and evaluation phases. Extensive experiments demonstrate the effectiveness of our method. Specifically, we obtain a test error of 2.46% for CIFAR-10, 23.7% for ImageNet under the mobile setting. On NAS-Bench-201, we also achieve state-of-the-art results on all three datasets and provide insights for the effective design of neural architecture search algorithms.

## Bib
@inproceedings{
chen2021drnas,
title={Dr{\{}NAS{\}}: Dirichlet Neural Architecture Search},
author={Xiangning Chen and Ruochen Wang and Minhao Cheng and Xiaocheng Tang and Cho-Jui Hsieh},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=9FWas6YbmB3}
}