# Title
A Genetic Programming Approach to Designing Convolutional Neural Network Architectures

## Author
Masanori Suganuma, Shinichi Shirakawa, Tomoharu Nagao

## Abstract
We propose a method for designing convolutional neural network (CNN) architectures based on Cartesian genetic programming (CGP). In the proposed method, the architectures of CNNs are represented by directed acyclic graphs, in which each node represents highly-functional modules such as convolutional blocks and tensor operations, and each edge represents the connectivity of layers. The architecture is optimized to maximize the classification accuracy for a validation dataset by an evolutionary algorithm. We show that the proposed method can find competitive CNN architectures compared with state-of-the-art methods on the image classification task using CIFAR-10 and CIFAR-100 datasets.

## Bib
@inproceedings{ijcai2018-0755,
  title     = {A Genetic Programming Approach to Designing Convolutional Neural Network Architectures},
  author    = {Masanori Suganuma and Shinichi Shirakawa and Tomoharu Nagao},
  booktitle = {Proceedings of the Twenty-Seventh International Joint Conference on
               Artificial Intelligence, {IJCAI-18}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  pages     = {5369--5373},
  year      = {2018},
  month     = {7},
  doi       = {10.24963/ijcai.2018/755},
  url       = {https://doi.org/10.24963/ijcai.2018/755},
}
