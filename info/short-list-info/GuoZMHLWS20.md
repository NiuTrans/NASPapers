# Title 
Single Path One-Shot Neural Architecture Search with Uniform Sampling

## Venue
ECCV

## Author 
Zichao Guo, Xiangyu Zhang, Haoyuan Mu, Wen Heng, Zechun Liu, Yichen Wei, Jian Sun

## Key Words 
- Uniform Sampling 
- One-shot

## Abstract 
We revisit the one-shot Neural Architecture Search (NAS) paradigm and analyze its advantages over existing NAS approaches. Existing one-shot method, however, is hard to train and not yet effective on large scale datasets like ImageNet. This work propose a Single Path One-Shot model to address the challenge in the training. Our central idea is to construct a simplified supernet, where all architectures are single paths so that weight co-adaption problem is alleviated. Training is performed by uniform path sampling. All architectures (and their weights) are trained fully and equally.
Comprehensive experiments verify that our approach is flexible and effective. It is easy to train and fast to search. It effortlessly supports complex search spaces (e.g., building blocks, channel, mixed-precision quantization) and different search constraints (e.g., FLOPs, latency). It is thus convenient to use for various needs. It achieves start-of-the-art performance on the large dataset ImageNet.


## Bib
@inproceedings{DBLP:conf/eccv/GuoZMHLWS20,
  author    = {Zichao Guo and
               Xiangyu Zhang and
               Haoyuan Mu and
               Wen Heng and
               Zechun Liu and
               Yichen Wei and
               Jian Sun},
  editor    = {Andrea Vedaldi and
               Horst Bischof and
               Thomas Brox and
               Jan{-}Michael Frahm},
  title     = {Single Path One-Shot Neural Architecture Search with Uniform Sampling},
  booktitle = {Computer Vision - {ECCV} 2020 - 16th European Conference, Glasgow,
               UK, August 23-28, 2020, Proceedings, Part {XVI}},
  series    = {Lecture Notes in Computer Science},
  volume    = {12361},
  pages     = {544--560},
  publisher = {Springer},
  year      = {2020},
  url       = {https://doi.org/10.1007/978-3-030-58517-4\_32},
  doi       = {10.1007/978-3-030-58517-4\_32},
  timestamp = {Tue, 09 Feb 2021 15:29:44 +0100},
  biburl    = {https://dblp.org/rec/conf/eccv/GuoZMHLWS20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}