# Title
Block-Wisely Supervised Neural Architecture Search With Knowledge Distillation

## Author
Changlin Li, Jiefeng Peng, Liuchun Yuan, Guangrun Wang, Xiaodan Liang, Liang Lin, Xiaojun Chang

## Abstract
Neural Architecture Search (NAS), aiming at automatically designing network architectures by machines, is expected to bring about a new revolution in machine learning. Despite these high expectation, the effectiveness and efficiency of existing NAS solutions are unclear, with some recent works going so far as to suggest that many existing NAS solutions are no better than random architecture selection. The ineffectiveness of NAS solutions may be attributed to inaccurate architecture evaluation. Specifically, to speed up NAS, recent works have proposed under-training different candidate architectures in a large search space concurrently by using shared network parameters; however, this has resulted in incorrect architecture ratings and furthered the ineffectiveness of NAS. In this work, we propose to modularize the large search space of NAS into blocks to ensure that the potential candidate architectures are fully trained; this reduces the representation shift caused by the shared parameters and leads to the correct rating of the candidates. Thanks to the block-wise search, we can also evaluate all of the candidate architectures within each block. Moreover, we find that the knowledge of a network model lies not only in the network parameters but also in the network architecture. Therefore, we propose to distill the neural architecture (DNA) knowledge from a teacher model to supervise our block-wise architecture search, which significantly improves the effectiveness of NAS. Remarkably, the performance of our searched architectures has exceeded the teacher model, demonstrating the practicability of our method. Finally, our method achieves a state-of-the-art 78.4% top-1 accuracy on ImageNet in a mobile setting. All of our searched models along with the evaluation code are available at https://github.com/changlin31/DNA.

## Bib
@INPROCEEDINGS{9157026,
  author={C. {Li} and J. {Peng} and L. {Yuan} and G. {Wang} and X. {Liang} and L. {Lin} and X. {Chang}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Block-Wisely Supervised Neural Architecture Search With Knowledge Distillation}, 
  year={2020},
  volume={},
  number={},
  pages={1986-1995},
  doi={10.1109/CVPR42600.2020.00206}}