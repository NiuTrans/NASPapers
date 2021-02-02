# Title
Overcoming Multi-Model Forgetting in One-Shot NAS With Diversity Maximization

## Author
Miao Zhang, Huiqi Li, Shirui Pan, Xiaojun Chang, Steven Su

## Abstract
One-Shot Neural Architecture Search (NAS) significantly improves the computational efficiency through weight sharing. However, this approach also introduces multi-model forgetting during the supernet training (architecture search phase), where the performance of previous architectures degrade when sequentially training new architectures with partially-shared weights. To overcome such catastrophic forgetting, the state-of-the-art method assumes that the shared weights are optimal when jointly optimizing a posterior probability. However, this strict assumption is not necessarily held for One-Shot NAS in practice. In this paper, we formulate the supernet training in the One-Shot NAS as a constrained optimization problem of continual learning that the learning of current architecture should not degrade the performance of previous architectures during the supernet training. We propose a Novelty Search based Architecture Selection (\textbf{NSAS}) loss function and demonstrate that the posterior probability could be calculated without the strict assumption when maximizing the diversity of the selected constraints. A greedy novelty search method is devised to find the most representative subset to regularize the supernet training. We apply our proposed approach to two One-Shot NAS baselines, random sampling NAS (RandomNAS) and gradient-based sampling NAS (GDAS). Extensive experiments demonstrate that our method enhances the predictive ability of the supernet in One-Shot NAS and achieves remarkable performance on CIFAR-10, CIFAR-100, and PTB with efficiency.

## Bib
@INPROCEEDINGS{9156768,
  author={M. {Zhang} and H. {Li} and S. {Pan} and X. {Chang} and S. {Su}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Overcoming Multi-Model Forgetting in One-Shot NAS With Diversity Maximization}, 
  year={2020},
  volume={},
  number={},
  pages={7806-7815},
  doi={10.1109/CVPR42600.2020.00783}}