# Title 
Teacher Guided Architecture Search
## Author 
Pouya Bashivan, Mark Tensen, James J DiCarlo

## Abstract 
Much of the recent improvement in neural networks for computer vision has resulted from discovery of new networks architectures. Most prior work has used the performance of candidate models following limited training to automatically guide the search in a feasible way. Could further gains in computational efficiency be achieved by guiding the search via measurements of a high performing network with unknown detailed architecture (e.g. the primate visual system)? As one step toward this goal, we use representational similarity analysis to evaluate the similarity of internal activations of candidate networks with those of a (fixed, high performing) teacher network. We show that adopting this evaluation metric could produce up to an order of magnitude in search efficiency over performance-guided methods. Our approach finds a convolutional cell structure with similar performance as was previously found using other methods but at a total computational cost that is two orders of magnitude lower than Neural Architecture Search (NAS) and more than four times lower than progressive neural architecture search (PNAS). We further show that measurements from only ~300 neurons from primate visual system provides enough signal to find a network with an Imagenet top-1 error that is significantly lower than that achieved by performance-guided architecture search alone. These results suggest that representational matching can be used to accelerate network architecture search in cases where one has access to some or all of the internal representations of a teacher network of interest, such as the brain's sensory processing networks.
## Bib
@article{DBLP:journals/corr/abs-1808-01405,
  author    = {Pouya Bashivan and
               Mark Tensen and
               James J. DiCarlo},
  title     = {Teacher Guided Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1808.01405},
  year      = {2018},
  url       = {http://arxiv.org/abs/1808.01405},
  archivePrefix = {arXiv},
  eprint    = {1808.01405},
  timestamp = {Sun, 02 Sep 2018 15:01:55 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1808-01405.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}