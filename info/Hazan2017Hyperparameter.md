# Title 
Hyperparameter Optimization: A Spectral Approach
## Author 
Elad Hazan, Adam Klivans, Yang Yuan
## Abstract 
We give a simple, fast algorithm for hyperparameter optimization inspired by techniques from the analysis of Boolean functions. We focus on the high-dimensional regime where the canonical example is training a neural network with a large number of hyperparameters. The algorithm --- an iterative application of compressed sensing techniques for orthogonal polynomials --- requires only uniform sampling of the hyperparameters and is thus easily parallelizable.
Experiments for training deep neural networks on Cifar-10 show that compared to state-of-the-art tools (e.g., Hyperband and Spearmint), our algorithm finds significantly improved solutions, in some cases better than what is attainable by hand-tuning. In terms of overall running time (i.e., time required to sample various settings of hyperparameters plus additional computation time), we are at least an order of magnitude faster than Hyperband and Bayesian Optimization. We also outperform Random Search 8x.
Additionally, our method comes with provable guarantees and yields the first improvements on the sample complexity of learning decision trees in over two decades. In particular, we obtain the first quasi-polynomial time algorithm for learning noisy decision trees with polynomial sample complexity.  
## Bib
@article{DBLP:journals/corr/HazanKY17,
  author    = {Elad Hazan and
               Adam R. Klivans and
               Yang Yuan},
  title     = {Hyperparameter Optimization: {A} Spectral Approach},
  journal   = {CoRR},
  volume    = {abs/1706.00764},
  year      = {2017},
  url       = {http://arxiv.org/abs/1706.00764},
  archivePrefix = {arXiv},
  eprint    = {1706.00764},
  timestamp = {Mon, 13 Aug 2018 16:48:09 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/HazanKY17.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}