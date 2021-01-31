# Title
RENAS: Reinforced Evolutionary Neural Architecture Search

## Author
Yukang Chen, Gaofeng Meng, Qian Zhang, Shiming Xiang, Chang Huang, Lisen Mu, Xinggang Wang

## Abstract
Neural Architecture Search (NAS) is an important yet challenging task in network design due to its high computational consumption. To address this issue, we propose the Reinforced Evolutionary Neural Architecture Search (RENAS), which is an evolutionary method with reinforced mutation for NAS. Our method integrates reinforced mutation into an evolution algorithm for neural architecture exploration, in which a mutation controller is introduced to learn the effects of slight modifications and make mutation actions. The reinforced mutation controller guides the model population to evolve efficiently. Furthermore, as child models can inherit parameters from their parents during evolution, our method requires very limited computational resources. In experiments, we conduct the proposed search method on CIFAR-10 and obtain a powerful network architecture, RENASNet. This architecture achieves a competitive result on CIFAR-10. The explored network architecture is transferable to ImageNet and achieves a new state-of-the-art accuracy, i.e., 75.7% top-1 accuracy with 5.36M parameters on mobile ImageNet. We further test its performance on semantic segmentation with DeepLabv3 on the PASCAL VOC. RENASNet outperforms MobileNet-v1, MobileNet-v2 and NASNet. It achieves 75.83% mIOU without being pretrained on COCO.

## Bib
@INPROCEEDINGS{8953426,  author={Y. {Chen} and G. {Meng} and Q. {Zhang} and S. {Xiang} and C. {Huang} and L. {Mu} and X. {Wang}},  booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={RENAS: Reinforced Evolutionary Neural Architecture Search},   year={2019},  volume={},  number={},  pages={4782-4791},  doi={10.1109/CVPR.2019.00492}}