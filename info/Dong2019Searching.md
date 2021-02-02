# Title
Searching for a Robust Neural Architecture in Four GPU Hours

## Author
Xuanyi Dong, Yi Yang

## Abstract
Conventional neural architecture search (NAS) approaches are usually based on reinforcement learning or evolutionary strategy, which take more than 1000 GPU hours to find a good model on CIFAR-10. We propose an efficient NAS approach, which learns the searching approach by gradient descent. Our approach represents the search space as a directed acyclic graph (DAG). This DAG contains thousands of sub-graphs, each of which indicates a kind of neural architecture. To avoid traversing all the possibilities of the sub-graphs, we develop a differentiable sampler over the DAG. This sampler is learnable and optimized by the validation loss after training the sampled architecture. In this way, our approach can be trained in an end-to-end fashion by gradient descent, named Gradient-based search using Differentiable Architecture Sampler (GDAS). In experiments, we can finish one searching procedure in four GPU hours on CIFAR-10, and the discovered model obtains a test error of 2.82% with only 2.5M parameters, which is on par with the state-of-the-art.

## Bib
@INPROCEEDINGS{8953848,
  author={X. {Dong} and Y. {Yang}},
  booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Searching for a Robust Neural Architecture in Four GPU Hours}, 
  year={2019},
  volume={},
  number={},
  pages={1761-1770},
  doi={10.1109/CVPR.2019.00186}}