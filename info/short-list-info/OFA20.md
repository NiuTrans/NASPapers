# Title 
Once-for-All: Train One Network and Specialize it for Efficient Deployment

## Venue
ICLR

## Author 
Han Cai, Chuang Gan, Tianzhe Wang, Zhekai Zhang, Song Han

## Key Words 
- Efficient Deep Learning
- Specialized Neural Network Architecture
- AutoML

## Abstract 
We address the challenging problem of efficient inference across many devices and resource constraints, especially on edge devices. Conventional approaches either manually design or use neural architecture search (NAS) to find a specialized neural network and train it from scratch for each case, which is computationally prohibitive (causing CO2 emission as much as 5 cars' lifetime) thus unscalable. In this work, we propose to train a once-for-all (OFA) network that supports diverse architectural settings by decoupling training and search, to reduce the cost. We can quickly get a specialized sub-network by selecting from the OFA network without additional training. To efficiently train OFA networks, we also propose a novel progressive shrinking algorithm, a generalized pruning method that reduces the model size across many more dimensions than pruning (depth, width, kernel size, and resolution). It can obtain a surprisingly large number of sub-networks (>1019) that can fit different hardware platforms and latency constraints while maintaining the same level of accuracy as training independently. On diverse edge devices, OFA consistently outperforms state-of-the-art (SOTA) NAS methods (up to 4.0% ImageNet top1 accuracy improvement over MobileNetV3, or same accuracy but 1.5x faster than MobileNetV3, 2.6x faster than EfficientNet w.r.t measured latency) while reducing many orders of magnitude GPU hours and CO2 emission. In particular, OFA achieves a new SOTA 80.0% ImageNet top-1 accuracy under the mobile setting (<600M MACs). OFA is the winning solution for the 3rd Low Power Computer Vision Challenge (LPCVC), DSP classification track and the 4th LPCVC, both classification track and detection track.


## Bib
@inproceedings{DBLP:conf/iclr/CaiGWZH20,
  author    = {Han Cai and
               Chuang Gan and
               Tianzhe Wang and
               Zhekai Zhang and
               Song Han},
  title     = {Once-for-All: Train One Network and Specialize it for Efficient Deployment},
  booktitle = {8th International Conference on Learning Representations, {ICLR} 2020,
               Addis Ababa, Ethiopia, April 26-30, 2020},
  publisher = {OpenReview.net},
  year      = {2020},
  url       = {https://openreview.net/forum?id=HylxE1HKwS},
  timestamp = {Fri, 20 Nov 2020 16:16:07 +0100},
  biburl    = {https://dblp.org/rec/conf/iclr/CaiGWZH20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}