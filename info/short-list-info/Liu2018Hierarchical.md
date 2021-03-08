# Title
Hierarchical Representations for Efficient Architecture Search

## Venue
ICLR

## Author
Hanxiao Liu, Karen Simonyan, Oriol Vinyals, Chrisantha Fernando, Koray Kavukcuoglu

## Abstract
We explore efficient neural architecture search methods and show that a simple yet powerful evolutionary algorithm can discover new architectures with excellent performance. Our approach combines a novel hierarchical genetic representation scheme that imitates the modularized design pattern commonly adopted by human experts, and an expressive search space that supports complex topologies. Our algorithm efficiently discovers architectures that outperform a large number of manually designed models for image classification, obtaining top-1 error of 3.6% on CIFAR-10 and 20.3% when transferred to ImageNet, which is competitive with the best existing neural architecture search approaches. We also present results using random search, achieving 0.3% less top-1 accuracy on CIFAR-10 and 0.1% less on ImageNet whilst reducing the search time from 36 hours down to 1 hour.

## Bib
@inproceedings{
liu2018hierarchical,
title={Hierarchical Representations for Efficient Architecture Search},
author={Hanxiao Liu and Karen Simonyan and Oriol Vinyals and Chrisantha Fernando and Koray Kavukcuoglu},
booktitle={International Conference on Learning Representations},
year={2018},
url={https://openreview.net/forum?id=BJQRKzbA-},
}