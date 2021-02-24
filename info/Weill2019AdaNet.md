# Title
AdaNet: A Scalable and Flexible Framework for Automatically Learning Ensembles

## Author
Charles Weill, Javier Gonzalvo, Vitaly Kuznetsov, Scott Yang, Scott Yak, Hanna Mazzawi, Eugen Hotaj, Ghassen Jerfel, Vladimir Macko, Ben Adlam, Mehryar Mohri, Corinna Cortes

## Abstract
AdaNet is a lightweight TensorFlow-based (Abadi et al., 2015) framework for automatically learning high-quality ensembles with minimal expert intervention. Our framework is inspired by the AdaNet algorithm (Cortes et al., 2017) which learns the structure of a neural network as an ensemble of subnetworks. We designed it to: (1) integrate with the existing TensorFlow ecosystem, (2) offer sensible default search spaces to perform well on novel datasets, (3) present a flexible API to utilize expert information when available, and (4) efficiently accelerate training with distributed CPU, GPU, and TPU hardware. The code is open-source and available at: https://github.com/tensorflow/adanet

## Bib
@misc{weill2019adanet,
      title={AdaNet: A Scalable and Flexible Framework for Automatically Learning Ensembles}, 
      author={Charles Weill and Javier Gonzalvo and Vitaly Kuznetsov and Scott Yang and Scott Yak and Hanna Mazzawi and Eugen Hotaj and Ghassen Jerfel and Vladimir Macko and Ben Adlam and Mehryar Mohri and Corinna Cortes},
      year={2019},
      eprint={1905.00080},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}