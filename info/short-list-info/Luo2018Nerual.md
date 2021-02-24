# Title
Neural Architecture Optimization

## Venue
NeurIPS

## Author
Renqian Luo, Fei Tian, Tao Qin, Enhong Chen, Tie-Yan Liu

## Abstract
Automatic neural architecture design has shown its potential in discovering powerful neural network architectures. Existing methods, no matter based on reinforcement learning or evolutionary algorithms (EA), conduct architecture search in a discrete space, which is highly inefficient. In this paper, we propose a simple and efficient method to automatic neural architecture design based on continuous optimization. We call this new approach neural architecture optimization (NAO). There are three key components in our proposed approach: (1) An encoder embeds/maps neural network architectures into a continuous space. (2) A predictor takes the continuous representation of a network as input and predicts its accuracy. (3) A decoder maps a continuous representation of a network back to its architecture. The performance predictor and the encoder enable us to perform gradient based optimization in the continuous space to find the embedding of a new architecture with potentially better accuracy. Such a better embedding is then decoded to a network by the decoder. Experiments show that the architecture discovered by our method is very competitive for image classification task on CIFAR-10 and language modeling task on PTB, outperforming or on par with the best results of previous architecture search methods with a significantly reduction of computational resources. Specifically we obtain 2.11% test set error rate for CIFAR-10 image classification task and 56.0 test set perplexity of PTB language modeling task. The best discovered architectures on both tasks are successfully transferred to other tasks such as CIFAR-100 and WikiText-2. Furthermore, combined with the recent proposed weight sharing mechanism, we discover powerful architecture on CIFAR-10 (with error rate 3.53%) and on PTB (with test set perplexity 56.6), with very limited computational resources (less than 10 GPU hours) for both tasks.

## Bib
@inproceedings{NEURIPS2018_933670f1,
 author = {Luo, Renqian and Tian, Fei and Qin, Tao and Chen, Enhong and Liu, Tie-Yan},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {S. Bengio and H. Wallach and H. Larochelle and K. Grauman and N. Cesa-Bianchi and R. Garnett},
 pages = {7816--7827},
 publisher = {Curran Associates, Inc.},
 title = {Neural Architecture Optimization},
 url = {https://proceedings.neurips.cc/paper/2018/file/933670f1ac8ba969f32989c312faba75-Paper.pdf},
 volume = {31},
 year = {2018}
}