# Title
AutoSpeech: Neural Architecture Search for Speaker Recognition

## Author
Shaojin Ding, Tianlong Chen, Xinyu Gong, Weiwei Zha, Zhangyang Wang

## Abstract
Speaker recognition systems based on Convolutional Neural Networks (CNNs) are often built with off-the-shelf backbones such as VGG-Net or ResNet. However, these backbones were originally proposed for image classification, and therefore may not be naturally fit for speaker recognition. Due to the prohibitive complexity of manually exploring the design space, we propose the first neural architecture search approach for the speaker recognition tasks, named as AutoSpeech. Our algorithm first identifies the optimal operation combination in a neural cell and then derives a CNN model by stacking the neural cell for multiple times. The final speaker recognition model can be obtained by training the derived CNN model through the standard scheme. To evaluate the proposed approach, we conduct experiments on both speaker identification and speaker verification tasks using the VoxCeleb1 dataset. Results demonstrate that the derived CNN architectures from the proposed approach significantly outperform current speaker recognition systems based on VGG-M, ResNet-18, and ResNet-34 backbones, while enjoying lower model complexity.

## Bib
@inproceedings{Ding2020,
  author={Shaojin Ding and Tianlong Chen and Xinyu Gong and Weiwei Zha and Zhangyang Wang},
  title={{AutoSpeech: Neural Architecture Search for Speaker Recognition}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={916--920},
  doi={10.21437/Interspeech.2020-1258},
  url={http://dx.doi.org/10.21437/Interspeech.2020-1258}
}