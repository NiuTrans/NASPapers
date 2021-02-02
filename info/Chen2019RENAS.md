# Title 
RENAS: Reinforced Evolutionary Neural Architecture Search
## Author 
Yukang Chen, Gaofeng Meng, Qian Zhang, Shiming Xiang, Chang Huang, Lisen Mu, Xinggang Wang
## Abstract 
Neural Architecture Search (NAS) is an important yet challenging task in network design due to its high computational consumption. To address this issue, we propose the Reinforced Evolutionary Neural Architecture Search (RE- NAS), which is an evolutionary method with the reinforced mutation for NAS. Our method integrates reinforced mutation into an evolution algorithm for neural architecture exploration, in which a mutation controller is introduced to learn the effects of slight modifications and make mutation actions. The reinforced mutation controller guides the model population to evolve efficiently. Furthermore, as child models can inherit parameters from their parents during evolution, our method requires very limited computational resources. In experiments, we conduct the proposed search method on CIFAR-10 and obtain a powerful network architecture, RENASNet. This architecture achieves a competitive result on CIFAR-10. The explored network architecture is transferable to ImageNet and achieves a new state-of-the-art accuracy, i.e., 75.7% top-1 accuracy with 5.36M parameters on mobile ImageNet. We further test its performance on semantic segmentation with DeepLabv3 on the PASCAL VOC. RENASNet outperforms MobileNet-v1, MobileNet-v2 and NASNet. It achieves 75.83% mIOU without being pre-trained on COCO.
## Bib
@article{DBLP:journals/corr/abs-1808-00193,
  author    = {Yukang Chen and
               Qian Zhang and
               Chang Huang and
               Lisen Mu and
               Gaofeng Meng and
               Xinggang Wang},
  title     = {Reinforced Evolutionary Neural Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1808.00193},
  year      = {2018},
  url       = {http://arxiv.org/abs/1808.00193},
  archivePrefix = {arXiv},
  eprint    = {1808.00193},
  timestamp = {Tue, 10 Mar 2020 09:02:23 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1808-00193.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
