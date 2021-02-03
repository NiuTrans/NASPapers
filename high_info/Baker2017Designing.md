# Title 
Designing Neural Network Architectures using Reinforcement Learning

## Venue
ICLR

## Author 
Bowen Baker, Otkrist Gupta, Nikhil Naik, Ramesh Raskar
## Abstract 
At present, designing convolutional neural network (CNN) architectures requires both human expertise and labor. New architectures are handcrafted by careful experimentation or modified from a handful of existing networks. We introduce MetaQNN, a meta-modeling algorithm based on reinforcement learning to automatically generate high-performing CNN architectures for a given learning task. The learning agent is trained to sequentially choose CNN layers using Q-learning with an $ \epsilon $ -greedy exploration strategy and experience replay. The agent explores a large but finite space of possible architectures and iteratively discovers designs with improved performance on the learning task. On image classification benchmarks, the agent-designed networks (consisting of only standard convolution, pooling, and fully-connected layers) beat existing networks designed with the same layer types and are competitive against the state-of-the-art methods that use more complex layer types. We also outperform existing meta-modeling approaches for network design on image classification tasks.
## Bib
@article{DBLP:journals/corr/BakerGNR16,
  author    = {Bowen Baker and
               Otkrist Gupta and
               Nikhil Naik and
               Ramesh Raskar},
  title     = {Designing Neural Network Architectures using Reinforcement Learning},
  journal   = {CoRR},
  volume    = {abs/1611.02167},
  year      = {2016},
  url       = {http://arxiv.org/abs/1611.02167},
  archivePrefix = {arXiv},
  eprint    = {1611.02167},
  timestamp = {Mon, 13 Aug 2018 16:47:42 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/BakerGNR16.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}