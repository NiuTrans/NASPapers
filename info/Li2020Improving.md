# Title
Improving One-Shot NAS by Suppressing the Posterior Fading

## Author
Xiang Li, Chen Lin, Chuming Li, Ming Sun, Wei Wu, Junjie Yan, Wanli Ouyang

## Abstract
Neural architecture search (NAS) has demonstrated much success in automatically designing effective neural network architectures. To improve the efficiency of NAS, previous approaches adopt weight sharing method to force all models share the same set of weights. However, it has been observed that a model performing better with shared weights does not necessarily perform better when trained alone. In this paper, we analyse existing weight sharing one-shot NAS approaches from a Bayesian point of view and identify the Posterior Fading problem, which compromises the effectiveness of shared weights. To alleviate this problem, we present a novel approach to guide the parameter posterior towards its true distribution. Moreover, a hard latency constraint is introduced during the search so that the desired latency can be achieved. The resulted method, namely Posterior Convergent NAS (PC-NAS), achieves state-of-the-art performance under standard GPU latency constraint on ImageNet.

## Bib
@INPROCEEDINGS{9156314,  author={X. {Li} and C. {Lin} and C. {Li} and M. {Sun} and W. {Wu} and J. {Yan} and W. {Ouyang}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={Improving One-Shot NAS by Suppressing the Posterior Fading},   year={2020},  volume={},  number={},  pages={13833-13842},  doi={10.1109/CVPR42600.2020.01385}}