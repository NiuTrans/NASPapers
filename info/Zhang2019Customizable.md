# Title
Customizable Architecture Search for Semantic Segmentation

## Author
Yiheng Zhang, Zhaofan Qiu, Jingen Liu, Ting Yao, Dong Liu, Tao Mei

## Abstract
In this paper, we propose a Customizable Architecture Search (CAS) approach to automatically generate a network architecture for semantic image segmentation. The generated network consists of a sequence of stacked computation cells. A computation cell is represented as a directed acyclic graph, in which each node is a hidden representation (i.e., feature map) and each edge is associated with an operation (e.g., convolution and pooling), which transforms data to a new layer. During the training, the CAS algorithm explores the search space for an optimized computation cell to build a network. The cells of the same type share one architecture but with different weights. In real applications, however, an optimization may need to be conducted under some constraints such as GPU time and model size. To this end, a cost corresponding to the constraint will be assigned to each operation. When an operation is selected during the search, its associated cost will be added to the objective. As a result, our CAS is able to search an optimized architecture with customized constraints. The approach has been thoroughly evaluated on Cityscapes and CamVid datasets, and demonstrates superior performance over several state-of-the-art techniques. More remarkably, our CAS achieves 72.3% mIoU on the Cityscapes dataset with speed of 108 FPS on an Nvidia TitanXp GPU.

## Bib
@INPROCEEDINGS{8953370,
  author={Y. {Zhang} and Z. {Qiu} and J. {Liu} and T. {Yao} and D. {Liu} and T. {Mei}},
  booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Customizable Architecture Search for Semantic Segmentation}, 
  year={2019},
  volume={},
  number={},
  pages={11633-11642},
  doi={10.1109/CVPR.2019.01191}}