# Title
Memory-Efficient Hierarchical Neural Architecture Search for Image Denoising

## Author
Haokui Zhang, Ying Li, Hao Chen, Chunhua Shen

## Abstract
Recently, neural architecture search (NAS) methods have attracted much attention and outperformed manually designed architectures on a few high-level vision tasks. In this paper, we propose HiNAS (Hierarchical NAS), an effort towards employing NAS to automatically design effective neural network architectures for image denoising. HiNAS adopts gradient based search strategies and employs operations with adaptive receptive field to build an flexible hierarchical search space. During the search stage, HiNAS shares cells across different feature levels to save memory and employ an early stopping strategy to avoid the collapse issue in NAS, and considerably accelerate the search speed. The proposed HiNAS is both memory and computation efficient, which takes only about 4.5 hours for searching using a single GPU. We evaluate the effectiveness of our proposed HiNAS on two different datasets, namely an additive white Gaussian noise dataset BSD500, and a realistic noise dataset SIM1800. Experimental results show that the architecture found by HiNAS has fewer parameters and enjoys a faster inference speed, while achieving highly competitive performance compared with state-of-the-art methods. We also present analysis on the architectures found by NAS. HiNAS also shows good performance on experiments for image de-raining.

## Bib
@INPROCEEDINGS{9156867,
  author={H. {Zhang} and Y. {Li} and H. {Chen} and C. {Shen}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Memory-Efficient Hierarchical Neural Architecture Search for Image Denoising}, 
  year={2020},
  volume={},
  number={},
  pages={3654-3663},
  doi={10.1109/CVPR42600.2020.00371}}