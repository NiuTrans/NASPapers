# Title
Efficient Multi-Objective Neural Architecture Search via Lamarckian Evolution

## Venue
ICLR

## Author
Thomas Elsken, Jan Hendrik Metzen, Frank Hutter

## Abstract
Architecture search aims at automatically finding neural architectures that are competitive with architectures designed by human experts. While recent approaches have achieved state-of-the-art predictive performance for image recognition, they are problematic under resource constraints for two reasons: (1) the neural architectures found are solely optimized for high predictive performance, without penalizing excessive resource consumption; (2)most architecture search methods require vast computational resources. We address the first shortcoming by proposing LEMONADE, an evolutionary algorithm for multi-objective architecture search that allows approximating the Pareto-front of architectures under multiple objectives, such as predictive performance and number of parameters, in a single run of the method. We address the second shortcoming by proposing a Lamarckian inheritance mechanism for LEMONADE which generates children networks that are warmstarted with the predictive performance of their trained parents. This is accomplished by using (approximate) network morphism operators for generating children. The combination of these two contributions allows finding models that are on par or even outperform different-sized NASNets, MobileNets, MobileNets V2 and Wide Residual Networks on CIFAR-10 and ImageNet64x64 within only one week on eight GPUs, which is about 20-40x less compute power than previous architecture search methods that yield state-of-the-art performance.

## Bib
@inproceedings{
elsken2018efficient,
title={Efficient Multi-Objective Neural Architecture Search via Lamarckian Evolution},
author={Thomas Elsken and Jan Hendrik Metzen and Frank Hutter},
booktitle={International Conference on Learning Representations},
year={2019},
url={https://openreview.net/forum?id=ByME42AqK7},
}