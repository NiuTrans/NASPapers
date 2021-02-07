# Title
NAS-Bench-ASR: Reproducible Neural Architecture Search for Speech Recognition

## Author
Abhinav Mehrotra, Alberto Gil C. P. Ramos, Sourav Bhattacharya, Łukasz Dudziak, Ravichander Vipperla, Thomas Chau, Mohamed S Abdelfattah, Samin Ishtiaq, Nicholas Donald Lane

## Abstract
Powered by innovations in novel architecture design, noise tolerance techniques and increasing model capacity, Automatic Speech Recognition (ASR) made giant strides in improving prediction accuracies over the past decade. ASR models are often trained with tens of thousand hours of high quality speech data to produce the state-of-the-art results. Industry-scale ASR model-training thus remains as a computationally heavy and time-consuming procedure, and consequently attracted little attention thus far in adopting automatic techniques in exploring neural architecture variations. Neural Architecture Search (NAS), on the other hand, gained a lot of interest in the past few years for its ability in discovering state-of-the-art architectures mainly in computer vision tasks. However, NAS approaches also suffer from the requirement of a large-scale computing infrastructure to support training of a massive number of neural networks and are often difficult to reproduce. Lately, a number of attempts have been made to ameliorate the computational problem and improve the search turnaround time of NAS algorithms by introducing benchmark datasets like NAS-Bench-101, NAS-Bench-201, and NAS-NLP. These datasets, however, focus predominantly on computer vision and NLP tasks and thus suffer from the problem of limited coverage of application domains. In this work we apply NAS for finding cell architecture for ASR models and release a comprehensive NAS-Bench dataset for reproducible NAS research. The dataset consists of 8,242 unique ASR models trained on the TIMIT audio dataset, each starting from 3 seed initializations. Novelty of our dataset includes consideration for on-device deployability and inclusion of runtime measures of all the models on diverse hardware platforms and settings. We further evaluate performances of a number of NAS algorithms on our dataset. Finally, we show that cells in our search space for TIMIT transfer well to a much larger LibriSpeech dataset. 

## Bib
@inproceedings{
mehrotra2021nasbenchasr,
title={{\{}NAS{\}}-Bench-{\{}ASR{\}}: Reproducible Neural Architecture Search for Speech Recognition},
author={Abhinav Mehrotra and Alberto Gil C. P. Ramos and Sourav Bhattacharya and {\L}ukasz Dudziak and Ravichander Vipperla and Thomas Chau and Mohamed S Abdelfattah and Samin Ishtiaq and Nicholas Donald Lane},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=CU0APx9LMaL}
}