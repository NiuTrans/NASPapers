# Title
MiLeNAS: Efficient Neural Architecture Search via Mixed-Level Reformulation

## Author
Chaoyang He, Haishan Ye, Li Shen, Tong Zhang

## Abstract
Many recently proposed methods for Neural Architecture Search (NAS) can be formulated as bilevel optimization. For efficient implementation, its solution requires approximations of second-order methods. In this paper, we demonstrate that gradient errors caused by such approximations lead to suboptimality, in the sense that the optimization procedure fails to converge to a (locally) optimal solution. To remedy this, this paper proposes MiLeNAS, a mixed-level reformulation for NAS that can be optimized efficiently and reliably. It is shown that even when using a simple first-order method on the mixed-level formulation, MiLeNAS can achieve a lower validation error for NAS problems. Consequently, architectures obtained by our method achieve consistently higher accuracies than those obtained from bilevel optimization. Moreover, MiLeNAS proposes a framework beyond DARTS. It is upgraded via model size-based search and early stopping strategies to complete the search process in around 5 hours. Extensive experiments within the convolutional architecture search space validate the effectiveness of our approach.

## Bib
@INPROCEEDINGS{9156336,
  author={C. {He} and H. {Ye} and L. {Shen} and T. {Zhang}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={MiLeNAS: Efficient Neural Architecture Search via Mixed-Level Reformulation}, 
  year={2020},
  volume={},
  number={},
  pages={11990-11999},
  doi={10.1109/CVPR42600.2020.01201}}