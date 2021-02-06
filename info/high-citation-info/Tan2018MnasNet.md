# Title 
MnasNet: Platform-Aware Neural Architecture Search for Mobile

## Venue
CVPR

## Author 
Mingxing Tan, Bo Chen, Ruoming Pang, Vijay Vasudevan, Mark Sandler, Andrew Howard, Quoc V. Le
## Abstract 
Designing convolutional neural networks (CNN) for mobile devices is challenging because mobile models need to be small and fast, yet still accurate. Although significant efforts have been dedicated to design and improve mobile CNNs on all dimensions, it is very difficult to manually balance these trade-offs when there are so many architectural possibilities to consider. In this paper, we propose an automated mobile neural architecture search (MNAS) approach, which explicitly incorporate model latency into the main objective so that the search can identify a model that achieves a good trade-off between accuracy and latency. Unlike previous work, where latency is considered via another, often inaccurate proxy (e.g., FLOPS), our approach directly measures real-world inference latency by executing the model on mobile phones. To further strike the right balance between flexibility and search space size, we propose a novel factorized hierarchical search space that encourages layer diversity throughout the network. Experimental results show that our approach consistently outperforms state-of-the-art mobile CNN models across multiple vision tasks. On the ImageNet classification task, our MnasNet achieves 75.2% top-1 accuracy with 78ms latency on a Pixel phone, which is 1.8x faster than MobileNetV2 [29] with 0.5% higher accuracy and 2.3x faster than NASNet [36] with 1.2% higher accuracy. Our MnasNet also achieves better mAP quality than MobileNets for COCO object detection. Code is at [this https URL](https://github.com/tensorflow/tpu/tree/master/models/official/mnasnet)
## Bib
@article{DBLP:journals/corr/abs-1807-11626,
  author    = {Mingxing Tan and
               Bo Chen and
               Ruoming Pang and
               Vijay Vasudevan and
               Quoc V. Le},
  title     = {MnasNet: Platform-Aware Neural Architecture Search for Mobile},
  journal   = {CoRR},
  volume    = {abs/1807.11626},
  year      = {2018},
  url       = {http://arxiv.org/abs/1807.11626},
  archivePrefix = {arXiv},
  eprint    = {1807.11626},
  timestamp = {Mon, 13 Aug 2018 16:46:25 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1807-11626.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}