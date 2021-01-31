# Title
Evaluating The Search Phase of Neural Architecture Search

## Author
Kaicheng Yu, Christian Sciuto, Martin Jaggi, Claudiu Musat, Mathieu Salzmann

## Abstract
Neural Architecture Search (NAS) aims to facilitate the design of deep networks for new tasks. Existing techniques rely on two stages: searching over the architecture space and validating the best architecture. NAS algorithms are currently compared solely based on their results on the downstream task. While intuitive, this fails to explicitly evaluate the effectiveness of their search strategies. In this paper, we propose to evaluate the NAS search phase.
To this end, we compare the quality of the solutions obtained by NAS search policies with that of random architecture selection. We find that: (i) On average, the state-of-the-art NAS algorithms perform similarly to the random policy; (ii) the widely-used weight sharing strategy degrades the ranking of the NAS candidates to the point of not reflecting their true performance, thus reducing the effectiveness of the search process.
We believe that our evaluation framework will be key to designing NAS strategies that consistently discover architectures superior to random ones.

## Bib
@inproceedings{
Yu2020Evaluating,
title={Evaluating The Search Phase of Neural Architecture Search},
author={Kaicheng Yu and Christian Sciuto and Martin Jaggi and Claudiu Musat and Mathieu Salzmann},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=H1loF2NFwr}
}