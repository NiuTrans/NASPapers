# Title
One-Shot Neural Architecture Search via Novelty Driven Sampling

## Author
Miao Zhang, Huiqi Li, Shirui Pan, Taoping Liu, Steven Su

## Abstract
One-Shot Neural architecture search (NAS) has received wide attentions due to its computational efficiency. Most state-of-the-art One-Shot NAS methods use the validation accuracy based on inheriting weights from the supernet as the stepping stone to search for the best performing architecture, adopting a bilevel optimization pattern with assuming this validation accuracy approximates to the test accuracy after re-training. However, recent works have found that there is no positive correlation between the above validation accuracy and test accuracy for these One-Shot NAS methods, and this reward based sampling for supernet training also entails the rich-get-richer problem. To handle this deceptive problem, this paper presents a new approach, Efficient Novelty-driven Neural Architecture Search, to sample the most abnormal architecture to train the supernet. Specifically, a single-path supernet is adopted, and only the weights of a single architecture sampled by our novelty search are optimized in each step to reduce the memory demand greatly. Experiments demonstrate the effectiveness and efficiency of our novelty search based architecture sampling method.

## Bib
@inproceedings{ijcai2020-0441,
  title     = {One-Shot Neural Architecture Search via Novelty Driven Sampling},
  author    = {Zhang, Miao and Li, Huiqi and Pan, Shirui and Liu, Taoping and Su, Steven},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {3188--3194},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/441},
  url       = {https://doi.org/10.24963/ijcai.2020/441},
}
