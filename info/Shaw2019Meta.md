# Title
Meta Architecture Search

## Author
Albert Shaw, Wei Wei, Weiyang Liu, Le Song, Bo Dai

## Abstract
Neural Architecture Search (NAS) has been quite successful in constructing state-of-the-art models on a variety of tasks. Unfortunately, the computational cost can make it difficult to scale. In this paper, we make the first attempt to study Meta Architecture Search which aims at learning a task-agnostic representation that can be used to speed up the process of architecture search on a large number of tasks. We propose the Bayesian Meta Architecture SEarch (BASE) framework which takes advantage of a Bayesian formulation of the architecture search problem to learn over an entire set of tasks simultaneously. We show that on Imagenet classification, we can find a model that achieves 25.7% top-1 error and 8.1% top-5 error by adapting the architecture in less than an hour from an 8 GPU days pretrained meta-network. By learning a good prior for NAS, our method dramatically decreases the required computation cost while achieving comparable performance to current state-of-the-art methods - even finding competitive models for unseen datasets with very quick adaptation. We believe our framework will open up new possibilities for efficient and massively scalable architecture search research across multiple tasks.

## Bib
@inproceedings{NEURIPS2019_ea1818cb,
 author = {Shaw, Albert and Wei, Wei and Liu, Weiyang and Song, Le and Dai, Bo},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
 pages = {11227--11237},
 publisher = {Curran Associates, Inc.},
 title = {Meta Architecture Search},
 url = {https://proceedings.neurips.cc/paper/2019/file/ea1818cbe59c23b20f1a10a8aa083a82-Paper.pdf},
 volume = {32},
 year = {2019}
}