# Title
NAS-Bench-101: Towards Reproducible Neural Architecture Search

## Author
Chris Ying, Aaron Klein, Eric Christiansen, Esteban Real, Kevin Murphy, Frank Hutter

## Abstract
Recent advances in neural architecture search (NAS) demand tremendous computational resources, which makes it difficult to reproduce experiments and imposes a barrier-to-entry to researchers without access to large-scale computation. We aim to ameliorate these problems by introducing NAS-Bench-101, the first public architecture dataset for NAS research. To build NAS-Bench-101, we carefully constructed a compact, yet expressive, search space, exploiting graph isomorphisms to identify 423k unique convolutional architectures. We trained and evaluated all of these architectures multiple times on CIFAR-10 and compiled the results into a large dataset of over 5 million trained models. This allows researchers to evaluate the quality of a diverse range of models in milliseconds by querying the pre-computed dataset. We demonstrate its utility by analyzing the dataset as a whole and by benchmarking a range of architecture optimization algorithms.

## Bib
@InProceedings{pmlr-v97-ying19a,
  title = 	 {{NAS}-Bench-101: Towards Reproducible Neural Architecture Search},
  author =       {Ying, Chris and Klein, Aaron and Christiansen, Eric and Real, Esteban and Murphy, Kevin and Hutter, Frank},
  booktitle = 	 {Proceedings of the 36th International Conference on Machine Learning},
  pages = 	 {7105--7114},
  year = 	 {2019},
  editor = 	 {Kamalika Chaudhuri and Ruslan Salakhutdinov},
  volume = 	 {97},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {09--15 Jun},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v97/ying19a/ying19a.pdf},
  url = 	 {
http://proceedings.mlr.press/v97/ying19a.html
},
  abstract = 	 {Recent advances in neural architecture search (NAS) demand tremendous computational resources, which makes it difficult to reproduce experiments and imposes a barrier-to-entry to researchers without access to large-scale computation. We aim to ameliorate these problems by introducing NAS-Bench-101, the first public architecture dataset for NAS research. To build NAS-Bench-101, we carefully constructed a compact, yet expressive, search space, exploiting graph isomorphisms to identify 423k unique convolutional architectures. We trained and evaluated all of these architectures multiple times on CIFAR-10 and compiled the results into a large dataset of over 5 million trained models. This allows researchers to evaluate the quality of a diverse range of models in milliseconds by querying the pre-computed dataset. We demonstrate its utility by analyzing the dataset as a whole and by benchmarking a range of architecture optimization algorithms.}
}