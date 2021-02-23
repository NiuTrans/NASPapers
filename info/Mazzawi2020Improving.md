# Title
Improving Keyword Spotting and Language Identification via Neural Architecture Search at Scale

## Author
Hanna Mazzawi, Xavi Gonzalvo, Aleks Kracun, Prashant Sridhar, Niranjan Subrahmanya, Ignacio Lopez Moreno, Hyun Jin Park, Patrick Violette

## Abstract
In this paper we present a novel Neural Architecture Search (NAS) framework to improve keyword spotting and spoken language identification models. Even with the huge success of deep neural networks (DNNs) in many different domains, finding the best network architecture is still a laborious task and very computationally expensive at best with existing searching approaches. Our search approach efficiently and robustly finds better model sequences with respect to hand-designed systems. We do this by constructing architectures incrementally, using a custom mutation algorithm and leveraging the power of parameter transfer between layers. We demonstrate that our approach can automatically design DNNs with an order of magnitude fewer parameters that achieves better performance than the current best models. It leads to significant performance improvements: up to 4.09% accuracy increase for language identification (6.1% if we allow an increase in the number of parameters) and 0.3% for phoneme classification in keyword spotting with half the size of the model.







## Bib
@inproceedings{Mazzawi2019,
  author={Hanna Mazzawi and Xavi Gonzalvo and Aleks Kracun and Prashant Sridhar and Niranjan Subrahmanya and Ignacio Lopez Moreno and Hyun Jin Park and Patrick Violette},
  title={{Improving Keyword Spotting and Language Identification via Neural Architecture Search at Scale}},
  year=2019,
  booktitle={Proc. Interspeech 2019},
  pages={1278--1282},
  doi={10.21437/Interspeech.2019-1916},
  url={http://dx.doi.org/10.21437/Interspeech.2019-1916}
}