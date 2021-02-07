# Title
Graph-Guided Architecture Search for Real-Time Semantic Segmentation

## Author
Peiwen Lin, Peng Sun, Guangliang Cheng, Sirui Xie, Xi Li, Jianping Shi

## Abstract
Designing a lightweight semantic segmentation network often requires researchers to find a trade-off between performance and speed, which is always empirical due to the limited interpretability of neural networks. In order to release researchers from these tedious mechanical trials, we propose a Graph-guided Architecture Search (GAS) pipeline to automatically search real-time semantic segmentation networks. Unlike previous works that use a simplified search space and stack a repeatable cell to form a network, we introduce a novel search mechanism with a new search space where a lightweight model can be effectively explored through the cell-level diversity and latency oriented constraint. Specifically, to produce the cell-level diversity, the cell-sharing constraint is eliminated through the cell-independent manner. Then a graph convolution network (GCN) is seamlessly integrated as a communication mechanism between cells. Finally, a latency-oriented constraint is endowed into the search process to balance the speed and performance. Extensive experiments on Cityscapes and CamVid datasets demonstrate that GAS achieves the new state-of-the-art trade-off between accuracy and speed. In particular, on Cityscapes dataset, GAS achieves the new best performance of 73.5% mIoU with the speed of 108.4 FPS on Titan Xp.

## Bib
@INPROCEEDINGS{9157730,  author={P. {Lin} and P. {Sun} and G. {Cheng} and S. {Xie} and X. {Li} and J. {Shi}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={Graph-Guided Architecture Search for Real-Time Semantic Segmentation},   year={2020},  volume={},  number={},  pages={4202-4211},  doi={10.1109/CVPR42600.2020.00426}}