# Title
Auto-Panoptic: Cooperative Multi-Component Architecture Search for Panoptic Segmentation

## Author
Yangxin Wu, Gengwei Zhang, Hang Xu, Xiaodan Liang, Liang Lin

## Abstract
Panoptic segmentation is posed as a new popular test-bed for the state-of-the-art holistic scene understanding methods with the requirement of simultaneously segmenting both foreground things and background stuff. The state-of-the-art panoptic segmentation network exhibits high structural complexity in different network components, i.e. backbone, proposal-based foreground branch, segmentation-based background branch, and feature fusion module across branches, which heavily relies on expert knowledge and tedious trials. In this work, we propose an efficient, cooperative and highly automated framework to simultaneously search for all main components including backbone, segmentation branches, and feature fusion module in a unified panoptic segmentation pipeline based on the prevailing one-shot Network Architecture Search (NAS) paradigm. Notably, we extend the common single-task NAS into the multi-component scenario by taking the advantages of the newly proposed intra-modular search space and problem-oriented inter-modular search space, which helps us to obtain an optimal network architecture that not only performs well in both instance segmentation and semantic segmentation tasks but also be aware of the reciprocal relations between foreground things and background stuff classes. To relieve the vast computation burden incurred by applying NAS to complicated network architectures, we present a novel path-priority greedy search policy to find a robust, transferrable architecture with significantly reduced searching overhead. Our searched architecture, namely Auto-Panoptic, achieves the new state-of-the-art on the challenging COCO and ADE20K benchmarks. Moreover, extensive experiments are conducted to demonstrate the effectiveness of path-priority policy and transferability of Auto-Panoptic across different datasets.

## Bib
@inproceedings{NEURIPS2020_ec1f7645,
 author = {Wu, Yangxin and Zhang, Gengwei and Xu, Hang and Liang, Xiaodan and Lin, Liang},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Larochelle and M. Ranzato and R. Hadsell and M. F. Balcan and H. Lin},
 pages = {20508--20519},
 publisher = {Curran Associates, Inc.},
 title = {Auto-Panoptic: Cooperative Multi-Component Architecture Search for Panoptic Segmentation},
 url = {https://proceedings.neurips.cc/paper/2020/file/ec1f764517b7ffb52057af6df18142b7-Paper.pdf},
 volume = {33},
 year = {2020}
}

