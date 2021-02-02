# Title
XNAS: Neural Architecture Search with Expert Advice

## Author
Niv Nayman, Asaf Noy, Tal Ridnik, Itamar Friedman, Rong Jin, Lihi Zelnik

## Abstract
This paper introduces a novel optimization method for differential neural architecture search, based on the theory of prediction with expert advice. Its optimization criterion is well fitted for an architecture-selection, i.e., it minimizes the regret incurred by a sub-optimal selection of operations. Unlike previous search relaxations, that require hard pruning of architectures, our method is designed to dynamically wipe out inferior architectures and enhance superior ones. It achieves an optimal worst-case regret bound and suggests the use of multiple learning-rates, based on the amount of information carried by the backward gradients. Experiments show that our algorithm achieves a strong performance over several image classification datasets. Specifically, it obtains an error rate of 1.6% for CIFAR-10, 23.9% for ImageNet under mobile settings, and achieves state-of-the-art results on three additional datasets.

## Bib
@inproceedings{NEURIPS2019_00e26af6,
 author = {Nayman, Niv and Noy, Asaf and Ridnik, Tal and Friedman, Itamar and Jin, Rong and Zelnik, Lihi},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
 pages = {1977--1987},
 publisher = {Curran Associates, Inc.},
 title = {XNAS: Neural Architecture Search with Expert Advice},
 url = {https://proceedings.neurips.cc/paper/2019/file/00e26af6ac3b1c1c49d7c3d79c60d000-Paper.pdf},
 volume = {32},
 year = {2019}
}