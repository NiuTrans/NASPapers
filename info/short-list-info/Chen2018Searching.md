# Title 
Searching for Efficient Multi-Scale Architectures for Dense Image Prediction

## Venue
NeurIPS

## Author 
Liang-Chieh Chen, Maxwell D. Collins, Yukun Zhu, George Papandreou, Barret Zoph, Florian Schroff, Hartwig Adam, Jonathon Shlens

## Abstract 
The design of neural network architectures is an important component for achieving state-of-the-art performance with machine learning systems across a broad array of tasks. Much work has endeavored to design and build architectures automatically through clever construction of a search space paired with simple learning algorithms. Recent progress has demonstrated that such meta-learning methods may exceed scalable human-invented architectures on image classification tasks. An open question is the degree to which such methods may generalize to new domains. In this work we explore the construction of meta-learning techniques for dense image prediction focused on the tasks of scene parsing, person-part segmentation, and semantic image segmentation. Constructing viable search spaces in this domain is challenging because of the multi-scale representation of visual information and the necessity to operate on high resolution imagery. Based on a survey of techniques in dense image prediction, we construct a recursive search space and demonstrate that even with efficient random search, we can identify architectures that outperform human-invented architectures and achieve state-of-the-art performance on three dense prediction tasks including 82.7\% on Cityscapes (street scene parsing), 71.3\% on PASCAL-Person-Part (person-part segmentation), and 87.9\% on PASCAL VOC 2012 (semantic image segmentation). Additionally, the resulting architecture is more computationally efficient, requiring half the parameters and half the computational cost as previous state of the art systems.

## Bib
@article{DBLP:journals/corr/abs-1809-04184,
  author    = {Liang{-}Chieh Chen and
               Maxwell D. Collins and
               Yukun Zhu and
               George Papandreou and
               Barret Zoph and
               Florian Schroff and
               Hartwig Adam and
               Jonathon Shlens},
  title     = {Searching for Efficient Multi-Scale Architectures for Dense Image
               Prediction},
  journal   = {CoRR},
  volume    = {abs/1809.04184},
  year      = {2018},
  url       = {http://arxiv.org/abs/1809.04184},
  archivePrefix = {arXiv},
  eprint    = {1809.04184},
  timestamp = {Fri, 05 Oct 2018 11:34:52 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1809-04184.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}