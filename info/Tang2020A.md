# Title
A Semi-Supervised Assessor of Neural Architectures

## Author
Yehui Tang, Yunhe Wang, Yixing Xu, Hanting Chen, Boxin Shi, Chao Xu, Chunjing Xu, Qi Tian, Chang Xu

## Abstract
Neural architecture search (NAS) aims to automatically design deep neural networks of satisfactory performance. Wherein, architecture performance predictor is critical to efficiently value an intermediate neural architecture. But for the training of this predictor, a number of neural architectures and their corresponding real performance often have to be collected. In contrast with classical performance predictor optimized in a fully supervised way, this paper suggests a semi-supervised assessor of neural architectures. We employ an auto-encoder to discover meaningful representations of neural architectures. Taking each neural architecture as an individual instance in the search space, we construct a graph to capture their intrinsic similarities, where both labeled and unlabeled architectures are involved. A graph convolutional neural network is introduced to predict the performance of architectures based on the learned representations and their relation modeled by the graph. Extensive experimental results on the NAS-Benchmark-101 dataset demonstrated that our method is able to make a significant reduction on the required fully trained architectures for finding efficient architectures.

## Bib
@INPROCEEDINGS{9157156,  author={Y. {Tang} and Y. {Wang} and Y. {Xu} and H. {Chen} and B. {Shi} and C. {Xu} and C. {Xu} and Q. {Tian} and C. {Xu}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={A Semi-Supervised Assessor of Neural Architectures},   year={2020},  volume={},  number={},  pages={1807-1816},  doi={10.1109/CVPR42600.2020.00188}}