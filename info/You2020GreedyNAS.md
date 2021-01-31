# Title
GreedyNAS: Towards Fast One-Shot NAS With Greedy Supernet

## Author
Shan You, Tao Huang, Mingmin Yang, Fei Wang, Chen Qian, Changshui Zhang

## Abstract
Training a supernet matters for one-shot neural architecture search (NAS) methods since it serves as a basic performance estimator for different architectures (paths). Current methods mainly hold the assumption that a supernet should give a reasonable ranking over all paths. They thus treat all paths equally, and spare much effort to train paths. However, it is harsh for a single supernet to evaluate accurately on such a huge-scale search space (e.g., 7^21). In this paper, instead of covering all paths, we ease the burden of supernet by encouraging it to focus more on evaluation of those potentially-good ones, which are identified using a surrogate portion of validation data. Concretely, during training, we propose a multi-path sampling strategy with rejection, and greedily filter the weak paths. The training efficiency is thus boosted since the training space has been greedily shrunk from all paths to those potentially-good ones. Moreover, we further adopt an exploration and exploitation policy by introducing an empirical candidate path pool. Our proposed method GreedyNAS is easy-to-follow, and experimental results on ImageNet dataset indicate that it can achieve better Top-1 accuracy under same search space and FLOPs or latency level, but with only ~60% of supernet training cost. By searching on a larger space, our GreedyNAS can also obtain new state-of-the-art architectures.

## Bib
@INPROCEEDINGS{9156924,  author={S. {You} and T. {Huang} and M. {Yang} and F. {Wang} and C. {Qian} and C. {Zhang}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={GreedyNAS: Towards Fast One-Shot NAS With Greedy Supernet},   year={2020},  volume={},  number={},  pages={1996-2005},  doi={10.1109/CVPR42600.2020.00207}}