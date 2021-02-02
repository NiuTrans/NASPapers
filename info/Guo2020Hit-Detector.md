# Title
Hit-Detector: Hierarchical Trinity Architecture Search for Object Detection

## Author
Jianyuan Guo, Kai Han, Yunhe Wang, Chao Zhang, Zhaohui Yang, Han Wu, Xinghao Chen, Chang Xu

## Abstract
Neural Architecture Search (NAS) has achieved great success in image classification task. Some recent works have managed to explore the automatic design of efficient backbone or feature fusion layer for object detection. However, these methods focus on searching only one certain component of object detector while leaving others manually designed. We identify the inconsistency between searched component and manually designed ones would withhold the detector of stronger performance. To this end, we propose a hierarchical trinity search framework to simultaneously discover efficient architectures for all components (i.e. backbone, neck, and head) of object detector in an end-to-end manner. In addition, we empirically reveal that different parts of the detector prefer different operators. Motivated by this, we employ a novel scheme to automatically screen different sub search spaces for different components so as to perform the end-to-end search for each component on the corresponding sub search space efficiently. Without bells and whistles, our searched architecture, namely Hit-Detector, achieves 41.4% mAP on COCO minival set with 27M parameters. Our implementation is available at https://github.com/ggjy/HitDet.pytorch.

## Bib
@INPROCEEDINGS{9156291,
  author={J. {Guo} and K. {Han} and Y. {Wang} and C. {Zhang} and Z. {Yang} and H. {Wu} and X. {Chen} and C. {Xu}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Hit-Detector: Hierarchical Trinity Architecture Search for Object Detection}, 
  year={2020},
  volume={},
  number={},
  pages={11402-11411},
  doi={10.1109/CVPR42600.2020.01142}}