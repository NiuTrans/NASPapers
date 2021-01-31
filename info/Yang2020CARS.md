# Title
CARS: Continuous Evolution for Efficient Neural Architecture Search

## Author
Zhaohui Yang, Yunhe Wang, Xinghao Chen, Boxin Shi, Chao Xu, Chunjing Xu, Qi Tian, Chang Xu

## Abstract
Searching techniques in most of existing neural architecture search (NAS) algorithms are mainly dominated by differentiable methods for the efficiency reason. In contrast, we develop an efficient continuous evolutionary approach for searching neural networks. Architectures in the population that share parameters within one SuperNet in the latest generation will be tuned over the training dataset with a few epochs. The searching in the next evolution generation will directly inherit both the SuperNet and the population, which accelerates the optimal network generation. The non-dominated sorting strategy is further applied to preserve only results on the Pareto front for accurately updating the SuperNet. Several neural networks with different model sizes and performances will be produced after the continuous search with only 0.4 GPU days. As a result, our framework provides a series of networks with the number of parameters ranging from 3.7M to 5.1M under mobile settings. These networks surpass those produced by the state-of-the-art methods on the benchmark ImageNet dataset.

## Bib
@INPROCEEDINGS{9156384,  author={Z. {Yang} and Y. {Wang} and X. {Chen} and B. {Shi} and C. {Xu} and C. {Xu} and Q. {Tian} and C. {Xu}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={CARS: Continuous Evolution for Efficient Neural Architecture Search},   year={2020},  volume={},  number={},  pages={1826-1835},  doi={10.1109/CVPR42600.2020.00190}}