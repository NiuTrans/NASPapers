# Title 
A Flexible Approach to Automated RNN Architecture Generation
## Author 
Martin Schrimpf, Stephen Merity, James Bradbury, Richard Socher
## Abstract 
The process of designing neural architectures requires expert knowledge and extensive trial and error. While automated architecture search may simplify these requirements, the recurrent neural network (RNN) architectures generated by existing methods are limited in both flexibility and components. We propose a domain-specific language (DSL) for use in automated architecture search which can produce novel RNNs of arbitrary depth and width. The DSL is flexible enough to define standard architectures such as the Gated Recurrent Unit and Long Short Term Memory and allows the introduction of non-standard RNN components such as trigonometric curves and layer normalization. Using two different candidate generation techniques, random search with a ranking function and reinforcement learning, we explore the novel architectures produced by the RNN DSL for language modeling and machine translation domains. The resulting architectures do not follow human intuition yet perform well on their targeted tasks, suggesting the space of usable RNN architectures is far larger than previously assumed.
## Bib
@article{DBLP:journals/corr/abs-1712-07316,
  author    = {Martin Schrimpf and
               Stephen Merity and
               James Bradbury and
               Richard Socher},
  title     = {A Flexible Approach to Automated {RNN} Architecture Generation},
  journal   = {CoRR},
  volume    = {abs/1712.07316},
  year      = {2017},
  url       = {http://arxiv.org/abs/1712.07316},
  archivePrefix = {arXiv},
  eprint    = {1712.07316},
  timestamp = {Thu, 21 Mar 2019 11:19:44 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1712-07316.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}