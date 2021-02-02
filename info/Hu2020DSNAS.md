# Title
DSNAS: Direct Neural Architecture Search Without Parameter Retraining

## Author
Shoukang Hu, Sirui Xie, Hehui Zheng, Chunxiao Liu, Jianping Shi, Xunying Liu, Dahua Lin

## Abstract
If NAS methods are solutions, what is the problem? Most existing NAS methods require two-stage parameter optimization. However, performance of the same architecture in the two stages correlates poorly. In this work, we propose a new problem definition for NAS, task-specific end-to-end, based on this observation. We argue that given a computer vision task for which a NAS method is expected, this definition can reduce the vaguely-defined NAS evaluation to i) accuracy of this task and ii) the total computation consumed to finally obtain a model with satisfying accuracy. Seeing that most existing methods do not solve this problem directly, we propose DSNAS, an efficient differentiable NAS framework that simultaneously optimizes architecture and parameters with a low-biased Monte Carlo estimate. Child networks derived from DSNAS can be deployed directly without parameter retraining. Comparing with two-stage methods, DSNAS successfully discovers networks with comparable accuracy (74.4%) on ImageNet in 420 GPU hours, reducing the total time by more than 34%.

## Bib
@INPROCEEDINGS{9157467,
  author={S. {Hu} and S. {Xie} and H. {Zheng} and C. {Liu} and J. {Shi} and X. {Liu} and D. {Lin}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={DSNAS: Direct Neural Architecture Search Without Parameter Retraining}, 
  year={2020},
  volume={},
  number={},
  pages={12081-12089},
  doi={10.1109/CVPR42600.2020.01210}}