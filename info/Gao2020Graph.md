# Title 
Graph Neural Architecture Search
## Author 
Yang Gao, Hong Yang, Peng Zhang, Chuan Zhou, Yue Hu
## Abstract 
Graph neural networks (GNNs) emerged recently as a powerful tool for analyzing non-Euclidean data such as social network data. Despite their success, the design of graph neural networks requires heavy manual work and domain knowledge. In this paper, we present a graph neural architecture search method (GraphNAS) that enables automatic design of the best graph neural architecture based on reinforcement learning. Specifically, GraphNAS uses a recurrent network to generate variable-length strings that describe the architectures of graph neural networks, and trains the recurrent network with policy gradient to maximize the expected accuracy of the generated architectures on a validation data set. Furthermore, to improve the search efficiency of GraphNAS on big networks, GraphNAS restricts the search space from an entire architecture space to a sequential concatenation of the best search results built on each single architecture layer. Experiments on real-world datasets demonstrate that GraphNAS can design a novel network architecture that rivals the best human-invented architecture in terms of validation set accuracy. Moreover, in a transfer learning task we observe that graph neural architectures designed by GraphNAS, when transferred to new datasets, still gain improvement in terms of prediction accuracy.
## Bib
@inproceedings{ijcai2020-0195,
  title     = {Graph Neural Architecture Search},
  author    = {Gao, Yang and Yang, Hong and Zhang, Peng and Zhou, Chuan and Hu, Yue},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {1403--1409},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/195},
  url       = {https://doi.org/10.24963/ijcai.2020/195},
}
