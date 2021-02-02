# Title
All in One Bad Weather Removal Using Architectural Search

## Author
Ruoteng Li, Robby T. Tan, Loong-Fah Cheong

## Abstract
Many methods have set state-of-the-art performance on restoring images degraded by bad weather such as rain, haze, fog, and snow, however they are designed specifically to handle one type of degradation. In this paper, we propose a method that can handle multiple bad weather degradations: rain, fog, snow and adherent raindrops using a single network. To achieve this, we first design a generator with multiple task-specific encoders, each of which is associated with a particular bad weather degradation type. We utilize a neural architecture search to optimally process the image features extracted from all encoders. Subsequently, to convert degraded image features to clean background features, we introduce a series of tensor-based operations encapsulating the underlying physics principles behind the formation of rain, fog, snow and adherent raindrops. These operations serve as the basic building blocks for our architectural search. Finally, our discriminator simultaneously assesses the correctness and classifies the degradation type of the restored image. We design a novel adversarial learning scheme that only backpropagates the loss of a degradation type to the respective task-specific encoder. Despite being designed to handle different types of bad weather, extensive experiments demonstrate that our method performs competitively to the individual and dedicated state-of-the-art image restoration methods.

## Bib
@INPROCEEDINGS{9157460,
  author={R. {Li} and R. T. {Tan} and L. -F. {Cheong}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={All in One Bad Weather Removal Using Architectural Search}, 
  year={2020},
  volume={},
  number={},
  pages={3172-3182},
  doi={10.1109/CVPR42600.2020.00324}}