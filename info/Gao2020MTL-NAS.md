# Title
MTL-NAS: Task-Agnostic Neural Architecture Search Towards General-Purpose Multi-Task Learning

## Author
Yuan Gao, Haoping Bai, Zequn Jie, Jiayi Ma, Kui Jia, Wei Liu

## Abstract
We propose to incorporate neural architecture search (NAS) into general-purpose multi-task learning (GP-MTL). Existing NAS methods typically define different search spaces according to different tasks. In order to adapt to different task combinations (i.e., task sets), we disentangle the GP-MTL networks into single-task backbones (optionally encode the task priors), and a hierarchical and layerwise features sharing/fusing scheme across them. This enables us to design a novel and general task-agnostic search space, which inserts cross-task edges (i.e., feature fusion connections) into fixed single-task network backbones. Moreover, we also propose a novel single-shot gradient-based search algorithm that closes the performance gap between the searched architectures and the final evaluation architecture. This is realized with a minimum entropy regularization on the architecture weights during the search phase, which makes the architecture weights converge to near-discrete values and therefore achieves a single model. As a result, our searched model can be directly used for evaluation without (re-)training from scratch. We perform extensive experiments using different single-task backbones on various task sets, demonstrating the promising performance obtained by exploiting the hierarchical and layerwise features, as well as the desirable generalizability to different i) task sets and ii) single-task backbones. The code of our paper is available at https://github.com/bhpfelix/MTLNAS.

## Bib
@INPROCEEDINGS{9157640,
  author={Y. {Gao} and H. {Bai} and Z. {Jie} and J. {Ma} and K. {Jia} and W. {Liu}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={MTL-NAS: Task-Agnostic Neural Architecture Search Towards General-Purpose Multi-Task Learning}, 
  year={2020},
  volume={},
  number={},
  pages={11540-11549},
  doi={10.1109/CVPR42600.2020.01156}}