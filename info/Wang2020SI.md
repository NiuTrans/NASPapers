# Title
SI-VDNAS: Semi-Implicit Variational Dropout for Hierarchical One-shot Neural Architecture Search

## Author
Yaoming Wang, Wenrui Dai, Chenglin Li, Junni Zou, Hongkai Xiong

## Abstract
Bayesian methods have improved the interpretability and stability of neural architecture search (NAS). In this paper, we propose a novel probabilistic approach, namely Semi-Implicit Variational Dropout one-shot Neural Architecture Search (SI-VDNAS), that leverages semi-implicit variational dropout to support architecture search with variable operations and edges. SI-VDNAS achieves stable training that would not be affected by the over-selection of skip-connect operation. Experimental results demonstrate that SI-VDNAS finds a convergent architecture with only 2.7 MB parameters within 0.8 GPU-days and can achieve 2.60% top-1 error rate on CIFAR-10. The convergent architecture can obtain a top-1 error rate of 16.20% and 25.6% when transferred to CIFAR-100 and ImageNet (mobile setting).

## Bib
@inproceedings{ijcai2020-0289,
  title     = {SI-VDNAS: Semi-Implicit Variational Dropout for Hierarchical One-shot Neural Architecture Search},
  author    = {Wang, Yaoming and Dai, Wenrui and Li, Chenglin and Zou, Junni and Xiong, Hongkai},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {2088--2095},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/289},
  url       = {https://doi.org/10.24963/ijcai.2020/289},
}
