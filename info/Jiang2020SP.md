# Title
SP-NAS: Serial-to-Parallel Backbone Search for Object Detection

## Author
Chenhan Jiang, Hang Xu, Wei Zhang, Xiaodan Liang, Zhenguo Li

## Abstract
Advanced object detectors usually adopt a backbone network designed and pretrained by ImageNet classification. Recently neural architecture search (NAS) has emerged to automatically design a task-specific backbone to bridge the gap between the tasks of classification and detection. In this paper, we propose a two-phase serial-to-parallel architecture search framework named SP-NAS towards a flexible task-oriented detection backbone. Specifically, the serial-searching round aims at finding a sequence of serial blocks with optimal scale and output channels in the feature hierarchy by a Swap-Expand-Reignite search algorithm; the parallel-searching phase then assembles several sub-architectures along with the previous searched backbone into a more powerful parallel-structured backbone. We efficiently search a detection backbone by exploring a network morphism strategy on multiple detection benchmarks. The resulting architectures achieve SOTA results, i.e. top performance (LAMR: 0.055) on the automotive detection leaderboard of EuroCityPersons benchmark, improving 2.3% mAP with less FLOPS than NAS-FPN on COCO, and reaching 84.1% AP50 on VOC better than DetNAS and Auto-FPN in terms of both accuracy and speed.

## Bib
@INPROCEEDINGS{9156649,  author={C. {Jiang} and H. {Xu} and W. {Zhang} and X. {Liang} and Z. {Li}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={SP-NAS: Serial-to-Parallel Backbone Search for Object Detection},   year={2020},  volume={},  number={},  pages={11860-11869},  doi={10.1109/CVPR42600.2020.01188}}