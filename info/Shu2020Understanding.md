# Title
Understanding Architectures Learnt by Cell-based Neural Architecture Search

## Author
Yao Shu, Wei Wang, Shaofeng Cai

## Abstract
Neural architecture search (NAS) searches architectures automatically for given tasks, e.g., image classification and language modeling. Improving the search efficiency and effectiveness has attracted increasing attention in recent years. However, few efforts have been devoted to understanding the generated architectures. In this paper, we first reveal that existing NAS algorithms (e.g., DARTS, ENAS) tend to favor architectures with wide and shallow cell structures. These favorable architectures consistently achieve fast convergence and are consequently selected by NAS algorithms. Our empirical and theoretical study further confirms that their fast convergence derives from their smooth loss landscape and accurate gradient information. Nonetheless, these architectures may not necessarily lead to better generalization performance compared with other candidate architectures in the same search space, and therefore further improvement is possible by revising existing NAS algorithms.

## Bib
@inproceedings{
Shu2020Understanding,
title={Understanding Architectures Learnt by Cell-based Neural Architecture Search},
author={Yao Shu and Wei Wang and Shaofeng Cai},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=BJxH22EKPS}
}