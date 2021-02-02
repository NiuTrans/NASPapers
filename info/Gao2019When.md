# Title
When NAS Meets Robustness: In Search of Robust Architectures Against Adversarial Attacks

## Author
Minghao Guo, Yuzhe Yang, Rui Xu, Ziwei Liu

## Abstract
Recent advances in adversarial attacks uncover the intrinsic vulnerability of modern deep neural networks. Since then, extensive efforts have been devoted to enhancing the robustness of deep networks via specialized learning algorithms and loss functions. In this work, we take an architectural perspective and investigate the patterns of network architectures that are resilient to adversarial attacks. To obtain the large number of networks needed for this study, we adopt one-shot neural architecture search, training a large network for once and then finetuning the sub-networks sampled therefrom. The sampled architectures together with the accuracies they achieve provide a rich basis for our study. Our ''robust architecture Odyssey'' reveals several valuable observations: 1) densely connected patterns result in improved robustness; 2) under computational budget, adding convolution operations to direct connection edge is effective; 3) flow of solution procedure (FSP) matrix is a good indicator of network robustness. Based on these observations, we discover a family of robust architectures (RobNets). On various datasets, including CIFAR, SVHN, Tiny-ImageNet, and ImageNet, RobNets exhibit superior robustness performance to other widely used architectures. Notably, RobNets substantially improve the robust accuracy (~5% absolute gains) under both white-box and black-box attacks, even with fewer parameter numbers. Code is available at https://github.com/gmh14/RobNets.

## Bib
@INPROCEEDINGS{9156305,
  author={M. {Guo} and Y. {Yang} and R. {Xu} and Z. {Liu} and D. {Lin}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={When NAS Meets Robustness: In Search of Robust Architectures Against Adversarial Attacks}, 
  year={2020},
  volume={},
  number={},
  pages={628-637},
  doi={10.1109/CVPR42600.2020.00071}}