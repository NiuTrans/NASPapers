# Title
Neural Architecture Search for Keyword Spotting

## Author
Tong Mo, Yakun Yu, Mohammad Salameh, Di Niu, Shangling Jui

## Abstract
Deep neural networks have recently become a popular solution to keyword spotting systems, which enable the control of smart devices via voice. In this paper, we apply neural architecture search to search for convolutional neural network models that can help boost the performance of keyword spotting based on features extracted from acoustic signals while maintaining an acceptable memory footprint. Specifically, we use differentiable architecture search techniques to search for operators and their connections in a predefined cell search space. The found cells are then scaled up in both depth and width to achieve competitive performance. We evaluated the proposed method on Google’s Speech Commands Dataset and achieved a state-of-the-art accuracy of over 97% on the setting of 12-class utterance classification commonly reported in the literature.



## Bib
@inproceedings{Mo2020,
  author={Tong Mo and Yakun Yu and Mohammad Salameh and Di Niu and Shangling Jui},
  title={{Neural Architecture Search for Keyword Spotting}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={1982--1986},
  doi={10.21437/Interspeech.2020-3132},
  url={http://dx.doi.org/10.21437/Interspeech.2020-3132}
}