# Title
FBNetV2: Differentiable Neural Architecture Search for Spatial and Channel Dimensions

## Author
Alvin Wan, Xiaoliang Dai, Peizhao Zhang, Zijian He, Yuandong Tian, Saining Xie, Bichen Wu, Matthew Yu, Tao Xu, Kan Chen, Peter Vajda, Joseph E. Gonzalez

## Abstract
Differentiable Neural Architecture Search (DNAS) has demonstrated great success in designing state-of-the-art, efficient neural networks. However, DARTS-based DNAS's search space is small when compared to other search methods', since all candidate network layers must be explicitly instantiated in memory. To address this bottleneck, we propose a memory and computationally efficient DNAS variant: DMaskingNAS. This algorithm expands the search space by up to 10^14x over conventional DNAS, supporting searches over spatial and channel dimensions that are otherwise prohibitively expensive: input resolution and number of filters. We propose a masking mechanism for feature map reuse, so that memory and computational costs stay nearly constant as the search space expands. Furthermore, we employ effective shape propagation to maximize per-FLOP or per-parameter accuracy. The searched FBNetV2s yield state-of-the-art performance when compared with all previous architectures. With up to 421x less search cost, DMaskingNAS finds models with 0.9% higher accuracy, 15% fewer FLOPs than MobileNetV3-Small; and with similar accuracy but 20% fewer FLOPs than Efficient-B0. Furthermore, our FBNetV2 outperforms MobileNetV3 by 2.6% in accuracy, with equivalent model size. FBNetV2 models are open-sourced at https://github.com/facebookresearch/mobile-vision.

## Bib
@INPROCEEDINGS{9156431,
  author={A. {Wan} and X. {Dai} and P. {Zhang} and Z. {He} and Y. {Tian} and S. {Xie} and B. {Wu} and M. {Yu} and T. {Xu} and K. {Chen} and P. {Vajda} and J. E. {Gonzalez}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={FBNetV2: Differentiable Neural Architecture Search for Spatial and Channel Dimensions}, 
  year={2020},
  volume={},
  number={},
  pages={12962-12971},
  doi={10.1109/CVPR42600.2020.01298}}