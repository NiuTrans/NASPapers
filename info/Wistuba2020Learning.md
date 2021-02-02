# Title 
Learning to Rank Learning Curves
## Author 
Martin Wistuba, Tejaswini Pedapati
## Abstract 
Many automated machine learning methods, such as those for hyperparameter and neural architecture optimization, are computationally expensive because they involve training many different model configurations. In this work, we present a new method that saves computational budget by terminating poor configurations early on in the training. In contrast to existing methods, we consider this task as a ranking and transfer learning problem. We qualitatively show that by optimizing a pairwise ranking loss and leveraging learning curves from other datasets, our model is able to effectively rank learning curves without having to observe many or very long learning curves. We further demonstrate that our method can be used to accelerate a neural architecture search by a factor of up to 100 without a significant performance degradation of the discovered architecture. In further experiments we analyze the quality of ranking, the influence of different model components as well as the predictive behavior of the model.
## Bib
@article{DBLP:journals/corr/abs-2006-03361,
  author    = {Martin Wistuba and
               Tejaswini Pedapati},
  title     = {Learning to Rank Learning Curves},
  journal   = {CoRR},
  volume    = {abs/2006.03361},
  year      = {2020},
  url       = {https://arxiv.org/abs/2006.03361},
  archivePrefix = {arXiv},
  eprint    = {2006.03361},
  timestamp = {Mon, 08 Jun 2020 15:48:39 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2006-03361.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}