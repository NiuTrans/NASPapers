# Title
Neural Predictor for Neural Architecture Search

## Author
Wei Wen, Hanxiao Liu, Hai Li, Yiran Chen, Gabriel Bender, Pieter-Jan Kindermans

## Abstract
Neural Architecture Search methods are effective but often use complex algorithms to come up with the best architecture. We propose an approach with three basic steps that is conceptually much simpler. First we train N random architectures to generate N (architecture, validation accuracy) pairs and use them to train a regression model that predicts accuracy based on the architecture. Next, we use this regression model to predict the validation accuracies of a large number of random architectures. Finally, we train the top-K predicted architectures and deploy the model with the best validation result. While this approach seems simple, it is more than 20 times as sample efficient as Regularized Evolution on the NASBench-101 benchmark and can compete on ImageNet with more complex approaches based on weight sharing, such as ProxylessNAS.

## Bib
@inproceedings{wen2020neural,
  title={Neural predictor for neural architecture search},
  author={Wen, Wei and Liu, Hanxiao and Chen, Yiran and Li, Hai and Bender, Gabriel and Kindermans, Pieter-Jan},
  booktitle={European Conference on Computer Vision},
  pages={660--676},
  year={2020},
  organization={Springer}
}