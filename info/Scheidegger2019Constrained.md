# Title
Constrained deep neural network architecture search for IoT devices accounting for hardware calibration

## Author
Florian Scheidegger, Luca Benini, Costas Bekas, A. Cristiano I. Malossi

## Abstract
Deep neural networks achieve outstanding results for challenging image classification tasks. However, the design of network topologies is a complex task, and the research community is conducting ongoing efforts to discover top-accuracy topologies, either manually or by employing expensive architecture searches. We propose a unique narrow-space architecture search that focuses on delivering low-cost and rapidly executing networks that respect strict memory and time requirements typical of Internet-of-Things (IoT) near-sensor computing platforms. Our approach provides solutions with classification latencies below 10~ms running on a low-cost device with 1~GB RAM and a peak performance of 5.6~GFLOPS. The narrow-space search of floating-point models improves the accuracy on CIFAR10 of an established IoT model from 70.64% to 74.87% within the same memory constraints. We further improve the accuracy to 82.07% by including 16-bit half types and obtain the highest accuracy of 83.45% by extending the search with model-optimized IEEE 754 reduced types. To the best of our knowledge, this is the first empirical demonstration of more than 3000 trained models that run with reduced precision and push the Pareto optimal front by a wide margin. Within a given memory constraint, accuracy is improved by more than 7% points for half and more than 1% points for the best individual model format.

## Bib
@inproceedings{NEURIPS2019_f8037f94,
 author = {Scheidegger, Florian and Benini, Luca and Bekas, Costas and Malossi, A. Cristiano I.},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
 pages = {6056--6066},
 publisher = {Curran Associates, Inc.},
 title = {Constrained deep neural network architecture search for IoT devices accounting for hardware calibration},
 url = {https://proceedings.neurips.cc/paper/2019/file/f8037f94e53f17a2cc301033ca86d278-Paper.pdf},
 volume = {32},
 year = {2019}
}