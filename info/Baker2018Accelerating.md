# Title
Accelerating Neural Architecture Search using Performance Prediction

## Author
Bowen Baker, Otkrist Gupta, Ramesh Raskar, Nikhil Naik

## Abstract
Methods for neural network hyperparameter optimization and meta-modeling are computationally expensive due to the need to train a large number of model configurations. In this paper, we show that standard frequentist regression models can predict the final performance of partially trained model configurations using features based on network architectures, hyperparameters, and time series validation performance data. We empirically show that our performance prediction models are much more effective than prominent Bayesian counterparts, are simpler to implement, and are faster to train. Our models can predict final performance in both visual classification and language modeling domains, are effective for predicting performance of drastically varying model architectures, and can even generalize between model classes. Using these prediction models, we also propose an early stopping method for hyperparameter optimization and meta-modeling, which obtains a speedup of a factor up to 6x in both hyperparameter optimization and meta-modeling. Finally, we empirically show that our early stopping method can be seamlessly incorporated into both reinforcement learning-based architecture selection algorithms and bandit based search methods. Through extensive experimentation, we empirically show our performance prediction models and early stopping algorithm are state-of-the-art in terms of prediction accuracy and speedup achieved while still identifying the optimal model configurations.

## Bib
@misc{
baker*2018accelerating,
title={Accelerating Neural Architecture Search using Performance Prediction},
author={Bowen Baker*, Otkrist Gupta*, Ramesh Raskar, Nikhil Naik},
year={2018},
url={https://openreview.net/forum?id=BJypUGZ0Z},
}