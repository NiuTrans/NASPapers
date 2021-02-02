# Title
Meta-Learning of Neural Architectures for Few-Shot Learning

## Author
Thomas Elsken, Benedikt Staffler, Jan Hendrik Metzen, Frank Hutter

## Abstract
The recent progress in neural architecture search (NAS) has allowed scaling the automated design of neural architectures to real-world domains, such as object detection and semantic segmentation. However, one prerequisite for the application of NAS are large amounts of labeled data and compute resources. This renders its application challenging in few-shot learning scenarios, where many related tasks need to be learned, each with limited amounts of data and compute time. Thus, few-shot learning is typically done with a fixed neural architecture. To improve upon this, we propose MetaNAS, the first method which fully integrates NAS with gradient-based meta-learning. MetaNAS optimizes a meta-architecture along with the meta-weights during meta-training. During meta-testing, architectures can be adapted to a novel task with a few steps of the task optimizer, that is: task adaptation becomes computationally cheap and requires only little data per task. Moreover, MetaNAS is agnostic in that it can be used with arbitrary model-agnostic meta-learning algorithms and arbitrary gradient-based NAS methods. Empirical results on standard few-shot classification benchmarks show that MetaNAS with a combination of DARTS and REPTILE yields state-of-the-art results.

## Bib
@INPROCEEDINGS{9157641,
  author={T. {Elsken} and B. {Staffler} and J. H. {Metzen} and F. {Hutter}},
  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
  title={Meta-Learning of Neural Architectures for Few-Shot Learning}, 
  year={2020},
  volume={},
  number={},
  pages={12362-12372},
  doi={10.1109/CVPR42600.2020.01238}}