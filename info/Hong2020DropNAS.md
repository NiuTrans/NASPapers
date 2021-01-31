# Title
DropNAS: Grouped Operation Dropout for Differentiable Architecture Search

## Author
Weijun Hong, Guilin Li, Weinan Zhang, Ruiming Tang, Yunhe Wang, Zhenguo Li, Yong Yu

## Abstract
Neural architecture search (NAS) has shown encouraging results in automating the architecture design. Recently, DARTS relaxes the search process with a differentiable formulation that leverages weight-sharing and SGD for cost reduction of NAS. In DARTS, all candidate operations are trained simultaneously during the network weight training step. Our empirical results show that this training procedure leads to the co-adaption problem and Matthew Effect: operations with fewer parameters would be trained maturely earlier. This causes two problems: firstly, the operations with more parameters may never have the chance to express the desired function since those with less have already done the job; secondly, the system will punish those underperforming operations by lowering their architecture parameter and backward smaller loss gradients, this causes the Matthew Effect. In this paper, we systematically study these problems and propose a novel grouped operation dropout algorithm named DropNAS to fix the problems with DARTS. Extensive experiments demonstrate that DropNAS solves the above issues and achieves promising performance. Specifically, DropNAS achieves 2.26% test error on CIFAR-10, 16.39% on CIFAR-100 and 23.4% on ImageNet (with the same training hyperparameters as DARTS for a fair comparison). It is also observed that DropNAS is robust across variants of the DARTS search space. Code is available at https://github.com/huawei-noah.

## Bib
@inproceedings{ijcai2020-0322,
  title     = {DropNAS: Grouped Operation Dropout for Differentiable Architecture Search},
  author    = {Hong, Weijun and Li, Guilin and Zhang, Weinan and Tang, Ruiming and Wang, Yunhe and Li, Zhenguo and Yu, Yong},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {2326--2332},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/322},
  url       = {https://doi.org/10.24963/ijcai.2020/322},
}
