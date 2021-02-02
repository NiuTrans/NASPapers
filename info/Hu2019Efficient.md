# Title
Efficient Forward Architecture Search

## Author
Hanzhang Hu, John Langford, Rich Caruana, Saurajit Mukherjee, Eric J. Horvitz, Debadeepta Dey

## Abstract
We propose a neural architecture search (NAS) algorithm, Petridish, to iteratively add shortcut connections to existing network layers. The added shortcut connections effectively perform gradient boosting on the augmented layers. The proposed algorithm is motivated by the feature selection algorithm forward stage-wise linear regression, since we consider NAS as a generalization of feature selection for regression, where NAS selects shortcuts among layers instead of selecting features. In order to reduce the number of trials of possible connection combinations, we train jointly all possible connections at each stage of growth while leveraging feature selection techniques to choose a subset of them. We experimentally show this process to be an efficient forward architecture search algorithm that can find competitive models using few GPU days in both the search space of repeatable network modules (cell-search) and the space of general networks (macro-search). Petridish is particularly well-suited for warm-starting from existing models crucial for lifelong-learning scenarios.

## Bib
@inproceedings{NEURIPS2019_6c468ec5,
 author = {Hu, Hanzhang and Langford, John and Caruana, Rich and Mukherjee, Saurajit and Horvitz, Eric J and Dey, Debadeepta},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
 pages = {10122--10131},
 publisher = {Curran Associates, Inc.},
 title = {Efficient Forward Architecture Search},
 url = {https://proceedings.neurips.cc/paper/2019/file/6c468ec5a41d65815de23ec1d08d7951-Paper.pdf},
 volume = {32},
 year = {2019}
}