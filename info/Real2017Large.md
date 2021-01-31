# Title
Large-Scale Evolution of Image Classifiers

## Author
Esteban Real, Sherry Moore, Andrew Selle, Saurabh Saxena, Yutaka Leon Suematsu, Jie Tan, Quoc V. Le, Alexey Kurakin

## Abstract
Neural networks have proven effective at solving difficult problems but designing their architectures can be challenging, even for image classification problems alone. Our goal is to minimize human participation, so we employ evolutionary algorithms to discover such networks automatically. Despite significant computational requirements, we show that it is now possible to evolve models with accuracies within the range of those published in the last year. Specifically, we employ simple evolutionary techniques at unprecedented scales to discover models for the CIFAR-10 and CIFAR-100 datasets, starting from trivial initial conditions and reaching accuracies of 94.6\% (95.6\% for ensemble) and 77.0\%, respectively. To do this, we use novel and intuitive mutation operators that navigate large search spaces; we stress that no human participation is required once evolution starts and that the output is a fully-trained model. Throughout this work, we place special emphasis on the repeatability of results, the variability in the outcomes and the computational requirements.

## Bib
@InProceedings{pmlr-v70-real17a,
  title = 	 {Large-Scale Evolution of Image Classifiers},
  author =       {Esteban Real and Sherry Moore and Andrew Selle and Saurabh Saxena and Yutaka Leon Suematsu and Jie Tan and Quoc V. Le and Alexey Kurakin},
  booktitle = 	 {Proceedings of the 34th International Conference on Machine Learning},
  pages = 	 {2902--2911},
  year = 	 {2017},
  editor = 	 {Doina Precup and Yee Whye Teh},
  volume = 	 {70},
  series = 	 {Proceedings of Machine Learning Research},
  address = 	 {International Convention Centre, Sydney, Australia},
  month = 	 {06--11 Aug},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v70/real17a/real17a.pdf},
  url = 	 {http://proceedings.mlr.press/v70/real17a.html},
  abstract = 	 {Neural networks have proven effective at solving difficult problems but designing their architectures can be challenging, even for image classification problems alone. Our goal is to minimize human participation, so we employ evolutionary algorithms to discover such networks automatically. Despite significant computational requirements, we show that it is now possible to evolve models with accuracies within the range of those published in the last year. Specifically, we employ simple evolutionary techniques at unprecedented scales to discover models for the CIFAR-10 and CIFAR-100 datasets, starting from trivial initial conditions and reaching accuracies of 94.6\% (95.6\% for ensemble) and 77.0\%, respectively. To do this, we use novel and intuitive mutation operators that navigate large search spaces; we stress that no human participation is required once evolution starts and that the output is a fully-trained model. Throughout this work, we place special emphasis on the repeatability of results, the variability in the outcomes and the computational requirements.}
}
