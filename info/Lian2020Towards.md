# Title
Towards Fast Adaptation of Neural Architectures with Meta Learning

## Author
Dongze Lian, Yin Zheng, Yintao Xu, Yanxiong Lu, Leyu Lin, Peilin Zhao, Junzhou Huang, Shenghua Gao

## Abstract
Recently, Neural Architecture Search (NAS) has been successfully applied to multiple artificial intelligence areas and shows better performance compared with hand-designed networks. However, the existing NAS methods only target a specific task. Most of them usually do well in searching an architecture for single task but are troublesome for multiple datasets or multiple tasks. Generally, the architecture for a new task is either searched from scratch, which is neither efficient nor flexible enough for practical application scenarios, or borrowed from the ones searched on other tasks, which might be not optimal. In order to tackle the transferability of NAS and conduct fast adaptation of neural architectures, we propose a novel Transferable Neural Architecture Search method based on meta-learning in this paper, which is termed as T-NAS. T-NAS learns a meta-architecture that is able to adapt to a new task quickly through a few gradient steps, which makes the transferred architecture suitable for the specific task. Extensive experiments show that T-NAS achieves state-of-the-art performance in few-shot learning and comparable performance in supervised learning but with 50x less searching cost, which demonstrates the effectiveness of our method.

## Bib
@inproceedings{
Lian2020Towards,
title={Towards Fast Adaptation of Neural Architectures with Meta Learning},
author={Dongze Lian and Yin Zheng and Yintao Xu and Yanxiong Lu and Leyu Lin and Peilin Zhao and Junzhou Huang and Shenghua Gao},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=r1eowANFvr}
}