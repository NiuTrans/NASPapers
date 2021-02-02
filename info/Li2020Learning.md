# Title
Learning Architectures from an Extended Search Space for Language Modeling

## Author
Yinqiao Li, Chi Hu, Yuhao Zhang, Nuo Xu, Yufan Jiang, Tong Xiao, Jingbo Zhu, Tongran Liu, Changliang Li

## Abstract
Neural architecture search (NAS) has advanced significantly in recent years but most NAS systems restrict search to learning architectures of a recurrent or convolutional cell. In this paper, we extend the search space of NAS. In particular, we present a general approach to learn both intra-cell and inter-cell architectures (call it ESS). For a better search result, we design a joint learning method to perform intra-cell and inter-cell NAS simultaneously. We implement our model in a differentiable architecture search system. For recurrent neural language modeling, it outperforms a strong baseline significantly on the PTB and WikiText data, with a new state-of-the-art on PTB. Moreover, the learned architectures show good transferability to other systems. E.g., they improve state-of-the-art systems on the CoNLL and WNUT named entity recognition (NER) tasks and CoNLL chunking task, indicating a promising line of research on large-scale pre-learned architectures.

## Bib
@article{li2020learning,
  title={Learning architectures from an extended search space for language modeling},
  author={Li, Yinqiao and Hu, Chi and Zhang, Yuhao and Xu, Nuo and Jiang, Yufan and Xiao, Tong and Zhu, Jingbo and Liu, Tongran and Li, Changliang},
  journal={arXiv preprint arXiv:2005.02593},
  year={2020}
}