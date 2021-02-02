# Title 
Continual and Multi-Task Architecture Search
## Author 
Ramakanth Pasunuru, Mohit Bansal
## Abstract 
Architecture search is the process of automatically learning the neural model or cell structure that best suits the given task. Recently, this approach has shown promising performance improvements (on language modeling and image classification) with reasonable training speed, using a weight sharing strategy called Efficient Neural Architecture Search (ENAS). In our work, we first introduce a novel continual architecture search (CAS) approach, so as to continually evolve the model parameters during the sequential training of several tasks, without losing performance on previously learned tasks (via block-sparsity and orthogonality constraints), thus enabling life-long learning. Next, we explore a multi-task architecture search (MAS) approach over ENAS for finding a unified, single cell structure that performs well across multiple tasks (via joint controller rewards), and hence allows more generalizable transfer of the cell structure knowledge to an unseen new task. We empirically show the effectiveness of our sequential continual learning and parallel multi-task learning based architecture search approaches on diverse sentence-pair classification tasks (GLUE) and multimodal-generation based video captioning tasks. Further, we present several ablations and analyses on the learned cell structures.
## Bib
@article{DBLP:journals/corr/abs-1906-05226,
  author    = {Ramakanth Pasunuru and
               Mohit Bansal},
  title     = {Continual and Multi-Task Architecture Search},
  journal   = {CoRR},
  volume    = {abs/1906.05226},
  year      = {2019},
  url       = {http://arxiv.org/abs/1906.05226},
  archivePrefix = {arXiv},
  eprint    = {1906.05226},
  timestamp = {Fri, 14 Jun 2019 09:38:24 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1906-05226.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}