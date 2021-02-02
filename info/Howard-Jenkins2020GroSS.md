# Title
GroSS: Group-Size Series Decomposition for Grouped Architecture Search

## Author
Henry Howard-Jenkins, Yiwen Li, Victor A. Prisacariu

## Abstract
We present a novel approach which is able to explore the configuration of grouped convolutions within neural networks. Group-size Series (GroSS) decomposition is a mathematical formulation of tensor factorisation into a series of approximations of increasing rank terms. GroSS allows for dynamic and differentiable selection of factorisation rank, which is analogous to a grouped convolution. Therefore, to the best of our knowledge, GroSS is the first method to enable simultaneous training of differing numbers of groups within a single layer, as well as all possible combinations between layers. In doing so, GroSS is able to train an entire grouped convolution architecture search-space concurrently. We demonstrate this through architecture searches with performance objectives on multiple datasets and networks. GroSS enables more effective and efficient search for grouped convolutional architectures.

## Bib
@inproceedings{howard2020gross,
  title={GroSS: Group-Size Series Decomposition for Grouped Architecture Search},
  author={Howard-Jenkins, Henry and Li, Yiwen and Prisacariu, Victor Adrian},
  booktitle={European Conference on Computer Vision},
  pages={18--33},
  year={2020},
  organization={Springer}
}