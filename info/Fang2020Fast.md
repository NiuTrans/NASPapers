# Title
Fast Neural Network Adaptation via Parameter Remapping and Architecture Search

## Author
Jiemin Fang*, Yuzhu Sun*, Kangjian Peng*, Qian Zhang, Yuan Li, Wenyu Liu, Xinggang Wang

## Abstract
Deep neural networks achieve remarkable performance in many computer vision tasks. Most state-of-the-art~(SOTA) semantic segmentation and object detection approaches reuse neural network architectures designed for image classification as the backbone, commonly pre-trained on ImageNet. However, performance gains can be achieved by designing network architectures specifically for detection and segmentation, as shown by recent neural architecture search (NAS) research for detection and segmentation. One major challenge though, is that ImageNet pre-training of the search space representation (a.k.a. super network) or the searched networks incurs huge computational cost. In this paper, we propose a Fast Neural Network Adaptation (FNA) method, which can adapt both the architecture and parameters of a seed network (e.g. a high performing manually designed backbone) to become a network with different depth, width, or kernels via a Parameter Remapping technique, making it possible to utilize NAS for detection/segmentation tasks a lot more efficiently. In our experiments, we conduct FNA on MobileNetV2 to obtain new networks for both segmentation and detection that clearly out-perform existing networks designed both manually and by NAS. The total computation cost of FNA is significantly less than SOTA segmentation/detection NAS approaches: 1737 less than DPC, 6.8 less than Auto-DeepLab and 7.4 less than DetNAS. The code is available at https://github.com/JaminFong/FNA .

## Bib
@inproceedings{
Fang*2020Fast,
title={Fast Neural Network Adaptation via Parameter Remapping and Architecture Search},
author={Jiemin Fang* and Yuzhu Sun* and Kangjian Peng* and Qian Zhang and Yuan Li and Wenyu Liu and Xinggang Wang},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=rklTmyBKPH}
}