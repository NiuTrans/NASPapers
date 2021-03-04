# Title 
The Evolved Transformer

## Venue
ICML

## Author 
David R. So, Chen Liang, Quoc V. Le

## Key Words 
- Transformer
- Evolutionary Search

## Abstract 
Recent works have highlighted the strength of the Transformer architecture on sequence tasks while, at the same time, neural architecture search (NAS) has begun to outperform human-designed models. Our goal is to apply NAS to search for a better alternative to the Transformer. We first construct a large search space inspired by the recent advances in feed-forward sequence models and then run evolutionary architecture search with warm starting by seeding our initial population with the Transformer. To directly search on the computationally expensive WMT 2014 English-German translation task, we develop the Progressive Dynamic Hurdles method, which allows us to dynamically allocate more resources to more promising candidate models. The architecture found in our experiments -- the Evolved Transformer -- demonstrates consistent improvement over the Transformer on four well-established language tasks: WMT 2014 English-German, WMT 2014 English-French, WMT 2014 English-Czech and LM1B. At a big model size, the Evolved Transformer establishes a new state-of-the-art BLEU score of 29.8 on WMT'14 English-German; at smaller sizes, it achieves the same quality as the original "big" Transformer with 37.6% less parameters and outperforms the Transformer by 0.7 BLEU at a mobile-friendly model size of 7M parameters.


## Bib
@inproceedings{DBLP:conf/icml/SoLL19,
  author    = {David R. So and
               Quoc V. Le and
               Chen Liang},
  editor    = {Kamalika Chaudhuri and
               Ruslan Salakhutdinov},
  title     = {The Evolved Transformer},
  booktitle = {Proceedings of the 36th International Conference on Machine Learning,
               {ICML} 2019, 9-15 June 2019, Long Beach, California, {USA}},
  series    = {Proceedings of Machine Learning Research},
  volume    = {97},
  pages     = {5877--5886},
  publisher = {{PMLR}},
  year      = {2019},
  url       = {http://proceedings.mlr.press/v97/so19a.html},
  timestamp = {Thu, 26 Sep 2019 17:46:53 +0200},
  biburl    = {https://dblp.org/rec/conf/icml/SoLL19.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}