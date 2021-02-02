# Title
Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation

## Author
Chenxi Liu, Liang-Chieh Chen, Florian Schroff, Hartwig Adam, Wei Hua, Alan Yuille, Li Fei-Fei

## Abstract
Recently, Neural Architecture Search (NAS) has successfully identified neural network architectures that exceed human designed ones on large-scale image classification. In this paper, we study NAS for semantic image segmentation. Existing works often focus on searching the repeatable cell structure, while hand-designing the outer network structure that controls the spatial resolution changes. This choice simplifies the search space, but becomes increasingly problematic for dense image prediction which exhibits a lot more network level architectural variations. Therefore, we propose to search the network level structure in addition to the cell level structure, which forms a hierarchical architecture search space. We present a network level search space that includes many popular designs, and develop a formulation that allows efficient gradient-based architecture search (3 P100 GPU days on Cityscapes images). We demonstrate the effectiveness of the proposed method on the challenging Cityscapes, PASCAL VOC 2012, and ADE20K datasets. Auto-DeepLab, our architecture searched specifically for semantic image segmentation, attains state-of-the-art performance without any ImageNet pretraining.

## Bib
@INPROCEEDINGS{8954247,
  author={C. {Liu} and L. {Chen} and F. {Schroff} and H. {Adam} and W. {Hua} and A. L. {Yuille} and L. {Fei-Fei}},
  booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation}, 
  year={2019},
  volume={},
  number={},
  pages={82-92},
  doi={10.1109/CVPR.2019.00017}
}