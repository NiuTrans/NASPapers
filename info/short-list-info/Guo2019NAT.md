# Title 
NAT: Neural Architecture Transformer for Accurate and Compact Architectures

## Venue
NeurlPSs

## Author 
Yong Guo, Yin Zheng, Mingkui Tan, Qi Chen, Jian Chen, Peilin Zhao, Junzhou Huang
## Abstract 
Designing effective architectures is one of the key factors behind the success of deep neural networks. Existing deep architectures are either manually designed or automatically searched by some Neural Architecture Search (NAS) methods. However, even a well-searched architecture may still contain many non-significant or redundant modules or operations (e.g., convolution or pooling), which may not only incur substantial memory consumption and computation cost but also deteriorate the performance. Thus, it is necessary to optimize the operations inside an architecture to improve the performance without introducing extra computation cost. Unfortunately, such a constrained optimization problem is NP-hard. To make the problem feasible, we cast the optimization problem into a Markov decision process (MDP) and seek to learn a Neural Architecture Transformer (NAT) to replace the redundant operations with the more computationally efficient ones (e.g., skip connection or directly removing the connection). Based on MDP, we learn NAT by exploiting reinforcement learning to obtain the optimization policies w.r.t. different architectures. To verify the effectiveness of the proposed strategies, we apply NAT on both hand-crafted architectures and NAS based architectures. Extensive experiments on two benchmark datasets, i.e., CIFAR-10 and ImageNet, demonstrate that the transformed architecture by NAT significantly outperforms both its original form and those architectures optimized by existing methods.
## Bib
@article{DBLP:journals/corr/abs-1910-14488,
  author    = {Yong Guo and
               Yin Zheng and
               Mingkui Tan and
               Qi Chen and
               Jian Chen and
               Peilin Zhao and
               Junzhou Huang},
  title     = {{NAT:} Neural Architecture Transformer for Accurate and Compact Architectures},
  journal   = {CoRR},
  volume    = {abs/1910.14488},
  year      = {2019},
  url       = {http://arxiv.org/abs/1910.14488},
  archivePrefix = {arXiv},
  eprint    = {1910.14488},
  timestamp = {Thu, 07 Nov 2019 08:54:46 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1910-14488.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}