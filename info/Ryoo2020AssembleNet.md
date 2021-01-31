# Title
AssembleNet: Searching for Multi-Stream Neural Connectivity in Video Architectures

## Author
Michael S. Ryoo, AJ Piergiovanni, Mingxing Tan, Anelia Angelova

## Abstract
Learning to represent videos is a very challenging task both algorithmically and computationally. Standard video CNN architectures have been designed by directly extending architectures devised for image understanding to include the time dimension, using modules such as 3D convolutions, or by using two-stream design to capture both appearance and motion in videos. We interpret a video CNN as a collection of multi-stream convolutional blocks connected to each other, and propose the approach of automatically finding neural architectures with better connectivity and spatio-temporal interactions for video understanding. This is done by evolving a population of overly-connected architectures guided by connection weight learning. 
Architectures combining representations that abstract different input types (i.e., RGB and optical flow) at multiple temporal resolutions are searched for, allowing different types or sources of information to interact with each other. Our method, referred to as AssembleNet, outperforms prior approaches on public video datasets, in some cases by a great margin. We obtain 58.6% mAP on Charades and 34.27% accuracy on Moments-in-Time.

## Bib
@inproceedings{
Ryoo2020AssembleNet:,
title={AssembleNet: Searching for Multi-Stream Neural Connectivity in Video Architectures},
author={Michael S. Ryoo and AJ Piergiovanni and Mingxing Tan and Anelia Angelova},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=SJgMK64Ywr}
}