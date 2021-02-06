# Title
Rethinking Architecture Selection in Differentiable NAS

## Author
Ruochen Wang, Minhao Cheng, Xiangning Chen, Xiaocheng Tang, Cho-Jui Hsieh

## Abstract
Differentiable Neural Architecture Search is one of the most popular Neural Architecture Search (NAS) methods for its search efficiency and simplicity, accomplished by jointly optimizing the model weight and architecture parameters in a weight-sharing supernet via gradient-based algorithms. At the end of the search phrase, the operations with the largest architecture parameters will be selected to form the final architecture, with the implicit assumption that the values of architecture parameters reflect the operation strength. While much has been discussed about the supernet's optimization, the architecture selection process has received little attention. We provide empirical and theoretical analysis to show that the magnitude of architecture parameters does not necessarily indicate how much the operation contributes to the supernet's performance. We propose an alternative perturbation-based architecture selection that directly measures each operation's influence on the supernet. We re-evaluate several differentiable NAS methods with the proposed architecture selection and find that it is able to extract significantly improved architectures from the underlying supernets consistently. Furthermore, we find that several failure modes of Darts can be greatly alleviated with the proposed selection method, indicating that much of the poor generalization observed in Darts can be attributed to the failure of magnitude-based architecture selection rather than entirely the optimization of its supernet. Our code will be made publicly available shortly.

## Bib
@inproceedings{
wang2021rethinking,
title={Rethinking Architecture Selection in Differentiable {\{}NAS{\}}},
author={Ruochen Wang and Minhao Cheng and Xiangning Chen and Xiaocheng Tang and Cho-Jui Hsieh},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=PKubaeJkw3}
}