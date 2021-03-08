# Title 
Neural Architecture Search with Bayesian Optimisation and Optimal Transport

## Venue
NeurIPS

## Author 
Kirthevasan Kandasamy, Willie Neiswanger, Jeff Schneider, Barnabas Poczos, Eric Xing
## Abstract 
Bayesian Optimisation (BO) refers to a class of methods for global optimisation of a function f which is only accessible via point evaluations. It is typically used in settings where f is expensive to evaluate. A common use case for BO in machine learning is model selection, where it is not possible to analytically model the generalisation performance of a statistical model, and we resort to noisy and expensive training and validation procedures to choose the best model. Conventional BO methods have focused on Euclidean and categorical domains, which, in the context of model selection, only permits tuning scalar hyper-parameters of machine learning algorithms. However, with the surge of interest in deep learning, there is an increasing demand to tune neural network \emph{architectures}. In this work, we develop NASBOT, a Gaussian process based BO framework for neural architecture search. To accomplish this, we develop a distance metric in the space of neural network architectures which can be computed efficiently via an optimal transport program. This distance might be of independent interest to the deep learning community as it may find applications outside of BO. We demonstrate that NASBOT outperforms other alternatives for architecture search in several cross validation based model selection tasks on multi-layer perceptrons and convolutional neural networks.
## Bib
@article{DBLP:journals/corr/abs-1802-07191,
  author    = {Kirthevasan Kandasamy and
               Willie Neiswanger and
               Jeff Schneider and
               Barnab{\'{a}}s P{\'{o}}czos and
               Eric P. Xing},
  title     = {Neural Architecture Search with Bayesian Optimisation and Optimal
               Transport},
  journal   = {CoRR},
  volume    = {abs/1802.07191},
  year      = {2018},
  url       = {http://arxiv.org/abs/1802.07191},
  archivePrefix = {arXiv},
  eprint    = {1802.07191},
  timestamp = {Tue, 17 Nov 2020 16:08:03 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1802-07191.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}