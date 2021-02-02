# Title
DATA: Differentiable ArchiTecture Approximation

## Author
Jianlong Chang, xinbang zhang, Yiwen Guo, GAOFENG MENG, SHIMING XIANG, Chunhong Pan

## Abstract
Neural architecture search (NAS) is inherently subject to the gap of architectures during searching and validating. To bridge this gap, we develop Differentiable ArchiTecture Approximation (DATA) with an Ensemble Gumbel-Softmax (EGS) estimator to automatically approximate architectures during searching and validating in a differentiable manner. Technically, the EGS estimator consists of a group of Gumbel-Softmax estimators, which is capable of converting probability vectors to binary codes and passing gradients from binary codes to probability vectors. Benefiting from such modeling, in searching, architecture parameters and network weights in the NAS model can be jointly optimized with the standard back-propagation, yielding an end-to-end learning mechanism for searching deep models in a large enough search space. Conclusively, during validating, a high-performance architecture that approaches to the learned one during searching is readily built. Extensive experiments on a variety of popular datasets strongly evidence that our method is capable of discovering high-performance architectures for image classification, language modeling and semantic segmentation, while guaranteeing the requisite efficiency during searching.

## Bib
@inproceedings{NEURIPS2019_74071a67,
 author = {Chang, Jianlong and zhang, xinbang and Guo, Yiwen and MENG, GAOFENG and XIANG, SHIMING and Pan, Chunhong},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
 pages = {876--886},
 publisher = {Curran Associates, Inc.},
 title = {DATA: Differentiable ArchiTecture Approximation},
 url = {https://proceedings.neurips.cc/paper/2019/file/74071a673307ca7459bcf75fbd024e09-Paper.pdf},
 volume = {32},
 year = {2019}
}