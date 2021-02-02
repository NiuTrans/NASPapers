# Title 
NAS-FCOS: Fast Neural Architecture Search for Object Detection
## Author 
Ning Wang, Yang Gao, Hao Chen, Peng Wang, Zhi Tian, Chunhua Shen, Yanning Zhang
## Abstract 
The success of deep neural networks relies on significant architecture engineering. Recently neural architecture search (NAS) has emerged as a promise to greatly reduce manual effort in network design by automatically searching for optimal architectures, although typically such algorithms need an excessive amount of computational resources, e.g., a few thousand GPU-days. To date, on challenging vision tasks such as object detection, NAS, especially fast versions of NAS, is less studied. Here we propose to search for the decoder structure of object detectors with search efficiency being taken into consideration. To be more specific, we aim to efficiently search for the feature pyramid network (FPN) as well as the prediction head of a simple anchor-free object detector, namely FCOS, using a tailored reinforcement learning paradigm. With carefully designed search space, search algorithms and strategies for evaluating network quality, we are able to efficiently search a top-performing detection architecture within 4 days using 8 V100 GPUs. The discovered architecture surpasses state-of-the-art object detection models (such as Faster R-CNN, RetinaNet and FCOS) by 1.5 to 3.5 points in AP on the COCO dataset, with comparable computation complexity and memory footprint, demonstrating the efficacy of the proposed NAS for object detection.
## Bib
@article{DBLP:journals/corr/abs-1906-04423,
  author    = {Ning Wang and
               Yang Gao and
               Hao Chen and
               Peng Wang and
               Zhi Tian and
               Chunhua Shen},
  title     = {{NAS-FCOS:} Fast Neural Architecture Search for Object Detection},
  journal   = {CoRR},
  volume    = {abs/1906.04423},
  year      = {2019},
  url       = {http://arxiv.org/abs/1906.04423},
  archivePrefix = {arXiv},
  eprint    = {1906.04423},
  timestamp = {Thu, 12 Nov 2020 13:40:45 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1906-04423.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}