# Title 
Can weight sharing outperform random architecture search? An investigation with TuNAS
## Author 
Gabriel Bender, Hanxiao Liu, Bo Chen, Grace Chu, Shuyang Cheng, Pieter-Jan Kindermans, Quoc Le
## Abstract 
Efficient Neural Architecture Search methods based on weight sharing have shown good promise in democratizing Neural Architecture Search for computer vision models. There is, however, an ongoing debate whether these efficient methods are significantly better than random search. Here we perform a thorough comparison between efficient and random search methods on a family of progressively larger and more challenging search spaces for image classification and detection on ImageNet and COCO. While the efficacies of both methods are problem-dependent, our experiments demonstrate that there are large, realistic tasks where efficient search methods can provide substantial gains over random search. In addition, we propose and evaluate techniques which improve the quality of searched architectures and reduce the need for manual hyper-parameter tuning.
Source code and experiment data are available at [this https URL](https://github.com/google-research/google-research/tree/master/tunas)
## Bib
@article{DBLP:journals/corr/abs-2008-06120,
  author    = {Gabriel Bender and
               Hanxiao Liu and
               Bo Chen and
               Grace Chu and
               Shuyang Cheng and
               Pieter{-}Jan Kindermans and
               Quoc Le},
  title     = {Can weight sharing outperform random architecture search? An investigation
               with TuNAS},
  journal   = {CoRR},
  volume    = {abs/2008.06120},
  year      = {2020},
  url       = {https://arxiv.org/abs/2008.06120},
  archivePrefix = {arXiv},
  eprint    = {2008.06120},
  timestamp = {Thu, 03 Dec 2020 16:48:26 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2008-06120.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}