# Title
Simple and efficient architecture search for Convolutional Neural Networks

## Author
Thomas Elsken, Jan Hendrik Metzen, Frank Hutter

## Abstract
Neural networks have recently had a lot of success for many tasks. However, neural network architectures that perform well are still typically designed manually by experts in a cumbersome trial-and-error process. We propose a new method to automatically search for well-performing CNN architectures based on a simple hill climbing procedure whose operators apply network morphisms, followed by short optimization runs by cosine annealing. Surprisingly, this simple method yields competitive results, despite only requiring resources in the same order of magnitude as training a single network. E.g., on CIFAR-10, our method designs and trains networks with an error rate below 6% in only 12 hours on a single GPU; training for one day reduces this error further, to almost 5%.

## Bib
@misc{
elsken2018simple,
title={Simple and efficient architecture search for Convolutional Neural Networks},
author={Thomas Elsken, Jan Hendrik Metzen, Frank Hutter},
year={2018},
url={https://openreview.net/forum?id=SySaJ0xCZ},
}