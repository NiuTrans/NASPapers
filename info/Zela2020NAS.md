# Title
NAS-Bench-1Shot1: Benchmarking and Dissecting One-shot Neural Architecture Search

## Author
Arber Zela, Julien Siems, Frank Hutter

## Abstract
One-shot neural architecture search (NAS) has played a crucial role in making NAS methods computationally feasible in practice. Nevertheless, there is still a lack of understanding on how these weight-sharing algorithms exactly work due to the many factors controlling the dynamics of the process. In order to allow a scientific study of these components, we introduce a general framework for
one-shot NAS that can be instantiated to many recently-introduced variants and introduce a general benchmarking framework that draws on the recent large-scale tabular benchmark NAS-Bench-101 for cheap anytime evaluations of one-shot NAS methods. To showcase the framework, we compare several state-of-the-art one-shot NAS methods, examine how sensitive they are to their hyperparameters and how they can be improved by tuning their hyperparameters, and compare their performance to that of blackbox optimizers for NAS-Bench-101.

## Bib
@inproceedings{
Zela2020NAS-Bench-1Shot1:,
title={NAS-Bench-1Shot1: Benchmarking and Dissecting One-shot Neural Architecture Search},
author={Arber Zela and Julien Siems and Frank Hutter},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=SJx9ngStPH}
}