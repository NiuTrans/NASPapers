# Title 
GitGraph - Architecture Search Space Creation through Frequent Computational Subgraph Mining
## Author 
Kamil Bennani-Smires, Claudiu Musat, Andreea Hossmann, Michael Baeriswyl
## Abstract 
The dramatic success of deep neural networks across multiple application areas often relies on experts painstakingly designing a network architecture specific to each task. To simplify this process and make it more accessible, an emerging research effort seeks to automate the design of neural network architectures, using e.g. evolutionary algorithms or reinforcement learning or simple search in a constrained space of neural modules.
Considering the typical size of the search space (e.g. $10^{10}$ candidates for a 10-layer network) and the cost of evaluating a single candidate, current architecture search methods are very restricted. They either rely on static pre-built modules to be recombined for the task at hand, or they define a static hand-crafted framework within which they can generate new architectures from the simplest possible operations.
In this paper, we relax these restrictions, by capitalizing on the collective wisdom contained in the plethora of neural networks published in online code repositories. Concretely, we (a) extract and publish GitGraph, a corpus of neural architectures and their descriptions; (b) we create problem-specific neural architecture search spaces, implemented as a textual search mechanism over GitGraph; (c) we propose a method of identifying unique common subgraphs within the architectures solving each problem (e.g., image processing, reinforcement learning), that can then serve as modules in the newly created problem specific neural search space.
## Bib
@article{DBLP:journals/corr/abs-1801-05159,
  author    = {Kamil Bennani{-}Smires and
               Claudiu Musat and
               Andreea Hossmann and
               Michael Baeriswyl},
  title     = {GitGraph - Architecture Search Space Creation through Frequent Computational
               Subgraph Mining},
  journal   = {CoRR},
  volume    = {abs/1801.05159},
  year      = {2018},
  url       = {http://arxiv.org/abs/1801.05159},
  archivePrefix = {arXiv},
  eprint    = {1801.05159},
  timestamp = {Mon, 13 Aug 2018 16:46:56 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1801-05159.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}