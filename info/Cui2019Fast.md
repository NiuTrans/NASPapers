# Title 
Fast and Practical Neural Architecture Search
## Author 
Jiequan Cui, Pengguang Chen, Ruiyu Li, Shu Liu, Xiaoyong Shen, Jiaya Jia
## Abstract 
In this paper, we propose a fast and practical neural architecture search (FPNAS) framework for automatic network design. FPNAS aims to discover extremely efficient networks with less than 300M FLOPs. Different from previous NAS methods, our approach searches for the whole network architecture to guarantee block diversity instead of stacking a set of similar blocks repeatedly. We model the search process as a bi-level optimization problem and propose an approximation solution. On CIFAR-10, our approach is capable of design networks with comparable performance to state-of-the-arts while using orders of magnitude less computational resource with only 20 GPU hours. Experimental results on ImageNet and ADE20K datasets further demonstrate transferability of the searched networks.
## Bib
@InProceedings{Cui_2019_ICCV,
author = {Cui, Jiequan and Chen, Pengguang and Li, Ruiyu and Liu, Shu and Shen, Xiaoyong and Jia, Jiaya},
title = {Fast and Practical Neural Architecture Search},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}