# Title 
Neural Optimizer Search with Reinforcement Learning
## Author 
Irwan Bello, Barret Zoph, Vijay Vasudevan, Quoc V. Le
## Abstract 
We present an approach to automate the process of discovering optimization methods, with a focus on deep learning architectures. We train a Recurrent Neural Network controller to generate a string in a domain specific language that describes a mathematical update equation based on a list of primitive functions, such as the gradient, running average of the gradient, etc. The controller is trained with Reinforcement Learning to maximize the performance of a model after a few epochs. On CIFAR-10, our method discovers several update rules that are better than many commonly used optimizers, such as Adam, RMSProp, or SGD with and without Momentum on a ConvNet model. We introduce two new optimizers, named PowerSign and AddSign, which we show transfer well and improve training on a variety of different tasks and architectures, including ImageNet classification and Google's neural machine translation system.
## Bib
@article{DBLP:journals/corr/abs-1709-07417,
  author    = {Irwan Bello and
               Barret Zoph and
               Vijay Vasudevan and
               Quoc V. Le},
  title     = {Neural Optimizer Search with Reinforcement Learning},
  journal   = {CoRR},
  volume    = {abs/1709.07417},
  year      = {2017},
  url       = {http://arxiv.org/abs/1709.07417},
  archivePrefix = {arXiv},
  eprint    = {1709.07417},
  timestamp = {Mon, 13 Aug 2018 16:48:34 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1709-07417.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}