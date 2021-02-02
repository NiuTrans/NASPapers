# Title
AdversarialNAS: Adversarial Neural Architecture Search for GANs

## Author
Chen Gao, Yunpeng Chen, Si Liu, Zhenxiong Tan, Shuicheng Yan

## Abstract
Neural Architecture Search (NAS) that aims to automate the procedure of architecture design has achieved promising results in many computer vision fields. In this paper, we propose an AdversarialNAS method specially tailored for Generative Adversarial Networks (GANs) to search for a superior generative model on the task of unconditional image generation. The AdversarialNAS is the first method that can search the architectures of generator and discriminator simultaneously in a differentiable manner. During searching, the designed adversarial search algorithm does not need to comput any extra metric to evaluate the performance of the searched architecture, and the search paradigm considers the relevance between the two network architectures and improves their mutual balance. Therefore, AdversarialNAS is very efficient and only takes 1 GPU day to search for a superior generative model in the proposed large search space. Experiments demonstrate the effectiveness and superiority of our method. The discovered generative model sets a new state-of-the-art FID score of 10.87 and highly competitive Inception Score of 8.74 on CIFAR-10. Its transferability is also proven by setting new state-of-the-art FID score of 26.98 and Inception score of 9.63 on STL-10. Code is at: https://github.com/chengaopro/AdversarialNAS.

## Bib
@INPROCEEDINGS{9157134,
  author={C. {Gao} and Y. {Chen} and S. {Liu} and Z. {Tan} and S. {Yan}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={AdversarialNAS: Adversarial Neural Architecture Search for GANs}, 
  year={2020},
  volume={},
  number={},
  pages={5679-5688},
  doi={10.1109/CVPR42600.2020.00572}}