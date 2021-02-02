# Title
Auto-ReID: Searching for a Part-Aware ConvNet for Person Re-Identification

## Author
Ruijie Quan, Xuanyi Dong, Yu Wu, Linchao Zhu, Yi Yang

## Abstract
Prevailing deep convolutional neural networks (CNNs) for person re-IDentification (reID) are usually built upon ResNet or VGG backbones, which were originally designed for classification. Because reID is different from classification, the architecture should be modified accordingly. We propose to automatically search for a CNN architecture that is specifically suitable for the reID task. There are three aspects to be tackled. First, body structural information plays an important role in reID but it is not encoded in backbones. Second, Neural Architecture Search (NAS) automates the process of architecture design without human effort, but no existing NAS methods incorporate the structure information of input images. Third, reID is essentially a retrieval task but current NAS algorithms are merely designed for classification. To solve these problems, we propose a retrieval-based search algorithm over a specifically designed reID search space, named Auto-ReID. Our Auto-ReID enables the automated approach to find an efficient and effective CNN architecture for reID. Extensive experiments demonstrate that the searched architecture achieves state-of-the-art performance while reducing 50% parameters and 53% FLOPs compared to others.

## Bib
@InProceedings{Quan_2019_ICCV,
author = {Quan, Ruijie and Dong, Xuanyi and Wu, Yu and Zhu, Linchao and Yang, Yi},
title = {Auto-ReID: Searching for a Part-Aware ConvNet for Person Re-Identification},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}