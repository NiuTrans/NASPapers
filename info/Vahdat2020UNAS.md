# Title
UNAS: Differentiable Architecture Search Meets Reinforcement Learning

## Author
Arash Vahdat, Arun Mallya, Ming-Yu Liu, Jan Kautz

## Abstract
Neural architecture search (NAS) aims to discover network architectures with desired properties such as high accuracy or low latency. Recently, differentiable NAS (DNAS) has demonstrated promising results while maintaining a search cost orders of magnitude lower than reinforcement learning (RL) based NAS. However, DNAS models can only optimize differentiable loss functions in search, and they require an accurate differentiable approximation of non-differentiable criteria. In this work, we present UNAS, a unified framework for NAS, that encapsulates recent DNAS and RL-based approaches under one framework. Our framework brings the best of both worlds, and it enables us to search for architectures with both differentiable and non-differentiable criteria in one unified framework while maintaining a low search cost. Further, we introduce a new objective function for search based on the generalization gap that prevents the selection of architectures prone to overfitting. We present extensive experiments on the CIFAR-10, CIFAR-100 and ImageNet datasets and we perform search in two fundamentally different search spaces. We show that UNAS obtains the state-of-the-art average accuracy on all three datasets when compared to the architectures searched in the DARTS space. Moreover, we show that UNAS can find an efficient and accurate architecture in the ProxylessNAS search space, that outperforms existing MobileNetV2 based architectures. The source code is available at \url{https://github.com/NVlabs/unas}.

## Bib
@INPROCEEDINGS{9156297,
  author={A. {Vahdat} and A. {Mallya} and M. -Y. {Liu} and J. {Kautz}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={UNAS: Differentiable Architecture Search Meets Reinforcement Learning}, 
  year={2020},
  volume={},
  number={},
  pages={11263-11272},
  doi={10.1109/CVPR42600.2020.01128}}