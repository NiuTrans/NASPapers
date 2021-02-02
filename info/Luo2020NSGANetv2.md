# Title 
NSGANetV2: Evolutionary Multi-Objective Surrogate-Assisted Neural Architecture Search
## Author 
Zhichao Lu, Kalyanmoy Deb, Erik Goodman, Wolfgang Banzhaf, Vishnu Naresh Boddeti
## Abstract 
In this paper, we propose an efficient NAS algorithm for generating task-specific models that are competitive under multiple competing objectives. It comprises of two surrogates, one at the architecture level to improve sample efficiency and one at the weights level, through a supernet, to improve gradient descent training efficiency. On standard benchmark datasets (C10, C100, ImageNet), the resulting models, dubbed NSGANetV2, either match or outperform models from existing approaches with the search being orders of magnitude more sample efficient. Furthermore, we demonstrate the effectiveness and versatility of the proposed method on six diverse non-standard datasets, e.g. STL-10, Flowers102, Oxford Pets, FGVC Aircrafts etc. In all cases, NSGANetV2s improve the state-of-the-art (under mobile setting), suggesting that NAS can be a viable alternative to conventional transfer learning approaches in handling diverse scenarios such as small-scale or fine-grained datasets. Code is available at [this https URL](https://github.com/mikelzc1990/nsganetv2)
## Bib
@article{DBLP:journals/corr/abs-2007-10396,
  author    = {Zhichao Lu and
               Kalyanmoy Deb and
               Erik D. Goodman and
               Wolfgang Banzhaf and
               Vishnu Naresh Boddeti},
  title     = {NSGANetV2: Evolutionary Multi-Objective Surrogate-Assisted Neural
               Architecture Search},
  journal   = {CoRR},
  volume    = {abs/2007.10396},
  year      = {2020},
  url       = {https://arxiv.org/abs/2007.10396},
  archivePrefix = {arXiv},
  eprint    = {2007.10396},
  timestamp = {Tue, 28 Jul 2020 14:46:12 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2007-10396.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}