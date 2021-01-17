# A Paper List of Neural Architecture Search

In this document, we list the papers published from 2017 to August 2020 on Neural Architecture Search (NAS). We categorize these papers into different topics. Moreover, we find the code for some of the papers (if have).

## Outline

- [A Paper List of Neural Architecture Search](#a-paper-list-of-neural-architecture-search)
  - [Outline](#outline)
  - [A Short List](#a-short-list)
  - [A Long List](#a-long-list)
    - [Surveys - S](#surveys---s)
    - [Reinforcement Learning Methods - RL](#reinforcement-learning-methods---rl)
    - [Gradient-based Methods - G](#gradient-based-methods---g)
    - [Evolutionary Algorithms - EA](#evolutionary-algorithms---ea)
    - [Performance Prediction - PD](#performance-prediction---pd)
    - [Others - O](#others---o)
    - [Random Search](#random-search)
    - [Bayesian Optimization](#bayesian-optimization)
    - [Search Space](#search-space)
    - [High Citation Papers](#high-citation-papers)
  - [Systems](#systems)
  - [Team Members](#team-members)

*Data was from [Google Scholar](https://scholar.google.com/), and was updated on September 12th*  
*Italic in code links indicates these codes are not written by the authors of the paper. (like [GitHub]())*  
*Bold in titles means these papers are widely cited. Here we follow the standards below to judge its popularity. Only papers meeting the following conditions will be marked in bold.*  

+ *Papers published in 2020 are cited by more than or equal to 20 papers.* 
+ *Papers published in 2019 are cited by more than or equal to 100 papers.* 
+ *Papers published before 2019 are cited by more than or equal to 500 papers.* 

## A Short List

For a quick look at the field, here is a short list of must-read papers

## A Long List

### Surveys - S
| Title                                    | Venue |     Type     |                   Code                   | Year |
| :--------------------------------------- | :---: | :----------: | :--------------------------------------: | :--: |
| [Neural architecture search: A survey](http://jmlr.org/papers/v20/18-598.html) | JMLR  |    S    |                    -                     | 2018 |
| [A Survey on Neural Architecture Search](https://arxiv.org/abs/1905.01392) |   -   |    S    |                    -                     | 2019 |
| [Reinforcement Learning for Neural Architecture Search: A Review](https://www.sciencedirect.com/science/article/abs/pii/S0262885619300885) |  IVC  |  RL/S   |                    -                     | 2019 |
| [A Comprehensive Survey of Neural Architecture Search: Challenges and Solutions](https://arxiv.org/abs/2006.02903) |   -   |    S    |                    -                     | 2020 |
| [Evaluating The Search Phase of Neural Architecture Search](https://openreview.net/forum?id=H1loF2NFwr) | ICLR  | O/S | [github](https://github.com/kcyu2014/eval-nas) | 2020 |
| [**NAS evaluation is frustratingly hard**](https://openreview.net/forum?id=HygrdpVKvr) | ICLR  | O/S | [github](https://github.com/antoyang/NAS-Benchmark) | 2020 |



### Reinforcement Learning Methods - RL
| Title                                    |  Venue  |   Type    |                   Code                   | Year |
| :--------------------------------------- | :-----: | :-------: | :--------------------------------------: | :--: |
| [**Neural Architecture Search with Reinforcement Learning**](https://openreview.net/forum?id=r1Ue8Hcxg) |  ICLR   |    RL     |                    -                     | 2017 |
| [Learning to Compose Domain-Specific Transformations for Data Augmentation](http://papers.nips.cc/paper/6916-learning-to-compose-domain-specific-transformations-for-data-augmentation) | NeurIPS |    RL     |                    -                     | 2017 |
| [N2N learning: Network to Network Compression via Policy Gradient Reinforcement Learning](https://openreview.net/forum?id=B1hcZZ-AW) |  ICLR   |    RL     |                    -                     | 2017 |
| [**Designing Neural Network Architectures using Reinforcement Learning**](https://openreview.net/forum?id=S1c2cvqee) |  ICLR   |    RL     | [github](https://github.com/bowenbaker/metaqnn) | 2017 |
| [Neural Optimizer Search with Reinforcement Learning](http://proceedings.mlr.press/v70/bello17a.html) |  ICML   |    RL     |                    -                     | 2017 |
| [**Efficient Neural Architecture Search via Parameter Sharing**](http://proceedings.mlr.press/v80/pham18a.html) |  ICML   |    RL     | [github](https://github.com/carpedm20/ENAS-pytorch) | 2018 |
| [Efficient Architecture Search by Network Transformation](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16755) |  AAAI   |    RL     | [github](https://github.com/han-cai/EAS) | 2018 |
| [A Flexible Approach to Automated RNN Architecture Generation](https://openreview.net/forum?id=SkOb1Fl0Z) |  ICLR   |   RL/PD   |                    -                     | 2018 |
| [**Learning Transferable Architectures for Scalable Image Recognition**](https://ieeexplore.ieee.org/document/8579005) |  CVPR   |    RL     | [github](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet) | 2018 |
| [Practical Block-wise Neural Network Architecture Generation](https://ieeexplore.ieee.org/document/8578355/) |  CVPR   |    RL     |                    -                     | 2018 |
| [Path-Level Network Transformation for Efficient Architecture Search](http://proceedings.mlr.press/v80/cai18a.html) |  ICML   |    RL     | [github](https://github.com/han-cai/PathLevel-EAS) | 2018 |
| [**MnasNet: Platform-Aware Neural Architecture Search for Mobile**](https://ieeexplore.ieee.org/document/8954198/) |  CVPR   |   RL   | [github](https://github.com/AnjieZheng/MnasNet-PyTorch) | 2018 |
| [Faster Discovery of Neural Architectures by Searching for Paths in a Large Model](https://openreview.net/forum?id=rJkCq4JvM) |  ICLR  |    RL    | - | 2018 |
| [GitGraph - from Computational Subgraphs to Smaller Architecture Search Spaces](https://openreview.net/forum?id=rkiO1_1Pz) |  ICLR  |    RL    | - | 2018 |
| [UNAS: Differentiable Architecture Search Meets Reinforcement Learning](https://ieeexplore.ieee.org/document/9156297/) |  CVPR  |    G/RL    | - | 2018 |
| [Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells](https://ieeexplore.ieee.org/document/8953530/) |  CVPR   |    RL     | [github](https://github.com/DrSleep/nas-segm-pytorch) | 2019 |
| [Reinforcement Learning for Neural Architecture Search: A Review](https://www.sciencedirect.com/science/article/abs/pii/S0262885619300885) |   IVC   | RL/S |                    -                     | 2019 |
| [Can Weight Sharing Outperform Random Architecture Search? An Investigation With TuNAS](https://ieeexplore.ieee.org/document/9157751/) |  CVPR   |    RL     |                    -                     | 2019 |
| [Continual and Multi-Task Architecture Search](https://www.aclweb.org/anthology/P19-1185/) |   ACL   |    RL     | [github](https://www.aclweb.org/anthology/P19-1185/) | 2019 |
| [AutoGAN: Neural Architecture Search for Generative Adversarial Networks](https://openaccess.thecvf.com/content_ICCV_2019/html/Gong_AutoGAN_Neural_Architecture_Search_for_Generative_Adversarial_Networks_ICCV_2019_paper.html) |  ICCV   |    RL     | [github](https://github.com/TAMU-VITA/AutoGAN) | 2019 |
| [**ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware**](https://openreview.net/forum?id=HylVB3AqYm) |  ICLR   |   RL/G    | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 |
| [IRLAS: Inverse Reinforcement Learning for Architecture Search](https://ieeexplore.ieee.org/document/8954365/) |  CVPR  |    RL    | - | 2019 |
| [RENAS: Reinforced Evolutionary Neural Architecture Search](https://ieeexplore.ieee.org/document/8953426/) |  CVPR   |   EA/RL   | [github](https://github.com/yukang2017/RENAS) | 2019 |
| [AM-LFS: AutoML for Loss Function Search](https://openaccess.thecvf.com/content_ICCV_2019/html/Li_AM-LFS_AutoML_for_Loss_Function_Search_ICCV_2019_paper.html) |  ICCV  |    RL    | - | 2019 |
| [NAT: Neural Architecture Transformer for Accurate and Compact Architectures](https://papers.nips.cc/paper/8362-nat-neural-architecture-transformer-for-accurate-and-compact-architectures.html) |  NeurlPS  |    RL    | [github](https://github.com/guoyongcs/NAT) | 2019 |
| [MoSaNAS: Multi-Objective Surrogate-Assisted Neural Architecture Search](https://arxiv.org/abs/2001.08437) |  ECCV  |    RL    | - | 2020 |
| [S2DNAS: Transforming Static CNN Model for Dynamic Inference via Neural Architecture Search](https://arxiv.org/abs/1911.07033v2) |  ECCV  |    RL    | - | 2020 |
| [Breaking the Curse of Space Explosion: Towards Efficient NAS with Curriculum Search](https://arxiv.org/abs/2007.07197) |  ICML  |    RL    | [github](https://github.com/guoyongcs/CNAS) | 2020 |
| [NAS-FCOS: Fast Neural Architecture Search for Object Detection](https://ieeexplore.ieee.org/document/9156326/) |  CVPR  |    RL    | [github](https://github.com/Lausannen/NAS-FCOS) | 2020 |
| [Graph Neural Architecture Search](https://www.ijcai.org/Proceedings/2020/0195) |  IJCAI  |    RL    | [github](https://github.com/GraphNAS/GraphNAS) | 2020 |
| [InstaNAS: Instance-aware Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/5764) |  AAAI  |    RL    | [github](https://github.com/AnjieCheng/InstaNAS) | 2020 |
| [Towards Oracle Knowledge Distillation with Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/5866) |  AAAI  |    RL    | - | 2020 |



### Gradient-based Methods - G
| Title                                    |  Venue  | Type |                   Code                   | Year |
| :--------------------------------------- | :-----: | :--: | :--------------------------------------: | :--: |
| [**DARTS: Differentiable Architecture Search**](https://openreview.net/forum?id=S1eYHoC5FX) |  ICLR   |  G   | [github](https://github.com/quark0/darts) | 2018 |
| [Understanding and Simplifying One-Shot Architecture Search](http://proceedings.mlr.press/v80/bender18a.html) |  ICML   |  G   |                    -                     | 2018 |
| [SMASH: One-Shot Model Architecture Search through HyperNetworks](https://openreview.net/forum?id=rydeCEhs-) |  ICLR   |  G   | [github](https://github.com/ajbrock/SMASH) | 2018 |
| [Neural Architecture Optimization](http://papers.nips.cc/paper/8007-neural-architecture-optimization) | NeurIPS |  G   | [github](https://github.com/renqianluo/NAO) | 2018 |
| [Differentiable Neural Network Architecture Search](https://openreview.net/forum?id=BJ-MRKkwG) | ICLR-W  |  G   |                    -                     | 2018 |
| [**ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware**](https://openreview.net/forum?id=HylVB3AqYm) |  ICLR   | RL/G | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 |
| [Graph HyperNetworks for Neural Architecture Search](https://openreview.net/forum?id=rkgW0oA9FX) |  ICLR   |  G   |                    -                     | 2019 |
| [**SNAS: stochastic neural architecture search**](https://openreview.net/forum?id=rylqooRqK7) |  ICLR   |  G   | [github](https://github.com/SNAS-Series/SNAS-Series/tree/master/SNAS) | 2019 |
| [**FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search**](https://ieeexplore.ieee.org/document/8953587/) |  CVPR   |   G    | [github](https://github.com/facebookresearch/mobile-vision) | 2019 |
| [**Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation**](https://ieeexplore.ieee.org/document/8954247/) |  CVPR   |  G   | [gitHub](https://github.com/tensorflow/models/tree/master/research/deeplab) | 2019 |
| [AdversarialNAS: Adversarial Neural Architecture Search for GANs](https://ieeexplore.ieee.org/document/9157134/) |  CVPR   |  G   | [github](https://github.com/chengaopro/AdversarialNAS) | 2019 |
| [When NAS Meets Robustness: In Search of Robust Architectures against Adversarial Attacks](https://ieeexplore.ieee.org/document/9156305/) |  CVPR   |  G   | [github](https://github.com/gmh14/RobNets) | 2019 |
| [**Random Search and Reproducibility for Neural Architecture Search**](http://auai.org/uai2019/proceedings/papers/129.pdf) |   UAI   |  G   | [github](https://github.com/D-X-Y/NAS-Projects/blob/master/scripts-search/algos/RANDOM-NAS.sh) | 2019 |
| [One-Shot Neural Architecture Search via Self-Evaluated Template Network](https://openaccess.thecvf.com/content_ICCV_2019/html/Dong_One-Shot_Neural_Architecture_Search_via_Self-Evaluated_Template_Network_ICCV_2019_paper.html) |  ICCV   |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [Efficient Forward Architecture Search](https://papers.nips.cc/paper/9202-efficient-forward-architecture-search.html) | NeurIPS |  G   | [github](https://github.com/microsoft/petridishnn) | 2019 |
| [Improved Differentiable Architecture Search for Language Modeling and Named Entity Recognition](https://www.aclweb.org/anthology/D19-1367/) |  EMNLP  |  G   | [github](https://github.com/jiangyingjunn/i-darts) | 2019 |
| [Network Pruning via Transformable Architecture Search](https://arxiv.org/abs/1905.09717) | NeurIPS |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [XNAS: Neural Architecture Search with Expert Advice](https://papers.nips.cc/paper/8472-xnas-neural-architecture-search-with-expert-advice.html) | NeurIPS |  G   | [github](https://github.com/NivNayman/XNAS) | 2019 |
| [NetTailor: Tuning the Architecture, Not Just the Weights](https://ieeexplore.ieee.org/document/8953794) |  CVPR   |  G   | [github](https://github.com/pedro-morgado/nettailor) | 2019 |
| [**Searching for A Robust Neural Architecture in Four GPU Hours**](https://ieeexplore.ieee.org/document/8953848/) |  CVPR   |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [Progressive Differentiable Architecture Search: Bridging the Depth Gap Between Search and Evaluation](https://openaccess.thecvf.com/content_ICCV_2019/html/Chen_Progressive_Differentiable_Architecture_Search_Bridging_the_Depth_Gap_Between_Search_ICCV_2019_paper.html) |  ICCV   |  G   | [github](https://github.com/chenxin061/pdarts) | 2019 |
| [Customizable Architecture Search for Semantic Segmentation](https://ieeexplore.ieee.org/document/8953370) |  CVPR   |  G   |                    -                     | 2019 |
| [Auto-FPN: Automatic Network Architecture Adaptation for Object Detection Beyond Classification](https://openaccess.thecvf.com/content_ICCV_2019/html/Xu_Auto-FPN_Automatic_Network_Architecture_Adaptation_for_Object_Detection_Beyond_Classification_ICCV_2019_paper.html) |  ICCV  |    G    | - | 2019 |
| [Meta Architecture Search](https://papers.nips.cc/paper/9301-meta-architecture-search.html) |  NeurlPS  |    G    | [github](https://github.com/ashaw596/meta_architecture_search) | 2019 |
| [Efficient Neural Architecture Transformation Search in Channel-Level for Object Detection](https://papers.nips.cc/paper/9576-efficient-neural-architecture-transformation-search-in-channel-level-for-object-detection.html) |  NeurlPS  |    G    | - | 2019 |
| [DATA: Differentiable ArchiTecture Approximation](https://papers.nips.cc/paper/8374-data-differentiable-architecture-approximation.html) |  NeurlPS  |    G    | [github](https://github.com/XinbangZhang/DATA-NAS) | 2019 |
| [Adaptive Stochastic Natural Gradient Method for One-Shot Neural Architecture Search](http://proceedings.mlr.press/v97/akimoto19a.html) |  ICML  |    G    | [github](https://github.com/shirakawas/ASNG-NAS) | 2019 |
| [BayesNAS: A Bayesian Approach for Neural Architecture Search](http://proceedings.mlr.press/v97/zhou19e.html) |  ICML  |    G    | [github](https://github.com/BayesNAS) | 2019 |
| [MiLeNAS: Efficient Neural Architecture Search via Mixed-Level Reformulation](https://ieeexplore.ieee.org/document/9156336/) |  CVPR   |  G   | [github](https://github.com/chaoyanghe/MiLeNAS) | 2020 |
| [APQ: Joint Search for Network Architecture, Pruning and Quantization Policy](https://ieeexplore.ieee.org/document/9156411/) |  CVPR   |  G   | [github](https://github.com/mit-han-lab/apq) | 2020 |
| [SGAS: Sequential Greedy Architecture Search](https://ieeexplore.ieee.org/document/9157406/) |  CVPR   |  G   | [github](https://github.com/lightaime/sgas) | 2020 |
| [FBNetV2: Differentiable Neural Architecture Search for Spatial and Channel Dimensions](https://ieeexplore.ieee.org/document/9156431/) |  CVPR   |  G   | [github](https://github.com/facebookresearch/mobile-vision) | 2020 |
| [Block-wisely Supervised Neural Architecture Search with Knowledge Distillation](https://ieeexplore.ieee.org/document/9157026/) |  CVPR   |  G   | [github](https://github.com/changlin31/DNA) | 2020 |
| [Overcoming Multi-Model Forgetting in One-Shot NAS with Diversity Maximization](https://ieeexplore.ieee.org/document/9156768/) |  CVPR   |  G   | [github](https://github.com/MiaoZhang0525/NSAS_FOR_CVPR) | 2020 |
| [Densely Connected Search Space for More Flexible Neural Architecture Search](https://ieeexplore.ieee.org/document/9156957/) |  CVPR   |  G   | [github](https://github.com/JaminFong/DenseNAS) | 2020 |
| [Understanding Architectures Learnt by Cell-based Neural Architecture Search](https://openreview.net/forum?id=BJxH22EKPS) |  ICLR   |  G   | [github](https://github.com/shuyao95/Understanding-NAS) | 2020 |
| [**PC-DARTS: Partial Channel Connections for Memory-Efficient Architecture Search**](https://openreview.net/forum?id=BJlS634tPr&noteId=BJlS634tPr) |  ICLR   |  G   | [github](https://github.com/yuhuixu1993/PC-DARTS) | 2020 |
| [FasterSeg: Searching for Faster Real-time Semantic Segmentation](https://openreview.net/forum?id=BJgqQ6NYvB) |  ICLR   |  G   | [github](https://github.com/TAMU-VITA/FasterSeg) | 2020 |
| [**AtomNAS: Fine-Grained End-to-End Neural Architecture Search**](https://openreview.net/forum?id=BylQSxHFwr) |  ICLR   |  G   | [github](https://github.com/meijieru/AtomNAS) | 2020 |
| [Fast Neural Network Adaptation via Parameter Remapping and Architecture Search](https://openreview.net/forum?id=rklTmyBKPH) |  ICLR   |  G   | [github](https://github.com/JaminFong/FNA) | 2020 |
| [Learning Architectures from an Extended Search Space for Language Modeling](https://arxiv.org/abs/2005.02593v1) |   ACL   |  G   |                    -                     | 2020 |
| [Are Labels Necessary for Neural Architecture Search?](https://arxiv.org/abs/2003.12056) |  ECCV  |    G    | [github](https://github.com/facebookresearch/unnas) | 2020 |
| [BATS: Binary ArchitecTure Search](https://arxiv.org/abs/2003.01711) |  ECCV  |    G    | - | 2020 |
| [Stabilizing Differentiable Architecture Search via Perturbation-based Regularization](https://arxiv.org/abs/2002.05283) |  ICML  |    G    | [github](https://github.com/xiangning-chen/SmoothDARTS) | 2020 |
| [Memory-Efficient Hierarchical Neural Architecture Search for Image Denoising](https://ieeexplore.ieee.org/document/9156867/) |  CVPR  |    G    | - | 2020 |
| [All in One Bad Weather Removal Using Architectural Search](https://ieeexplore.ieee.org/document/9157460/) |  CVPR  |    G    | - | 2020 |
| [Organ at Risk Segmentation for Head and Neck Cancer Using Stratified Learning and Neural Architecture Search](https://ieeexplore.ieee.org/document/9156960/) |  CVPR  |    G    | - | 2020 |
| [Neural Architecture Search for Lightweight Non-Local Networks](https://ieeexplore.ieee.org/document/9157189/) |  CVPR  |    G    | [github](https://github.com/LiYingwei/AutoNL) | 2020 |
| [UNAS: Differentiable Architecture Search Meets Reinforcement Learning](https://ieeexplore.ieee.org/document/9156297/) |  CVPR  |    G/RL    | - | 2020 |
| [MTL-NAS: Task-Agnostic Neural Architecture Search Towards General-Purpose Multi-Task Learning](https://ieeexplore.ieee.org/document/9157640/) |  CVPR  |    G    | [github](https://github.com/bhpfelix/MTLNAS) | 2020 |
| [Hit-Detector: Hierarchical Trinity Architecture Search for Object Detection](https://ieeexplore.ieee.org/document/9156291) |  CVPR  |    G    | [github](https://github.com/ggjy/HitDet.pytorch) | 2020 |
| [DSNAS: Direct Neural Architecture Search Without Parameter Retraining](https://ieeexplore.ieee.org/document/9157467/) |  CVPR  |    G    | [github](https://github.com/SNAS-Series/SNAS-Series/) | 2020 |
| [Meta-Learning of Neural Architectures for Few-Shot Learning](https://ieeexplore.ieee.org/document/9157641) |  CVPR  |    G    | - | 2020 |
| [**Understanding and Robustifying Differentiable Architecture Search**](https://openreview.net/forum?id=H1gDNyrKDS) |  ICLR  |    G    | [github](https://github.com/automl/RobustDARTS) | 2020 |
| [CP-NAS: Child-Parent Neural Architecture Search for 1-bit CNNs](https://www.ijcai.org/Proceedings/2020/0144) |  IJCAI  |    G    | - | 2020 |
| [DropNAS: Grouped Operation Dropout for Differentiable Architecture Search](https://www.ijcai.org/Proceedings/2020/0322) |  IJCAI  |    G    | [github](https://github.com/huawei-noah) | 2020 |
| [MergeNAS: Merge Operations into One for Differentiable Architecture Search](https://www.ijcai.org/Proceedings/2020/0424) |  IJCAI  |    G    | - | 2020 |
| [SI-VDNAS: Semi-Implicit Variational Dropout for Hierarchical One-shot Neural Architecture Search](https://www.ijcai.org/Proceedings/2020/0289) |  IJCAI  |    G    | - | 2020 |
| [M-NAS: Meta Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/6084) |  AAAI  |    G    | - | 2020 |
| [Posterior-Guided Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/6181) |  AAAI  |    G    | [github](https://github.com/scenarios/PGNAS) | 2020 |
| [Binarized Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/6624) |  AAAI  |    G    | - | 2020 |
| [Neural Graph Embedding for Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/5903) |  AAAI  |    G    | - | 2020 |
| [Efficient Neural Architecture Search via Proximal Iterations](https://aaai.org/ojs/index.php/AAAI/article/view/6143) |  AAAI  |    G    | [github](https://github.com/xujinfan/NASP-codes) | 2020 |



### Evolutionary Algorithms - EA
| Title                                    | Venue | Type  |                   Code                   | Year |
| :--------------------------------------- | :---: | :---: | :--------------------------------------: | :--: |
| [**Large-Scale Evolution of Image Classifiers**](http://proceedings.mlr.press/v70/real17a.html) | ICML  |  EA   |                    -                     | 2017 |
| [Genetic CNN](https://openaccess.thecvf.com/content_ICCV_2017/html/Xie_Genetic_CNN_ICCV_2017_paper.html) |  ICCV   |    EA     | [*github*](https://github.com/aqibsaeed/Genetic-CNN) | 2017 |
| [Hierarchical Representations for Efficient Architecture Search](https://openreview.net/forum?id=BJQRKzbA-) | ICLR  |  EA   |                    -                     | 2018 |
| [**Regularized Evolution for Image Classifier Architecture Search**](https://aaai.org/ojs/index.php/AAAI/article/view/4405) | AAAI  |  EA   |                    -                     | 2018 |
| [A Genetic Programming Approach to Designing Convolutional Neural Network Architectures](https://www.ijcai.org/Proceedings/2018/0755) |  IJCAI  |    EA    | [github](https://github.com/sg-nm/cgp-cnn) | 2018 |
| [Simple And Efficient Architecture Search for Convolutional Neural Networks](https://openreview.net/forum?id=H1hymrkDf) |  ICLR   |     EA    | - | 2018 |
| [RENAS: Reinforced Evolutionary Neural Architecture Search](https://ieeexplore.ieee.org/document/8953426/) | CVPR  | EA/RL | [github](https://github.com/yukang2017/RENAS) | 2019 |
| [**Efficient Multi-Objective Neural Architecture Search via Lamarckian Evolution**](https://openreview.net/forum?id=ByME42AqK7) | ICLR  |  EA   |                    -                     | 2019 |
| [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://ieeexplore.ieee.org/document/8953899/) | CVPR  |  EA   | [github](https://github.com/lixincn2015/Partial-Order-Pruning) | 2019 |
| [MFAS: Multimodal Fusion Architecture Search](https://ieeexplore.ieee.org/document/8954353) | CVPR  |  EA   |                    -                     | 2019 |
| [Resource Constrained Neural Network Architecture Search: Will a Submodularity Assumption Help?](https://openaccess.thecvf.com/content_ICCV_2019/html/Xiong_Resource_Constrained_Neural_Network_Architecture_Search_Will_a_Submodularity_Assumption_ICCV_2019_paper.html) | ICCV  |  EA   | [github](https://github.com/yyxiongzju/RCNet) | 2019 |
| [Evolving Space-Time Neural Architectures for Videos](https://openaccess.thecvf.com/content_ICCV_2019/html/Piergiovanni_Evolving_Space-Time_Neural_Architectures_for_Videos_ICCV_2019_paper.html) | ICCV  |  EA   | [github](https://github.com/google-research/google-research/tree/master/evanet) | 2019 |
| [DetNAS: Backbone Search for Object Detection](https://papers.nips.cc/paper/8890-detnas-backbone-search-for-object-detection.html) |  NeurlPS   |    EA     | [github](https://github.com/megvii-model/DetNAS) | 2019 |
| [CARS: Continuous Evolution for Efficient Neural Architecture Search](https://ieeexplore.ieee.org/document/9156384/) |  CVPR   |    EA     | [github](https://github.com/huawei-noah/CARS) | 2020 |
| [GreedyNAS: Towards Fast One-Shot NAS With Greedy Supernet](https://ieeexplore.ieee.org/document/9156924/) |  CVPR   |    EA     | - | 2020 |
| [MemNAS: Memory-Efficient Neural Architecture Search With Grow-Trim Learning](https://ieeexplore.ieee.org/document/9156558/) |  CVPR   |    EA     | - | 2020 |
| [C2FNAS: Coarse-to-Fine Neural Architecture Search for 3D Medical Image Segmentation](https://ieeexplore.ieee.org/document/9156654/) |  CVPR   |    EA     | - | 2020 |
| [EcoNAS: Finding Proxies for Economical Neural Architecture Search](https://ieeexplore.ieee.org/document/9157571/) |  CVPR   |    EA     | - | 2020 |
| [Improving One-Shot NAS by Suppressing the Posterior Fading](https://ieeexplore.ieee.org/document/9156314/) |  CVPR   |    EA     | - | 2020 |
| [AssembleNet: Searching for Multi-Stream Neural Connectivity in Video Architectures](https://openreview.net/forum?id=SJgMK64Ywr) |  ICLR   |    EA    | - | 2020 |
| [One-Shot Neural Architecture Search via Novelty Driven Sampling](https://www.ijcai.org/Proceedings/2020/0441) |  IJCAI  |    EA    | [github](https://github.com/MiaoZhang0525/ENNAS_MASTER) | 2020 |
| [SM-NAS: Structural-to-Modular Neural Architecture Search for Object Detection](https://aaai.org/ojs/index.php/AAAI/article/view/6958) |  AAAI  |    EA    | - | 2020 |
| [Ultrafast Photorealistic Style Transfer via Neural Architecture Search](https://aaai.org/ojs/index.php/AAAI/article/view/6614) |  AAAI  |    EA    | [github](https://github.com/Richard-An/StyleNAS) | 2020 |



### Performance Prediction - PD
| Title                                    | Venue  | Type  |                   Code                   | Year |
| :--------------------------------------- | :----: | :---: | :--------------------------------------: | :--: |
| [Learning Curve Prediction with Bayesian Neural Networks](https://openreview.net/forum?id=S11KBYclx) |  ICLR  |  PD   |                    -                     | 2017 |
| [**Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization**](https://arxiv.org/abs/1603.06560) |  ICLR  |  PD   |                    -                     | 2017 |
| [Accelerating Neural Architecture Search using Performance Prediction](https://openreview.net/forum?id=HJqk3N1vG) | ICLR-W |  PD   | [github](https://github.com/MITAutoML/accelerating_nas) | 2018 |
| [**Progressive Neural Architecture Search**](https://openaccess.thecvf.com/content_ECCV_2018/html/Chenxi_Liu_Progressive_Neural_Architecture_ECCV_2018_paper.html) |  ECCV  |  PD   | [github](https://github.com/chenxi116/PNASNet.pytorch) | 2018 |
| [A Flexible Approach to Automated RNN Architecture Generation](https://openreview.net/forum?id=SkOb1Fl0Z) |  ICLR  | RL/PD |                    -                     | 2018 |
| [Multinomial Distribution Learning for Effective Neural Architecture Search](https://openaccess.thecvf.com/content_ICCV_2019/html/Zheng_Multinomial_Distribution_Learning_for_Effective_Neural_Architecture_Search_ICCV_2019_paper.html) |  ICCV  |  PD   | [github](https://github.com/tanglang96/MDENAS) | 2019 |
| [Learnable Embedding Space for Efficient Neural Architecture Compression](https://openreview.net/forum?id=S1xLN3C9YX) |  ICLR  |  PD   | [github](https://github.com/Friedrich1006/ESNAC) | 2019 |
| [TAPAS: Train-less Accuracy Predictor for Architecture Search](https://doi.org/10.1609/aaai.v33i01.33013927) |  AAAI   |    PD     | - | 2019 |
| [Generative Teaching Networks: Accelerating Neural Architecture Search by Learning to Generate Synthetic Training Data](https://arxiv.org/abs/1912.07768) |  ICML  |  PD   |                    -                     | 2020 |
| [Neural Architecture Search in a Proxy Validation Loss Landscape](https://proceedings.icml.cc/static/paper_files/icml/2020/439-Paper.pdf) |  ICML  |  PD   |                    -                     | 2020 |
| [Rethinking Performance Estimation in Neural Architecture Search](https://ieeexplore.ieee.org/document/9156290/) |  CVPR  |  PD   | [github](https://github.com/CVPR2020-ID1073/Rethinking-Performance-Estimation-in-Neural-Architecture-Search) | 2020 |
| [A Semi-Supervised Assessor of Neural Architectures](https://ieeexplore.ieee.org/document/9157156) |  CVPR   |    PD     | - | 2020 |
| [GP-NAS: Gaussian Process Based Neural Architecture Search](https://ieeexplore.ieee.org/document/9157633/) |  CVPR   |    PD     | - | 2020 |



### Others - O
| Title                                    |   Venue   |     Type     |                   Code                   | Year |
| :--------------------------------------- | :-------: | :----------: | :--------------------------------------: | :--: |
| [Hyperparameter Optimization: A Spectral Approach](https://arxiv.org/abs/1706.00764) | NeurIPS-W |    O     | [github](https://github.com/callowbird/Harmonica) | 2017 |
| [Searching for efficient multi-scale architectures for dense image prediction](http://papers.nips.cc/paper/8087-searching-for-efficient-multi-scale-architectures-for-dense-image-prediction) |  NeurIPS  |    O     |                    -                     | 2018 |
| [Neural Architecture Search with Bayesian Optimisation and Optimal Transport](https://papers.nips.cc/paper/7472-neural-architecture-search-with-bayesian-optimisation-and-optimal-transport.html) |  NeurIPS  |    O     | [github](https://github.com/kirthevasank/nasbot) | 2018 |
| [PPP-Net: Platform-aware Progressive Search for Pareto-optimal Neural Architectures](https://openreview.net/forum?id=B1NT3TAIM) |  ICLR  |     O    | - | 2018 |
| [DeepArchitect: Automatically Designing and Training Deep Architectures](https://openreview.net/forum?id=rkTBjG-AZ) |  ICLR  |     O    | [github](https://github.com/negrinho/deep_architect_legacy) | 2018 |
| [Fast and Practical Neural Architecture Search](https://openaccess.thecvf.com/content_ICCV_2019/html/Cui_Fast_and_Practical_Neural_Architecture_Search_ICCV_2019_paper.html) |   ICCV    |    O     | [*github*](https://github.com/FPNAS/FPNASNet) | 2019 |
| [Teacher Guided Architecture Search](https://openaccess.thecvf.com/content_ICCV_2019/html/Bashivan_Teacher_Guided_Architecture_Search_ICCV_2019_paper.html) |   ICCV    |    O     |                    -                     | 2019 |
| [Towards modular and programmable architecture search](https://papers.nips.cc/paper/9524-towards-modular-and-programmable-architecture-search.html) |  NeurIPS  |    O     | [github](https://github.com/negrinho/deep_architect) | 2019 |
| [Deep Active Learning with a Neural Architecture Search](https://papers.nips.cc/paper/8831-deep-active-learning-with-a-neural-architecture-search.html) |  NeurIPS  |    O     | [github](https://github.com/geifmany/Active-inas) | 2019 |
| [NAS-Bench-101: Towards Reproducible Neural Architecture Search](http://proceedings.mlr.press/v97/ying19a.html) |   ICML    |    O     | [github](https://github.com/google-research/nasbench) | 2019 |
| [**Searching for MobileNetV3**](https://openaccess.thecvf.com/content_ICCV_2019/html/Howard_Searching_for_MobileNetV3_ICCV_2019_paper.html) |  ICCV   |     O    | [*github*](https://github.com/leaderj1001/MobileNetV3-Pytorch) | 2019 |
| [Auto-ReID: Searching for a Part-Aware ConvNet for Person Re-Identification](https://openaccess.thecvf.com/content_ICCV_2019/html/Quan_Auto-ReID_Searching_for_a_Part-Aware_ConvNet_for_Person_Re-Identification_ICCV_2019_paper.html) |  ICCV   |     O    | - | 2019 |
| [**Exploring Randomly Wired Neural Networks for Image Recognition**](https://openaccess.thecvf.com/content_ICCV_2019/html/Xie_Exploring_Randomly_Wired_Neural_Networks_for_Image_Recognition_ICCV_2019_paper.html) |  ICCV   |     O    | [*github*](https://github.com/seungwonpark/RandWireNN) | 2019 |
| [SpArSe: Sparse Architecture Search for CNNs on Resource-Constrained Microcontrollers](https://papers.nips.cc/paper/8743-sparse-sparse-architecture-search-for-cnns-on-resource-constrained-microcontrollers.html) |  NeurlPS   |     O    | - | 2019 |
| [Constrained deep neural network architecture search for IoT devices accounting for hardware calibration](https://papers.nips.cc/paper/8838-constrained-deep-neural-network-architecture-search-for-iot-devices-accounting-for-hardware-calibration.html) |  NeurlPS   |     O    | - | 2019 |
| [Angle-based Search Space Shrinking for Neural Architecture Search](https://arxiv.org/abs/2004.13431) |  ECCV   |     O    | - | 2020 |
| [AutoSTR: Efficient Backbone Search for Scene Text Recognition](https://arxiv.org/abs/2003.06567) |  ECCV   |     O    | [github](https://github.com/AutoML-4Paradigm/AutoSTR) | 2020 |
| [GroSS: Group-Size Series Decomposition for Grouped Architecture Search](https://arxiv.org/abs/1912.00673) |  ECCV   |     O    | - | 2020 |
| [DA-NAS: Data Adapted Pruning for Efficient Neural Architecture Search](https://arxiv.org/abs/2003.12563) |  ECCV   |     O    | - | 2020 |
| [Neural Predictor for Neural Architecture Search](https://arxiv.org/abs/1912.00848) |   ECCV  |     O    | - | 2020 |
| [Learning to Rank Learning Curves](https://arxiv.org/abs/2006.03361) |  ICML   |     O    | - | 2020 |
| [AOWS: Adaptive and Optimal Network Width Search With Latency Constraints](https://ieeexplore.ieee.org/document/9156666) |  CVPR   |     O    | [github](https://github.com/bermanmaxim/AOWS) | 2020 |
| [**NAS-Bench-1Shot1: Benchmarking and Dissecting One-shot Neural Architecture Search**](https://openreview.net/forum?id=SJx9ngStPH) |  ICLR   |     O    | [github](https://github.com/automl/nasbench-1shot1) | 2020 |
| [How to 0wn the NAS in Your Spare Time](https://openreview.net/forum?id=S1erpeBFPB) |  ICLR  |     O    | [github](https://github.com/Sanghyun-Hong/How-to-0wn-NAS-in-Your-Spare-Time) | 2020 |
| [Neural Epitome Search for Architecture-Agnostic Network Compression](https://openreview.net/forum?id=HyxjOyrKvr) |  ICLR   |     O    | [github](https://github.com/zhoudaquan/NES) | 2020 |
| [AdaBERT: Task-Adaptive BERT Compression with Differentiable Neural Architecture Search](https://www.ijcai.org/Proceedings/2020/0341) |  IJCAI  |     O    | - | 2020 |
| [AutoShrink: A Topology-aware NAS for Discovering Efficient Neural Architecture](https://aaai.org/ojs/index.php/AAAI/article/view/6163) |  AAAI   |     O    | [github](https://github.com/lordzth666/AutoShrink) | 2020 |
| [TextNAS: A Neural Architecture Search Space tailored for Text Representation](https://aaai.org/ojs/index.php/AAAI/article/view/6462) |   AAAI  |     O    | [github](https://github.com/microsoft/nni/tree/master/examples/nas/textnas) | 2020 |
| [Neural Architecture Search using Deep Neural Networks and Monte Carlo Tree Search](https://aaai.org/ojs/index.php/AAAI/article/view/6554) |  AAAI   |     O    | [github](https://github.com/linnanwang/AlphaX-NASBench101) | 2020 |
| [NADS: Neural Architecture Distribution Search for Uncertainty Awareness](https://arxiv.org/abs/2006.06646) |   ICML    |    O     |                    -                     | 2020 |
| [**NAS-BENCH-201: Extending the Scope of Reproducible Neural Architecture Search**](https://openreview.net/forum?id=HJxyZkBKDr) |   ICLR    |    O     | [github](https://github.com/D-X-Y/AutoDL-Projects) | 2020 |
| [**Evaluating The Search Phase of Neural Architecture Search**](https://openreview.net/forum?id=H1loF2NFwr) |   ICLR    | O/S | [github](https://github.com/kcyu2014/eval-nas) | 2020 |
| [**NAS evaluation is frustratingly hard**](https://openreview.net/forum?id=HygrdpVKvr) |   ICLR    | O/S | [github](https://github.com/antoyang/NAS-Benchmark) | 2020 |
| [Towards Fast Adaptation of Neural Architectures with Meta Learning](https://openreview.net/forum?id=r1eowANFvr) |   ICLR    |    O     | [github](https://github.com/dongzelian/T-NAS) | 2020 |
| [How to Own the NAS in Your Spare Time](https://openreview.net/forum?id=S1erpeBFPB) |   ICLR    |    O     | [github](https://github.com/Sanghyun-Hong/How-to-0wn-NAS-in-Your-Spare-Time) | 2020 |

### Random Search


### Bayesian Optimization


### Search Space



### High Citation Papers
| Title                                    |  Venue  |  Type  |                   Code                   | Year | Citations |
| :--------------------------------------- | :-----: | :----: | :--------------------------------------: | :--: | :-------: |
| [**Neural Architecture Search with Reinforcement Learning**](https://openreview.net/forum?id=r1Ue8Hcxg) |  ICLR   |    RL     |                    -                     | 2017 | 1876 |
| [**Learning Transferable Architectures for Scalable Image Recognition**](https://ieeexplore.ieee.org/document/8579005) |  CVPR   |    RL     | [github](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet) | 2018 | 1830 |
| [**DARTS: Differentiable Architecture Search**](https://openreview.net/forum?id=S1eYHoC5FX) |  ICLR   |  G   | [github](https://github.com/quark0/darts) | 2018 | 856 |
| [**Efficient Neural Architecture Search via Parameter Sharing**](http://proceedings.mlr.press/v80/pham18a.html) |  ICML   |    RL     | [github](https://github.com/carpedm20/ENAS-pytorch) | 2018 | 825 |
| [**Regularized Evolution for Image Classifier Architecture Search**](https://aaai.org/ojs/index.php/AAAI/article/view/4405) | AAAI  |  EA   |                    -                     | 2018 | 753 |
| [**Progressive Neural Architecture Search**](https://openaccess.thecvf.com/content_ECCV_2018/html/Chenxi_Liu_Progressive_Neural_Architecture_ECCV_2018_paper.html) |  ECCV  |  PD   | [github](https://github.com/chenxi116/PNASNet.pytorch) | 2018 | 708 |
| [**Large-Scale Evolution of Image Classifiers**](http://proceedings.mlr.press/v70/real17a.html) | ICML  |  EA   |                    -                     | 2017 | 697 |
| [**Designing Neural Network Architectures using Reinforcement Learning**](https://openreview.net/forum?id=S1c2cvqee) |  ICLR   |    RL     | [github](https://github.com/bowenbaker/metaqnn) | 2017 | 618 |
| [**MnasNet: Platform-Aware Neural Architecture Search for Mobile**](https://ieeexplore.ieee.org/document/8954198/) |  CVPR   |   RL   | [github](https://github.com/AnjieZheng/MnasNet-PyTorch) | 2018 | 578 |
| [**Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization**](https://arxiv.org/abs/1603.06560) |  ICLR  |  PD   |                    -                     | 2017 | 537 |
| [**ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware**](https://openreview.net/forum?id=HylVB3AqYm) |  ICLR   |   RL/G    | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 | 450 |
| [**Searching for MobileNetV3**](https://openaccess.thecvf.com/content_ICCV_2019/html/Howard_Searching_for_MobileNetV3_ICCV_2019_paper.html) |  ICCV   |     O    | [*github*](https://github.com/leaderj1001/MobileNetV3-Pytorch) | 2019 | 308 |
| [**Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation**](https://ieeexplore.ieee.org/document/8954247/) |  CVPR   |  G   | [gitHub](https://github.com/tensorflow/models/tree/master/research/deeplab) | 2019 | 277 |
| [**FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search**](https://ieeexplore.ieee.org/document/8953587/) |  CVPR   |   G    | [github](https://github.com/facebookresearch/mobile-vision) | 2019 | 276 |
| [**SNAS: stochastic neural architecture search**](https://openreview.net/forum?id=rylqooRqK7) |  ICLR   |  G   | [github](https://github.com/SNAS-Series/SNAS-Series/tree/master/SNAS) | 2019 | 253 |
| [**Random Search and Reproducibility for Neural Architecture Search**](http://auai.org/uai2019/proceedings/papers/129.pdf) |   UAI   |  G   | [github](https://github.com/D-X-Y/NAS-Projects/blob/master/scripts-search/algos/RANDOM-NAS.sh) | 2019 | 160 |
| [**Efficient Multi-Objective Neural Architecture Search via Lamarckian Evolution**](https://openreview.net/forum?id=ByME42AqK7) | ICLR  |  EA   |                    -                     | 2019 | 120 |
| [**Exploring Randomly Wired Neural Networks for Image Recognition**](https://openaccess.thecvf.com/content_ICCV_2019/html/Xie_Exploring_Randomly_Wired_Neural_Networks_for_Image_Recognition_ICCV_2019_paper.html) |  ICCV   |     O    | [*github*](https://github.com/seungwonpark/RandWireNN) | 2019 | 120 |
| [**Searching for A Robust Neural Architecture in Four GPU Hours**](https://ieeexplore.ieee.org/document/8953848/) |  CVPR   |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 | 105 |
| [**Evaluating The Search Phase of Neural Architecture Search**](https://openreview.net/forum?id=H1loF2NFwr) |   ICLR    | O/S | [github](https://github.com/kcyu2014/eval-nas) | 2020 | 92 |
| [**PC-DARTS: Partial Channel Connections for Memory-Efficient Architecture Search**](https://openreview.net/forum?id=BJlS634tPr&noteId=BJlS634tPr) |  ICLR   |  G   | [github](https://github.com/yuhuixu1993/PC-DARTS) | 2020 | 52 |
| [**NAS-BENCH-201: Extending the Scope of Reproducible Neural Architecture Search**](https://openreview.net/forum?id=HJxyZkBKDr) |   ICLR    |    O     | [github](https://github.com/D-X-Y/AutoDL-Projects) | 2020 | 46 |
| [**Understanding and Robustifying Differentiable Architecture Search**](https://openreview.net/forum?id=H1gDNyrKDS) |  ICLR  |    G    | [github](https://github.com/automl/RobustDARTS) | 2020 | 32 |
| [**NAS evaluation is frustratingly hard**](https://openreview.net/forum?id=HygrdpVKvr) | ICLR  | O/S | [github](https://github.com/antoyang/NAS-Benchmark) | 2020 | 24 |
| [**NAS-Bench-1Shot1: Benchmarking and Dissecting One-shot Neural Architecture Search**](https://openreview.net/forum?id=SJx9ngStPH) |  ICLR   |     O    | [github](https://github.com/automl/nasbench-1shot1) | 2020 | 20 |
| [**AtomNAS: Fine-Grained End-to-End Neural Architecture Search**](https://openreview.net/forum?id=BylQSxHFwr) |  ICLR   |  G   | [github](https://github.com/meijieru/AtomNAS) | 2020 | 20 |



## Systems

| Title                                    | Venue  |  Type  |                   Code                   | Year |
| :--------------------------------------- | :----: | :----: | :--------------------------------------: | :--: |
| [Auto-Keras: An Efficient Neural Architecture Search System](https://arxiv.org/abs/1806.10282) |   -    | System | [github](https://github.com/keras-team/autokeras) | 2018 |
| [Neural Network Intelligence](https://nni.readthedocs.io/en/latest/) |   -    | System | [github](https://github.com/microsoft/nni) |  -   |
| [AdaNet: A Scalable and Flexible Framework for Automatically Learning Ensembles](https://arxiv.org/abs/1905.00080) | ICML-W | System | [github](https://github.com/tensorflow/adanet) | 2019 |



## Team Members

The project is maintained by

*Yongyu Mu, Zefan Zhou, Zhongxiang Yan, Chi Hu, Yinqiao Li, Tong Xiao, and Jingbo Zhu*

*Natural Language Processing Lab., School of Computer Science and Engineering, Northeastern University*

*NiuTrans Research*

For any questions, please feel free to contact us (heshengmo [at] foxmail [dot] com or li.yin.qiao.2012 [at] hotmail [dot] com).

