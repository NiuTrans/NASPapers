# Title 
DARTS: Differentiable Architecture Search

## Venue
ICLR

## Author 
Hanxiao Liu, Karen Simonyan, Yiming Yang
## Abstract 
This paper addresses the scalability challenge of architecture search by formulating the task in a differentiable manner. Unlike conventional approaches of applying evolution or reinforcement learning over a discrete and non-differentiable search space, our method is based on the continuous relaxation of the architecture representation, allowing efficient search of the architecture using gradient descent. Extensive experiments on CIFAR-10, ImageNet, Penn Treebank and WikiText-2 show that our algorithm excels in discovering high-performance convolutional architectures for image classification and recurrent architectures for language modeling, while being orders of magnitude faster than state-of-the-art non-differentiable techniques. Our implementation has been made publicly available to facilitate further research on efficient architecture search algorithms.
## Bib
@article{DBLP:journals/corr/abs-1806-09055,
  author    = {Hanxiao Liu and
               Karen Simonyan and
               Yiming Yang},
  title     = {{DARTS:} Differentiable Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1806.09055},
  year      = {2018},
  url       = {http://arxiv.org/abs/1806.09055},
  archivePrefix = {arXiv},
  eprint    = {1806.09055},
  timestamp = {Mon, 13 Aug 2018 16:49:10 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1806-09055.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}