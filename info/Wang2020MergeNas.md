# Title
MergeNAS: Merge Operations into One for Differentiable Architecture Search

## Author
Xiaoxing Wang, Chao Xue, Junchi Yan, Xiaokang Yang, Yonggang Hu, Kewei Sun

## Abstract
Differentiable architecture search (DARTS) has been a promising one-shot architecture search approach for its mathematical formulation and competitive results. However, besides its caused high memory utilization and a large computation requirement, many research works have shown that DARTS also often suffers notable over-fitting and thus does not work robustly for some new tasks. In this paper, we propose a one-shot neural architecture search method referred to as MergeNAS by merging different types of operations e.g. convolutions into one operation. This merge-based approach not only reduces the search cost (about half a GPU day), but also alleviates over-fitting by reducing the redundant parameters. Extensive experiments on different search space and various datasets have been conducted to verify our approach, showing that MergeNAS can converge to a stable architecture and achieve better performance with fewer parameters and search cost. For test accuracy and its stability, MergeNAS outperforms all NAS baseline methods implemented on NAS-Bench-201, including DARTS, ENAS, RS, BOHB, GDAS and hand-crafted ResNet.

## Bib
@inproceedings{ijcai2020-0424,
  title     = {MergeNAS: Merge Operations into One for Differentiable Architecture Search},
  author    = {Wang, Xiaoxing and Xue, Chao and Yan, Junchi and Yang, Xiaokang and Hu, Yonggang and Sun, Kewei},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {3065--3072},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/424},
  url       = {https://doi.org/10.24963/ijcai.2020/424},
}
