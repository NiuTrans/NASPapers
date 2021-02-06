# Title 
Learning Transferable Architectures for Scalable Image Recognition

## Venue
CVPR

## Author 
Barret Zoph, Vijay Vasudevan, Jonathon Shlens, Quoc V. Le
## Abstract 
Developing neural network image classification models often requires significant architecture engineering. In this paper, we study a method to learn the model architectures directly on the dataset of interest. As this approach is expensive when the dataset is large, we propose to search for an architectural building block on a small dataset and then transfer the block to a larger dataset. The key contribution of this work is the design of a new search space (the "NASNet search space") which enables transferability. In our experiments, we search for the best convolutional layer (or "cell") on the CIFAR-10 dataset and then apply this cell to the ImageNet dataset by stacking together more copies of this cell, each with their own parameters to design a convolutional architecture, named "NASNet architecture". We also introduce a new regularization technique called ScheduledDropPath that significantly improves generalization in the NASNet models. On CIFAR-10 itself, NASNet achieves 2.4% error rate, which is state-of-the-art. On ImageNet, NASNet achieves, among the published works, state-of-the-art accuracy of 82.7% top-1 and 96.2% top-5 on ImageNet. Our model is 1.2% better in top-1 accuracy than the best human-invented architectures while having 9 billion fewer FLOPS - a reduction of 28% in computational demand from the previous state-of-the-art model. When evaluated at different levels of computational cost, accuracies of NASNets exceed those of the state-of-the-art human-designed models. For instance, a small version of NASNet also achieves 74% top-1 accuracy, which is 3.1% better than equivalently-sized, state-of-the-art models for mobile platforms. Finally, the learned features by NASNet used with the Faster-RCNN framework surpass state-of-the-art by 4.0% achieving 43.1% mAP on the COCO dataset.

## Bib
@article{DBLP:journals/corr/ZophVSL17,
  author    = {Barret Zoph and
               Vijay Vasudevan and
               Jonathon Shlens and
               Quoc V. Le},
  title     = {Learning Transferable Architectures for Scalable Image Recognition},
  journal   = {CoRR},
  volume    = {abs/1707.07012},
  year      = {2017},
  url       = {http://arxiv.org/abs/1707.07012},
  archivePrefix = {arXiv},
  eprint    = {1707.07012},
  timestamp = {Mon, 13 Aug 2018 16:48:00 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/ZophVSL17.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}