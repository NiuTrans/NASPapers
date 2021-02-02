# Title
SGAS: Sequential Greedy Architecture Search

## Author
Guohao Li, Guocheng Qian, Itzel C. Delgadillo, Matthias Müller, Ali Thabet, Bernard Ghanem

## Abstract
Architecture design has become a crucial component of successful deep learning. Recent progress in automatic neural architecture search (NAS) shows a lot of promise. However, discovered architectures often fail to generalize in the final evaluation. Architectures with a higher validation accuracy during the search phase may perform worse in the evaluation. Aiming to alleviate this common issue, we introduce sequential greedy architecture search (SGAS), an efficient method for neural architecture search. By dividing the search procedure into sub-problems, SGAS chooses and prunes candidate operations in a greedy fashion. We apply SGAS to search architectures for Convolutional Neural Networks (CNN) and Graph Convolutional Networks (GCN). Extensive experiments show that SGAS is able to find state-of-the-art architectures for tasks such as image classification, point cloud classification and node classification in protein-protein interaction graphs with minimal computational cost.

## Bib
@INPROCEEDINGS{9157406,
  author={G. {Li} and G. {Qian} and I. C. {Delgadillo} and M. {Müller} and A. {Thabet} and B. {Ghanem}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={SGAS: Sequential Greedy Architecture Search}, 
  year={2020},
  volume={},
  number={},
  pages={1617-1627},
  doi={10.1109/CVPR42600.2020.00169}}