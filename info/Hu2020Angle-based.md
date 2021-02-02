# Title
Angle-based Search Space Shrinking for Neural Architecture Search

## Author
Yiming Hu, Yuding Liang, Zichao Guo, Ruosi Wan, Xiangyu Zhang, Yichen Wei, Qingyi Gu, Jian Sun

## Abstract
In this work, we present a simple and general search space shrinking method, called Angle-Based search space Shrinking (ABS), for Neural Architecture Search (NAS). Our approach progressively simplifies the original search space by dropping unpromising candidates, thus can reduce difficulties for existing NAS methods to find superior architectures. In particular, we propose an angle-based metric to guide the shrinking process. We provide comprehensive evidences showing that, in weight-sharing supernet, the proposed metric is more stable and accurate than accuracy-based and magnitude-based metrics to predict the capability of child models. We also show that the angle-based metric can converge fast while training supernet, enabling us to get promising shrunk search spaces efficiently. ABS can easily apply to most of NAS approaches (e.g. SPOS, FairNAS, ProxylessNAS, DARTS and PDARTS). Comprehensive experiments show that ABS can dramatically enhance existing NAS approaches by providing a promising shrunk search space.

## Bib
@inproceedings{hu2020angle,
  title={Angle-based search space shrinking for neural architecture search},
  author={Hu, Yiming and Liang, Yuding and Guo, Zichao and Wan, Ruosi and Zhang, Xiangyu and Wei, Yichen and Gu, Qingyi and Sun, Jian},
  booktitle={European Conference on Computer Vision},
  pages={119--134},
  year={2020},
  organization={Springer}
}