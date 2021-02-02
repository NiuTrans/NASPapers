# Title 
Towards Oracle Knowledge Distillation with Neural Architecture Search
## Author 
Minsoo Kang, Jonghwan Mun, Bohyung Han
## Abstract 
We present a novel framework of knowledge distillation that is capable of learning powerful and efficient student models from ensemble teacher networks. Our approach addresses the inherent model capacity issue between teacher and student and aims to maximize benefit from teacher models during distillation by reducing their capacity gap. Specifically, we employ a neural architecture search technique to augment useful structures and operations, where the searched network is appropriate for knowledge distillation towards student models and free from sacrificing its performance by fixing the network capacity. We also introduce an oracle knowledge distillation loss to facilitate model search and distillation using an ensemble-based teacher model, where a student network is learned to imitate oracle performance of the teacher. We perform extensive experiments on the image classification datasets---CIFAR-100 and TinyImageNet---using various networks. We also show that searching for a new student model is effective in both accuracy and memory size and that the searched models often outperform their teacher models thanks to neural architecture search with oracle knowledge distillation.
## Bib
@article{DBLP:journals/corr/abs-1911-13019,
  author    = {Minsoo Kang and
               Jonghwan Mun and
               Bohyung Han},
  title     = {Towards Oracle Knowledge Distillation with Neural Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1911.13019},
  year      = {2019},
  url       = {http://arxiv.org/abs/1911.13019},
  archivePrefix = {arXiv},
  eprint    = {1911.13019},
  timestamp = {Wed, 08 Jan 2020 15:28:22 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1911-13019.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}