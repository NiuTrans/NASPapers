# Title
Rethinking Performance Estimation in Neural Architecture Search

## Author
Xiawu Zheng, Rongrong Ji, Qiang Wang, Qixiang Ye, Zhenguo Li, Yonghong Tian, Qi Tian

## Abstract
Neural architecture search (NAS) remains a challenging problem, which is attributed to the indispensable and time-consuming component of performance estimation (PE). In this paper, we provide a novel yet systematic rethinking of PE in a resource constrained regime, termed budgeted PE (BPE), which precisely and effectively estimates the performance of an architecture sampled from an architecture space. Since searching an optimal BPE is extremely time-consuming as it requires to train a large number of networks for evaluation, we propose a Minimum Importance Pruning (MIP) approach. Given a dataset and a BPE search space, MIP estimates the importance of hyper-parameters using random forest and subsequently prunes the minimum one from the next iteration. In this way, MIP effectively prunes less important hyper-parameters to allocate more computational resource on more important ones, thus achieving an effective exploration. By combining BPE with various search algorithms including reinforcement learning, evolution algorithm, random search, and differentiable architecture search, we achieve 1, 000× of NAS speed up with a negligible performance drop comparing to the SOTA.

## Bib
@INPROCEEDINGS{9156290,  author={X. {Zheng} and R. {Ji} and Q. {Wang} and Q. {Ye} and Z. {Li} and Y. {Tian} and Q. {Tian}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={Rethinking Performance Estimation in Neural Architecture Search},   year={2020},  volume={},  number={},  pages={11353-11362},  doi={10.1109/CVPR42600.2020.01137}}