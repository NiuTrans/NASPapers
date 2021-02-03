# Title 
Evaluating The Search Phase of Neural Architecture Search

## Venue
ICLR

## Author 
Kaicheng Yu, Christian Sciuto, Martin Jaggi, Claudiu Musat, Mathieu Salzmann
## Key Words 
- Neural architecture search
- parameter sharing
- random search
- evaluation framework
## Abstract 
Neural Architecture Search (NAS) aims to facilitate the design of deep networks for new tasks. Existing techniques rely on two stages: searching over the architecture space and validating the best architecture. NAS algorithms are currently compared solely based on their results on the downstream task. While intuitive, this fails to explicitly evaluate the effectiveness of their search strategies. In this paper, we propose to evaluate the NAS search phase.
To this end, we compare the quality of the solutions obtained by NAS search policies with that of random architecture selection. We find that: (i) On average, the state-of-the-art NAS algorithms perform similarly to the random policy; (ii) the widely-used weight sharing strategy degrades the ranking of the NAS candidates to the point of not reflecting their true performance, thus reducing the effectiveness of the search process.
We believe that our evaluation framework will be key to designing NAS strategies that consistently discover architectures superior to random ones.
## Bib
@article{DBLP:journals/corr/abs-1902-08142,
  author    = {Christian Sciuto and
               Kaicheng Yu and
               Martin Jaggi and
               Claudiu Musat and
               Mathieu Salzmann},
  title     = {Evaluating the Search Phase of Neural Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1902.08142},
  year      = {2019},
  url       = {http://arxiv.org/abs/1902.08142},
  archivePrefix = {arXiv},
  eprint    = {1902.08142},
  timestamp = {Tue, 21 May 2019 18:03:38 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1902-08142.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}