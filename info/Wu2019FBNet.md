# Title
FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search

## Author
Bichen Wu, Xiaoliang Dai, Peizhao Zhang, Yanghan Wang, Fei Sun, Yiming Wu, Yuandong Tian, Peter Vajda, Yangqing Jia, Kurt Keutzer

## Abstract
Designing accurate and efficient ConvNets for mobile devices is challenging because the design space is combinatorially large. Due to this, previous neural architecture search (NAS) methods are computationally expensive. ConvNet architecture optimality depends on factors such as input resolution and target devices. However, existing approaches are too resource demanding for case-by-case redesigns. Also, previous work focuses primarily on reducing FLOPs, but FLOP count does not always reflect actual latency. To address these, we propose a differentiable neural architecture search (DNAS) framework that uses gradient-based methods to optimize ConvNet architectures, avoiding enumerating and training individual architectures separately as in previous methods. FBNets (Facebook-Berkeley-Nets), a family of models discovered by DNAS surpass state-of-the-art models both designed manually and generated automatically. FBNet-B achieves 74.1% top-1 accuracy on ImageNet with 295M FLOPs and 23.1 ms latency on a Samsung S8 phone, 2.4x smaller and 1.5x faster than MobileNetV2-1.3 with similar accuracy. Despite higher accuracy and lower latency than MnasNet, we estimate FBNet-B's search cost is 420x smaller than MnasNet's, at only 216 GPU-hours. Searched for different resolutions and channel sizes, FBNets achieve 1.5% to 6.4% higher accuracy than MobileNetV2. The smallest FBNet achieves 50.2% accuracy and 2.9 ms latency (345 frames per second) on a Samsung S8. Over a Samsung-optimized FBNet, the iPhone-X-optimized model achieves a 1.4x speedup on an iPhone X. FBNet models are open-sourced at https://github.com/facebookresearch/mobile-vision.

## Bib
@INPROCEEDINGS{8953587,
  author={B. {Wu} and X. {Dai} and P. {Zhang} and Y. {Wang} and F. {Sun} and Y. {Wu} and Y. {Tian} and P. {Vajda} and Y. {Jia} and K. {Keutzer}},
  booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search}, 
  year={2019},
  volume={},
  number={},
  pages={10726-10734},
  doi={10.1109/CVPR.2019.01099}
  }