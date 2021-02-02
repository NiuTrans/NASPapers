# Title
BayesNAS: A Bayesian Approach for Neural Architecture Search

## Author
Hongpeng Zhou, Minghao Yang, Jun Wang, Wei Pan

## Abstract
One-Shot Neural Architecture Search (NAS) is a promising method to significantly reduce search time without any separate training. It can be treated as a Network Compression problem on the architecture parameters from an over-parameterized network. However, there are two issues associated with most one-shot NAS methods. First, dependencies between a node and its predecessors and successors are often disregarded which result in improper treatment over zero operations. Second, architecture parameters pruning based on their magnitude is questionable. In this paper, we employ the classic Bayesian learning approach to alleviate these two issues by modeling architecture parameters using hierarchical automatic relevance determination (HARD) priors. Unlike other NAS methods, we train the over-parameterized network for only one epoch then update the architecture. Impressively, this enabled us to find the architecture in both proxy and proxyless tasks on CIFAR-10 within only 0.2 GPU days using a single GPU. As a byproduct, our approach can be transferred directly to compress convolutional neural networks by enforcing structural sparsity which achieves extremely sparse networks without accuracy deterioration.

## Bib
@InProceedings{pmlr-v97-zhou19e,
  title = 	 {{B}ayes{NAS}: A {B}ayesian Approach for Neural Architecture Search},
  author =       {Zhou, Hongpeng and Yang, Minghao and Wang, Jun and Pan, Wei},
  booktitle = 	 {Proceedings of the 36th International Conference on Machine Learning},
  pages = 	 {7603--7613},
  year = 	 {2019},
  editor = 	 {Kamalika Chaudhuri and Ruslan Salakhutdinov},
  volume = 	 {97},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {09--15 Jun},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v97/zhou19e/zhou19e.pdf},
  url = 	 {
http://proceedings.mlr.press/v97/zhou19e.html
},
  abstract = 	 {One-Shot Neural Architecture Search (NAS) is a promising method to significantly reduce search time without any separate training. It can be treated as a Network Compression problem on the architecture parameters from an over-parameterized network. However, there are two issues associated with most one-shot NAS methods. First, dependencies between a node and its predecessors and successors are often disregarded which result in improper treatment over zero operations. Second, architecture parameters pruning based on their magnitude is questionable. In this paper, we employ the classic Bayesian learning approach to alleviate these two issues by modeling architecture parameters using hierarchical automatic relevance determination (HARD) priors. Unlike other NAS methods, we train the over-parameterized network for only one epoch then update the architecture. Impressively, this enabled us to find the architecture in both proxy and proxyless tasks on CIFAR-10 within only 0.2 GPU days using a single GPU. As a byproduct, our approach can be transferred directly to compress convolutional neural networks by enforcing structural sparsity which achieves extremely sparse networks without accuracy deterioration.}
}