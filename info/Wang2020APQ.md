# Title
APQ: Joint Search for Network Architecture, Pruning and Quantization Policy

## Author
Tianzhe Wang, Kuan Wang, Han Cai, Ji Lin, Zhijian Liu, Hanrui Wang, Yujun Lin, Song Han

## Abstract
We present APQ, a novel design methodology for efficient deep learning deployment. Unlike previous methods that separately optimize the neural network architecture, pruning policy, and quantization policy, we design to optimize them in a joint manner. To deal with the larger design space it brings, we devise to train a quantization-aware accuracy predictor that is fed to the evolutionary search to select the best fit. Since directly training such a predictor requires time-consuming quantization data collection, we propose to use predictor-transfer technique to get the quantization-aware predictor: we first generate a large dataset of 〈NN architecture, ImageNet accuracy〉 pairs by sampling a pretrained unified once-for-all network and doing direct evaluation; then we use these data to train an accuracy predictor without quantization, followed by transferring its weights to train the quantization-aware predictor, which largely reduces the quantization data collection time. Extensive experiments on ImageNet show the benefits of this joint design methodology: the model searched by our method maintains the same level accuracy as ResNet34 8-bit model while saving 8× BitOps; we achieve 2×/1.3× latency/energy saving compared to MobileNetV2+HAQ [30, 36] while obtaining the same level accuracy; the marginal search cost ofjoint optimization for a new deployment scenario outperforms separate optimizations using ProxylessNAS+AMC+HAQ [5, 12, 36] by 2.3% accuracy while reducing orders of magnitude GPU hours and CO 2 emission with respect to the training cost.

## Bib
@INPROCEEDINGS{9156411,
  author={T. {Wang} and K. {Wang} and H. {Cai} and J. {Lin} and Z. {Liu} and H. {Wang} and Y. {Lin} and S. {Han}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={APQ: Joint Search for Network Architecture, Pruning and Quantization Policy}, 
  year={2020},
  volume={},
  number={},
  pages={2075-2084},
  doi={10.1109/CVPR42600.2020.00215}}