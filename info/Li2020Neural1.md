# Title
Neural Architecture Search on Acoustic Scene Classification

## Author
Jixiang Li, Chuming Liang, Bo Zhang, Zhao Wang, Fei Xiang, Xiangxiang Chu

## Abstract
Convolutional neural networks are widely adopted in Acoustic Scene Classification (ASC) tasks, but they generally carry a heavy computational burden. In this work, we propose a high-performance yet lightweight baseline network inspired by MobileNetV2, which replaces square convolutional kernels with unidirectional ones to extract features alternately in temporal and frequency dimensions. Furthermore, we explore a dynamic architecture space built on the basis of the proposed baseline with the recent Neural Architecture Search (NAS) paradigm, which first train a supernet that incorporates all candidate architectures and then apply a well-known evolutionary algorithm NSGA-II to discover more efficient networks with higher accuracy and lower computational cost from the supernet. Experimental results demonstrate that our searched network is competent in ASC tasks, which achieves 90.3% F1-score on the DCASE2018 task 5 evaluation set, marking a new state-of-the-art performance while saving 25% of FLOPs compared to our baseline network.

## Bib
@inproceedings{Li2020,
  author={Jixiang Li and Chuming Liang and Bo Zhang and Zhao Wang and Fei Xiang and Xiangxiang Chu},
  title={{Neural Architecture Search on Acoustic Scene Classification}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={1171--1175},
  doi={10.21437/Interspeech.2020-0057},
  url={http://dx.doi.org/10.21437/Interspeech.2020-0057}
}