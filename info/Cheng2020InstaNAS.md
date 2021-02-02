# Title 
InstaNAS: Instance-aware Neural Architecture Search

## Author 
An-Chieh Cheng, Chieh Hubert Lin, Da-Cheng Juan, Wei Wei, Min Sun
## Abstract 
Conventional Neural Architecture Search (NAS) aims at finding a single architecture that achieves the best performance, which usually optimizes task related learning objectives such as accuracy. However, a single architecture may not be representative enough for the whole dataset with high diversity and variety. Intuitively, electing domain-expert architectures that are proficient in domain-specific features can further benefit architecture related objectives such as latency. In this paper, we propose InstaNAS---an instance-aware NAS framework---that employs a controller trained to search for a "distribution of architectures" instead of a single architecture; This allows the model to use sophisticated architectures for the difficult samples, which usually comes with large architecture related cost, and shallow architectures for those easy samples. During the inference phase, the controller assigns each of the unseen input samples with a domain expert architecture that can achieve high accuracy with customized inference costs. Experiments within a search space inspired by MobileNetV2 show InstaNAS can achieve up to 48.8% latency reduction without compromising accuracy on a series of datasets against MobileNetV2.
## Bib
@article{DBLP:journals/corr/abs-1811-10201,
  author    = {An{-}Chieh Cheng and
               Chieh Hubert Lin and
               Da{-}Cheng Juan and
               Wei Wei and
               Min Sun},
  title     = {InstaNAS: Instance-aware Neural Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1811.10201},
  year      = {2018},
  url       = {http://arxiv.org/abs/1811.10201},
  archivePrefix = {arXiv},
  eprint    = {1811.10201},
  timestamp = {Wed, 08 Jan 2020 11:59:23 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1811-10201.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}