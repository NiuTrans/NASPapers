# Title
Genetic CNN

## Venue
ICCV

## Author
Lingxi Xie, Alan Yuille

## Abstract
The deep convolutional neural network (CNN) is the state-of-the-art solution for large-scale visual recognition. Following some basic principles such as increasing network depth and constructing highway connections, researchers have manually designed a lot of fixed network architectures and verified their effectiveness. In this paper, we discuss the possibility of learning deep network structures automatically. Note that the number of possible network structures increases exponentially with the number of layers in the network, which motivates us to adopt the genetic algorithm to efficiently explore this large search space. The core idea is to propose an encoding method to represent each network structure in a fixed-length binary string. The genetic algorithm is initialized by generating a set of randomized individuals. In each generation, we define standard genetic operations, e.g., selection, mutation and crossover, to generate competitive individuals and eliminate weak ones. The competitiveness of each individual is defined as its recognition accuracy, which is obtained via a standalone training process on a reference dataset. We run the genetic process on CIFAR10, a small-scale dataset, demonstrating its ability to find high-quality structures which are little studied before. The learned powerful structures are also transferrable to the ILSVRC2012 dataset for large-scale visual recognition.

## Bib
@InProceedings{Xie_2017_ICCV,
author = {Xie, Lingxi and Yuille, Alan},
title = {Genetic CNN},
booktitle = {Proceedings of the IEEE International Conference on Computer Vision (ICCV)},
month = {Oct},
year = {2017}
}