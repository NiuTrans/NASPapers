# Title 
Towards modular and programmable architecture search

## Author 
Renato Negrinho, Darshan Patil, Nghia Le, Daniel Ferreira, Matthew Gormley, Geoffrey Gordon

## Abstract 
Neural architecture search methods are able to find high performance deep learning architectures with minimal effort from an expert. However, current systems focus on specific use-cases (e.g. convolutional image classifiers and recurrent language models), making them unsuitable for general use-cases that an expert might wish to write. Hyperparameter optimization systems are general-purpose but lack the constructs needed for easy application to architecture search. In this work, we propose a formal language for encoding search spaces over general computational graphs. The language constructs allow us to write modular, composable, and reusable search space encodings and to reason about search space design. We use our language to encode search spaces from the architecture search literature. The language allows us to decouple the implementations of the search space and the search algorithm, allowing us to expose search spaces to search algorithms through a consistent interface. Our experiments show the ease with which we can experiment with different combinations of search spaces and search algorithms without having to implement each combination from scratch. We release an implementation of our language with this paper.
## Bib
@article{DBLP:journals/corr/abs-1909-13404,
  author    = {Renato Negrinho and
               Darshan Patil and
               Nghia Le and
               Daniel Ferreira and
               Matthew R. Gormley and
               Geoffrey J. Gordon},
  title     = {Towards modular and programmable architecture search},
  journal   = {CoRR},
  volume    = {abs/1909.13404},
  year      = {2019},
  url       = {http://arxiv.org/abs/1909.13404},
  archivePrefix = {arXiv},
  eprint    = {1909.13404},
  timestamp = {Wed, 02 Oct 2019 13:04:08 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1909-13404.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}