# Title
Evolved Speech-Transformer: Applying Neural Architecture Search to End-to-End Automatic Speech Recognition

## Author
Jihwan Kim, Jisung Wang, Sangki Kim, Yeha Lee

## Abstract
Neural architecture search (NAS) has been successfully applied to finding efficient, high-performance deep neural network architectures in a task-adaptive manner without extensive human intervention. This is achieved by choosing genetic, reinforcement learning, or gradient -based algorithms as automative alternatives of manual architecture design. However, a naive application of existing NAS algorithms to different tasks may result in architectures which perform sub-par to those manually designed. In this work, we show that NAS can provide efficient architectures that outperform manually designed attention-based architectures on speech recognition tasks, after which we named Evolved Speech-Transformer (EST). With a combination of carefully designed search space and Progressive dynamic hurdles, a genetic algorithm based, our algorithm finds a memory-efficient architecture which outperforms vanilla Transformer with reduced training time.



## Bib
@inproceedings{Kim2020,
  author={Jihwan Kim and Jisung Wang and Sangki Kim and Yeha Lee},
  title={{Evolved Speech-Transformer: Applying Neural Architecture Search to End-to-End Automatic Speech Recognition}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={1788--1792},
  doi={10.21437/Interspeech.2020-1233},
  url={http://dx.doi.org/10.21437/Interspeech.2020-1233}
}