# Title
Neural Architecture Search on ImageNet in Four GPU Hours: A Theoretically Inspired Perspective

## Author
Wuyang Chen, Xinyu Gong, Zhangyang Wang

## Abstract
Neural Architecture Search (NAS) has been explosively studied to automate the discovery of top-performer neural networks. Current works require heavy training of supernet or intensive architecture evaluations, thus suffering from heavy resource consumption and often incurring search bias due to truncated training or approximations. Can we select the best neural architectures without involving any training and eliminate a drastic portion of the search cost?
We provide an affirmative answer, by proposing a novel framework called trainingfree neural architecture search (TE-NAS). TE-NAS ranks architectures by analyzing the spectrum of the neural tangent kernel (NTK), and the number of linear regions in the input space. Both are motivated by recent theory advances in deep networks, and can be computed without any training. We show that: (1) these two measurements imply the trainability and expressivity of a neural network; and (2) they strongly correlate with the network’s actual test accuracy. Further on, we design a pruning-based NAS mechanism to achieve a more flexible and superior trade-off between the trainability and expressivity during the search. In NASBench-201 and DARTS search spaces, TE-NAS completes high-quality search but only costs 0.5 and 4 GPU hours with one 1080Ti on CIFAR-10 and ImageNet, respectively. We hope our work to inspire more attempts in bridging between the theoretic findings of deep networks and practical impacts in real NAS applications.

## Bib
@inproceedings{
chen2021neural,
title={Neural Architecture Search on ImageNet in Four {\{}GPU{\}} Hours: A Theoretically Inspired Perspective},
author={Wuyang Chen and Xinyu Gong and Zhangyang Wang},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=Cnon5ezMHtu}
}