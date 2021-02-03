# Title
AtomNAS: Fine-Grained End-to-End Neural Architecture Search

## Venue
ICLR

## Author
Jieru Mei, Yingwei Li, Xiaochen Lian, Xiaojie Jin, Linjie Yang, Alan Yuille, Jianchao Yang

## Abstract
Search space design is very critical to neural architecture search (NAS) algorithms. We propose a fine-grained search space comprised of atomic blocks, a minimal search unit that is much smaller than the ones used in recent NAS algorithms. This search space allows a mix of operations by composing different types of atomic blocks, while the search space in previous methods only allows homogeneous operations. Based on this search space, we propose a resource-aware architecture search framework which automatically assigns the computational resources (e.g., output channel numbers) for each operation by jointly considering the performance and the computational cost. In addition, to accelerate the search process, we propose a dynamic network shrinkage technique which prunes the atomic blocks with negligible influence on outputs on the fly.  Instead of a search-and-retrain two-stage paradigm, our method simultaneously searches and trains the target architecture. 
Our method achieves state-of-the-art performance under several FLOPs configurations on ImageNet with a small searching cost.
We open our entire codebase at: https://github.com/meijieru/AtomNAS.

## Bib
@inproceedings{
Mei2020AtomNAS:,
title={AtomNAS: Fine-Grained End-to-End Neural Architecture Search},
author={Jieru Mei and Yingwei Li and Xiaochen Lian and Xiaojie Jin and Linjie Yang and Alan Yuille and Jianchao Yang},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=BylQSxHFwr}
}