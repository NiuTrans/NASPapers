# Title
Neural Epitome Search for Architecture-Agnostic Network Compression

## Author
Daquan Zhou, Xiaojie Jin, Qibin Hou, Kaixin Wang, Jianchao Yang, Jiashi Feng

## Abstract
Traditional compression methods including network pruning, quantization, low rank factorization and knowledge distillation all assume that network architectures and parameters should be hardwired.  In this work, we propose a new perspective on network compression, i.e., network parameters can be disentangled from the architectures.  From this viewpoint, we present the Neural Epitome Search (NES), a new neural network compression approach that learns to find compact yet expressive epitomes for weight parameters of a specified network architecture end-to-end. The complete network to compress can be generated from the learned epitome via a novel transformation method that adaptively transforms the epitomes to match shapes of the given architecture. Compared with existing compression methods, NES allows the weight tensors to be independent of the architecture design and hence can achieve a good trade-off between model compression rate and performance given a specific model size constraint. Experiments demonstrate that, on ImageNet, when taking MobileNetV2 as backbone, our approach improves the full-model baseline by 1.47% in top-1 accuracy with 25% MAdd reduction and AutoML for Model Compression (AMC) by 2.5% with nearly the same compression ratio. Moreover, taking EfficientNet-B0 as baseline, our NES yields an improvement of 1.2% but are with 10% less MAdd.  In particular, our method achieves a new state-of-the-art results of 77.5% under mobile settings (<350M MAdd). Code will be made publicly available.

## Bib
@inproceedings{
Zhou2020Neural,
title={Neural Epitome Search for Architecture-Agnostic Network Compression},
author={Daquan Zhou and Xiaojie Jin and Qibin Hou and Kaixin Wang and Jianchao Yang and Jiashi Feng},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=HyxjOyrKvr}
}