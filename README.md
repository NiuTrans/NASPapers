- [Neural Architecture Search](#NAS)
  - [Paper](#The Paper List)
    - [Surveys](#Surveys)
    - [Reinforcement Learning](#Reinforcement-Learning---RL)
    - [Gradient-based-methods---g](#Gradient-based Methods)
    - [Evaluationary-algorithms---ea](#Evaluationary Algorithms)
    - [Performance-prediction---pd](#Performance Prediction)
    - [Others](#Others)
    - [High-citation-papers](#High Citation Papers (> 100 citations))
  - [Systems](#Systems)

*Data from [Bing](https://cn.bing.com/academic/)*
*Updated August 13*
*The papers in bold are cited more in the same year*



## Paper List

### Surveys
| Title                                    | Venue |     Type     |                   Code                   | Year |
| :--------------------------------------- | :---: | :----------: | :--------------------------------------: | :--: |
| [**Neural architecture search: A survey**](http://www.jmlr.org/papers/volume20/18-598/18-598.pdf) | JMLR  |    Survey    |                    -                     | 2018 |
| [A Survey on Neural Architecture Search](https://arxiv.org/abs/1905.01392) |   -   |    Survey    |                    -                     | 2019 |
| [A Comprehensive Survey of Neural Architecture Search: Challenges and Solutions](https://arxiv.org/abs/2006.02903) |   -   |    Survey    |                    -                     | 2020 |
| [Reinforcement Learning for Neural Architecture Search: A Review](https://www.sciencedirect.com/science/article/abs/pii/S0262885619300885) |  SCI  |  RL/Survey   |                    -                     | 2019 |
| [**Evaluating The Search Phase of Neural Architecture Search**](https://openreview.net/forum?id=H1loF2NFwr) | ICLR  | Other/Survey |                    -                     | 2020 |
| [NAS evaluation is frustratingly hard](https://arxiv.org/abs/1912.12522) | ICLR  | Other/Survey | [github](https://github.com/antoyang/NAS-Benchmark) | 2020 |



### Reinforcement Learning - RL
| Title                                    |  Venue  |   Type    |                   Code                   | Year |
| :--------------------------------------- | :-----: | :-------: | :--------------------------------------: | :--: |
| [**Neural Architecture Search with Reinforcement Learning**](https://arxiv.org/abs/1611.01578) |  ICLR   |    RL     |                    -                     | 2017 |
| [**Efficient Neural Architecture Search via Parameter Sharing**](http://proceedings.mlr.press/v80/pham18a.html) |  ICML   |    RL     | [github](https://github.com/carpedm20/ENAS-pytorch) | 2018 |
| [**Designing Neural Network Architectures using Reinforcement Learning**](https://openreview.net/pdf?id=S1c2cvqee) |  ICLR   |    RL     | [github](https://github.com/bowenbaker/metaqnn) | 2017 |
| [Neural Optimizer Search with Reinforcement Learning](http://proceedings.mlr.press/v70/bello17a/bello17a.pdf) |  ICML   |    RL     |                    -                     | 2017 |
| [Efficient Architecture Search by Network Transformation](https://arxiv.org/pdf/1707.04873.pdf) |  AAAI   |    RL     | [github](https://github.com/han-cai/EAS) | 2018 |
| [Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells](https://arxiv.org/abs/1810.10804) |  CVPR   |    RL     |                    -                     | 2019 |
| [**Learning Transferable Architectures for Scalable Image Recognition**](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.pdf) |  CVPR   |    RL     | [github](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet) | 2018 |
| [N2N learning: Network to Network Compression via Policy Gradient Reinforcement Learning](https://openreview.net/forum?id=B1hcZZ-AW) |  ICLR   |    RL     |                    -                     | 2017 |
| [Practical Block-wise Neural Network Architecture Generation](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhong_Practical_Block-Wise_Neural_CVPR_2018_paper.pdf) |  CVPR   |    RL     |                    -                     | 2018 |
| [Path-Level Network Transformation for Efficient Architecture Search](https://arxiv.org/abs/1806.02639) |  ICML   |    RL     | [github](https://github.com/han-cai/PathLevel-EAS) | 2018 |
| [**MnasNet: Platform-Aware Neural Architecture Search for Mobile**](https://arxiv.org/abs/1807.11626) |  CVPR   |    RL     | [github](https://github.com/AnjieZheng/MnasNet-PyTorch) | 2018 |
| [Reinforcement Learning for Neural Architecture Search: A Review](https://www.sciencedirect.com/science/article/abs/pii/S0262885619300885) |   SCI   | RL/Survey |                    -                     | 2019 |
| [Can Weight Sharing Outperform Random Architecture Search? An Investigation With TuNAS](http://openaccess.thecvf.com/content_CVPR_2020/papers/Bender_Can_Weight_Sharing_Outperform_Random_Architecture_Search_An_Investigation_With_CVPR_2020_paper.pdf) |  CVPR   |    RL     |                    -                     | 2019 |
| [Continual and Multi-Task Architecture Search](https://www.aclweb.org/anthology/P19-1185.pdf) |   ACL   |    RL     |                    -                     | 2019 |
| [AutoGAN: Neural Architecture Search for Generative Adversarial Networks](https://arxiv.org/pdf/1908.03835.pdf) |  ICCV   |    RL     | [github](https://github.com/TAMU-VITA/AutoGAN) | 2019 |
| [**ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware**](https://openreview.net/pdf?id=HylVB3AqYm) |  ICLR   |   RL/G    | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 |
| [A Flexible Approach to Automated RNN Architecture Generation](https://openreview.net/forum?id=SkOb1Fl0Z) |  ICLR   |   RL/PD   |                    -                     | 2018 |
| [Learning to Compose Domain-Specific Transformations for Data Augmentation](http://papers.nips.cc/paper/6916-learning-to-compose-domain-specific-transformations-for-data-augmentation) | NeurIPS |    RL     |                    -                     | 2017 |
| [RENAS: Reinforced Evolutionary Neural Architecture Search](https://arxiv.org/abs/1808.00193) |  CVPR   |   EA/RL   |                    -                     | 2019 |



### Gradient-based Methods - G
| Title                                    |  Venue  | Type |                   Code                   | Year |
| :--------------------------------------- | :-----: | :--: | :--------------------------------------: | :--: |
| [**DARTS: Differentiable Architecture Search**](https://arxiv.org/abs/1806.09055) |  ICLR   |  G   | [github](https://github.com/quark0/darts) | 2018 |
| [**ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware**](https://openreview.net/pdf?id=HylVB3AqYm) |  ICLR   | RL/G | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 |
| [Graph HyperNetworks for Neural Architecture Search](https://arxiv.org/pdf/1810.05749.pdf) |  ICLR   |  G   |                    -                     | 2019 |
| [SNAS: stochastic neural architecture search](https://openreview.net/pdf?id=rylqooRqK7) |  ICLR   |  G   |                    -                     | 2019 |
| [**FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search**](https://arxiv.org/abs/1812.03443) |  CVPR   |  G   |                    -                     | 2019 |
| [Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation](https://arxiv.org/pdf/1901.02985.pdf) |  CVPR   |  G   | [gitHub](https://github.com/tensorflow/models/tree/master/research/deeplab) | 2019 |
| [**Understanding and Simplifying One-Shot Architecture Search**](http://proceedings.mlr.press/v80/bender18a/bender18a.pdf) |  ICML   |  G   |                    -                     | 2018 |
| [**SMASH: One-Shot Model Architecture Search through HyperNetworks**](https://arxiv.org/pdf/1708.05344.pdf) |  ICLR   |  G   | [github](https://github.com/ajbrock/SMASH) | 2018 |
| [**Neural Architecture Optimization**](https://arxiv.org/pdf/1808.07233.pdf) | NeurIPS |  G   | [github](https://github.com/renqianluo/NAO) | 2018 |
| [Differentiable Neural Network Architecture Search](https://openreview.net/pdf?id=BJ-MRKkwG) | ICLR-W  |  G   |                    -                     | 2018 |
| [MiLeNAS: Efficient Neural Architecture Search via Mixed-Level Reformulation](https://arxiv.org/pdf/2003.12238.pdf) |  CVPR   |  G   | [github](https://github.com/chaoyanghe/MiLeNAS) | 2020 |
| [APQ: Joint Search for Network Architecture, Pruning and Quantization Policy](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_APQ_Joint_Search_for_Network_Architecture_Pruning_and_Quantization_Policy_CVPR_2020_paper.pdf) |  CVPR   |  G   | [github](https://github.com/mit-han-lab/apq) | 2020 |
| [SGAS: Sequential Greedy Architecture Search](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_SGAS_Sequential_Greedy_Architecture_Search_CVPR_2020_paper.pdf) |  CVPR   |  G   | [github](https://github.com/lightaime/sgas) | 2020 |
| [FBNetV2: Differentiable Neural Architecture Search for Spatial and Channel Dimensions](https://arxiv.org/abs/2004.05565) |  CVPR   |  G   | [github](https://github.com/facebookresearch/mobile-vision) | 2020 |
| [AdversarialNAS: Adversarial Neural Architecture Search for GANs](https://arxiv.org/pdf/1912.02037.pdf) |  CVPR   |  G   | [github](https://github.com/chengaopro/AdversarialNAS) | 2019 |
| [When NAS Meets Robustness: In Search of Robust Architectures against Adversarial Attacks](https://arxiv.org/abs/1911.10695) |  CVPR   |  G   | [github](https://github.com/gmh14/RobNets) | 2019 |
| [Block-wisely Supervised Neural Architecture Search with Knowledge Distillation](https://www.xiaojun.ai/papers/CVPR2020_04676.pdf) |  CVPR   |  G   | [github](https://github.com/changlin31/DNA) | 2020 |
| [Overcoming Multi-Model Forgetting in One-Shot NAS with Diversity Maximization](https://www.xiaojun.ai/papers/cvpr-2020-zhang.pdf) |  CVPR   |  G   | [github](https://github.com/MiaoZhang0525/NSAS_FOR_CVPR) | 2020 |
| [Densely Connected Search Space for More Flexible Neural Architecture Search](https://arxiv.org/abs/1906.09607) |  CVPR   |  G   | [github](https://github.com/JaminFong/DenseNAS) | 2020 |
| [Understanding Architectures Learnt by Cell-based Neural Architecture Search](https://openreview.net/pdf?id=H1gDNyrKDS) |  ICLR   |  G   | [github](https://github.com/automl/RobustDARTS) | 2020 |
| [PC-DARTS: Partial Channel Connections for Memory-Efficient Architecture Search](https://openreview.net/forum?id=BJlS634tPr&noteId=BJlS634tPr) |  ICLR   |  G   | [github](https://github.com/yuhuixu1993/PC-DARTS) | 2020 |
| [FasterSeg: Searching for Faster Real-time Semantic Segmentation](https://openreview.net/pdf?id=BJgqQ6NYvB) |  ICLR   |  G   | [github](https://github.com/TAMU-VITA/FasterSeg) | 2020 |
| [Random Search and Reproducibility for Neural Architecture Search](https://arxiv.org/abs/1902.07638) |   UAI   |  G   | [github](https://github.com/D-X-Y/NAS-Projects/blob/master/scripts-search/algos/RANDOM-NAS.sh) | 2019 |
| [One-Shot Neural Architecture Search via Self-Evaluated Template Network](https://arxiv.org/abs/1910.05733) |  ICCV   |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [Efficient Forward Architecture Search](https://arxiv.org/abs/1905.13360) | NeurIPS |  G   | [github](https://github.com/microsoft/petridishnn) | 2019 |
| [Improved Differentiable Architecture Search for Language Modeling and Named Entity Recognition](https://www.aclweb.org/anthology/D19-1367.pdf/) |  EMNLP  |  G   |                    -                     | 2019 |
| [Network Pruning via Transformable Architecture Search](https://arxiv.org/abs/1905.09717) | NeurIPS |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [XNAS: Neural Architecture Search with Expert Advice](https://arxiv.org/abs/1906.08031) | NeurIPS |  G   |                    -                     | 2019 |
| [NetTailor: Tuning the Architecture, Not Just the Weights](https://arxiv.org/abs/1907.00274) |  CVPR   |  G   | [github](https://github.com/pedro-morgado/nettailor) | 2019 |
| [Searching for A Robust Neural Architecture in Four GPU Hours](http://xuanyidong.com/publication/gradient-based-diff-sampler/) |  CVPR   |  G   | [github](https://github.com/D-X-Y/NAS-Projects) | 2019 |
| [AtomNAS: Fine-Grained End-to-End Neural Architecture Search](https://openreview.net/forum?id=BylQSxHFwr) |  ICLR   |  G   | [github](https://github.com/meijieru/AtomNAS) | 2020 |
| [Fast Neural Network Adaptation via Parameter Remapping and Architecture Search](https://openreview.net/forum?id=rklTmyBKPH) |  ICLR   |  G   | [github](https://github.com/JaminFong/FNA) | 2020 |
| [Progressive Differentiable Architecture Search: Bridging the Depth Gap Between Search and Evaluation](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Progressive_Differentiable_Architecture_Search_Bridging_the_Depth_Gap_Between_Search_ICCV_2019_paper.pdf) |  ICCV   |  G   |                    -                     | 2019 |
| [Customizable Architecture Search for Semantic Segmentation](http://arxiv.org/pdf/1908.09550.pdf) |  CVPR   |  G   |                    -                     | 2019 |
| [Learning Architectures from an Extended Search Space for Language Modeling](https://arxiv.org/abs/2005.02593v1) |   ACL   |  G   |                    -                     | 2020 |



### Evaluationary Algorithms - EA
| Title                                    | Venue | Type  |                   Code                   | Year |
| :--------------------------------------- | :---: | :---: | :--------------------------------------: | :--: |
| [**Hierarchical Representations for Efficient Architecture Search**](https://openreview.net/forum?id=BJQRKzbA-) | ICLR  |  EA   |                    -                     | 2018 |
| [**Large-Scale Evolution of Image Classifiers**](https://arxiv.org/pdf/1703.01041.pdf) | ICML  |  EA   |                    -                     | 2017 |
| [RENAS: Reinforced Evolutionary Neural Architecture Search](https://arxiv.org/abs/1808.00193) | CVPR  | EA/RL |                    -                     | 2019 |
| [Efficient Multi-Objective Neural Architecture Search via Lamarckian Evolution](https://arxiv.org/abs/1804.09081) | ICLR  |  EA   |                    -                     | 2019 |
| [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://arxiv.org/pdf/1903.03777.pdf) | CVPR  |  EA   | [github](https://github.com/lixincn2015/Partial-Order-Pruning) | 2019 |
| [MFAS: Multimodal Fusion Architecture Search](https://arxiv.org/pdf/1903.06496.pdf) | CVPR  |  EA   |                    -                     | 2019 |
| [**Regularized Evolution for Image Classifier Architecture Search**](https://arxiv.org/pdf/1802.01548.pdf) | AAAI  |  EA   |                    -                     | 2018 |
| [Resource Constrained Neural Network Architecture Search: Will a Submodularity Assumption Help?](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xiong_Resource_Constrained_Neural_Network_Architecture_Search_Will_a_Submodularity_Assumption_ICCV_2019_paper.pdf) | ICCV  |  EA   |                    -                     | 2019 |
| [Evolving Space-Time Neural Architectures for Videos](https://arxiv.org/abs/1811.10636) | ICCV  |  EA   | [github](https://github.com/google-research/google-research/tree/master/evanet) | 2019 |



### Performance Prediction - PD
| Title                                    | Venue  | Type  |                   Code                   | Year |
| :--------------------------------------- | :----: | :---: | :--------------------------------------: | :--: |
| [Speeding up Automatic Hyperparameter Optimization of Deep Neural Networksby Extrapolation of Learning Curves](http://ml.informatik.uni-freiburg.de/papers/15-IJCAI-Extrapolation_of_Learning_Curves.pdf) | IJCAI  |  PD   | [github](https://github.com/automl/pylearningcurvepredictor) | 2015 |
| [Learning Curve Prediction with Bayesian Neural Networks](http://ml.informatik.uni-freiburg.de/papers/17-ICLR-LCNet.pdf) |  ICLR  |  PD   |                    -                     | 2017 |
| [**Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization**](https://arxiv.org/abs/1603.06560) |  ICLR  |  PD   |                    -                     | 2017 |
| [Accelerating Neural Architecture Search using Performance Prediction](https://arxiv.org/abs/1705.10823) | ICLR-W |  PD   |                    -                     | 2018 |
| [**Progressive Neural Architecture Search**](http://openaccess.thecvf.com/content_ECCV_2018/papers/Chenxi_Liu_Progressive_Neural_Architecture_ECCV_2018_paper.pdf) |  ECCV  |  PD   | [github](https://github.com/chenxi116/PNASNet.pytorch) | 2018 |
| [Generative Teaching Networks: Accelerating Neural Architecture Search by Learning to Generate Synthetic Training Data](https://arxiv.org/abs/1912.07768) |  ICML  |  PD   |                    -                     | 2020 |
| [Neural Architecture Search in a Proxy Validation Loss Landscape](https://proceedings.icml.cc/static/paper_files/icml/2020/439-Paper.pdf) |  ICML  |  PD   |                    -                     | 2020 |
| [Rethinking Performance Estimation in Neural Architecture Search](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Rethinking_Performance_Estimation_in_Neural_Architecture_Search_CVPR_2020_paper.pdf) |  CVPR  |  PD   |                                          |      |
| [Multinomial Distribution Learning for Effective Neural Architecture Search](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zheng_Multinomial_Distribution_Learning_for_Effective_Neural_Architecture_Search_ICCV_2019_paper.pdf) |  ICCV  |  PD   | [github](https://github.com/tanglang96/MDENAS) | 2019 |
| [Learnable Embedding Space for Efficient Neural Architecture Compression](https://openreview.net/forum?id=S1xLN3C9YX) |  ICLR  |  PD   | [github](https://github.com/Friedrich1006/ESNAC) | 2019 |
| [A Flexible Approach to Automated RNN Architecture Generation](https://openreview.net/forum?id=SkOb1Fl0Z) |  ICLR  | RL/PD |                    -                     | 2018 |



### Others
| Title                                    |   Venue   |     Type     |                   Code                   | Year |
| :--------------------------------------- | :-------: | :----------: | :--------------------------------------: | :--: |
| [Hyperparameter Optimization: A Spectral Approach](https://arxiv.org/abs/1706.00764) | NeurIPS-W |    Other     | [github](https://github.com/callowbird/Harmonica) | 2017 |
| [Searching for efficient multi-scale architectures for dense image prediction](https://papers.nips.cc/paper/8087-searching-for-efficient-multi-scale-architectures-for-dense-image-prediction.pdf) |  NeurIPS  |    Other     |                    -                     | 2018 |
| [Neural Architecture Search with Bayesian Optimisation and Optimal Transport](https://arxiv.org/pdf/1802.07191.pdf) |  NeurIPS  |    Other     | [github](https://github.com/kirthevasank/nasbot) | 2018 |
| [NADS: Neural Architecture Distribution Search for Uncertainty Awareness](https://arxiv.org/pdf/2006.06646.pdf) |   ICML    |    Other     |                    -                     | 2020 |
| [NAS-BENCH-201: Extending the Scope of Reproducible Neural Architecture Search](https://openreview.net/forum?id=HJxyZkBKDr) |   ICLR    |    Other     | [github](https://github.com/D-X-Y/AutoDL-Projects) | 2020 |
| [**Evaluating The Search Phase of Neural Architecture Search**](https://openreview.net/forum?id=H1loF2NFwr) |   ICLR    | Other/Survey |                    -                     | 2020 |
| [NAS evaluation is frustratingly hard](https://arxiv.org/abs/1912.12522) |   ICLR    | Other/Survey | [github](https://github.com/antoyang/NAS-Benchmark) | 2020 |
| [Towards Fast Adaptation of Neural Architectures with Meta Learning](https://openreview.net/forum?id=r1eowANFvr) |   ICLR    |    Other     |                    -                     | 2020 |
| [How to Own the NAS in Your Spare Time](https://arxiv.org/abs/2002.06776) |   ICLR    |    Other     |                    -                     | 2020 |
| [Fast and Practical Neural Architecture Search](http://openaccess.thecvf.com/content_ICCV_2019/papers/Cui_Fast_and_Practical_Neural_Architecture_Search_ICCV_2019_paper.pdf) |   ICCV    |    Other     |                    -                     | 2019 |
| [Teacher Guided Architecture Search](http://openaccess.thecvf.com/content_ICCV_2019/papers/Bashivan_Teacher_Guided_Architecture_Search_ICCV_2019_paper.pdf) |   ICCV    |    Other     |                    -                     | 2019 |
| [Towards modular and programmable architecture search](https://arxiv.org/abs/1909.13404) |  NeurIPS  |    Other     | [github](https://github.com/negrinho/deep_architect) | 2019 |
| [Deep Active Learning with a Neural Architecture Search](https://arxiv.org/pdf/1811.07579.pdf) |  NeurIPS  |    Other     |                    -                     | 2019 |
| [NAS-Bench-101: Towards Reproducible Neural Architecture Search](https://arxiv.org/abs/1902.09635) |   ICML    |    Other     | [github](https://github.com/google-research/nasbench) | 2019 |



### High Citation Papers
| Title                                    |  Venue  |  Type  |                   Code                   | Year | Citations |
| :--------------------------------------- | :-----: | :----: | :--------------------------------------: | :--: | :-------: |
| [Learning Transferable Architectures for Scalable Image Recognition](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.pdf) |  CVPR   |   RL   | [github](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet) | 2018 |  1155+41  |
| [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578) |  ICLR   |   RL   |                    -                     | 2017 |  825+365  |
| [Efficient Neural Architecture Search via Parameter Sharing](http://proceedings.mlr.press/v80/pham18a.html) |  ICML   |   RL   | [github](https://github.com/carpedm20/ENAS-pytorch) | 2018 |    621    |
| [Designing Neural Network Architectures using Reinforcement Learning](https://openreview.net/pdf?id=S1c2cvqee) |  ICLR   |   RL   | [github](https://github.com/bowenbaker/metaqnn) | 2017 |  407+35   |
| [Large-Scale Evolution of Image Classifiers](https://arxiv.org/pdf/1703.01041.pdf) |  ICML   |   EA   |                    -                     | 2017 |  282+181  |
| [DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055) |  ICLR   |   G    | [github](https://github.com/quark0/darts) | 2018 |  270+171  |
| [Progressive Neural Architecture Search](http://openaccess.thecvf.com/content_ECCV_2018/papers/Chenxi_Liu_Progressive_Neural_Architecture_ECCV_2018_paper.pdf) |  ECCV   |   PD   | [github](https://github.com/chenxi116/PNASNet.pytorch) | 2018 |  273+166  |
| [Hierarchical Representations for Efficient Architecture Search](https://openreview.net/forum?id=BJQRKzbA-) |  ICLR   |   EA   |                    -                     | 2018 |  161+81   |
| [Regularized Evolution for Image Classifier Architecture Search](https://arxiv.org/pdf/1802.01548.pdf) |  AAAI   |   EA   |                    -                     | 2018 |  255+168  |
| [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/abs/1807.11626) |  CVPR   |   RL   | [github](https://github.com/AnjieZheng/MnasNet-PyTorch) | 2018 |  183+95   |
| [Neural Architecture Search: A Survey](http://www.jmlr.org/papers/volume20/18-598/18-598.pdf) |  JMLR   | Survey |                    -                     | 2018 |  163+60   |
| [ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware](https://openreview.net/pdf?id=HylVB3AqYm) |  ICLR   |  RL/G  | [github](https://github.com/MIT-HAN-LAB/ProxylessNAS) | 2019 |  139+99   |
| [Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization](https://arxiv.org/abs/1603.06560) |  ICLR   |   PD   |                    -                     | 2017 |  157+36   |
| [SMASH: One-Shot Model Architecture Search through HyperNetworks](https://arxiv.org/pdf/1708.05344.pdf) |  ICLR   |   G    | [github](https://github.com/ajbrock/SMASH) | 2018 |  141+43   |
| [FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443) |  CVPR   |   G    |                    -                     | 2019 |  110+23   |
| [Neural Architecture Optimization](https://arxiv.org/pdf/1808.07233.pdf) | NeurIPS |   G    | [github](https://github.com/renqianluo/NAO) | 2018 |  114+11   |
| [Understanding and Simplifying One-Shot Architecture Search](http://proceedings.mlr.press/v80/bender18a/bender18a.pdf) |  ICML   |   G    |                    -                     | 2018 |    120    |





## Systems
| Title                                    | Venue  |  Type  |                   Code                   | Year |
| :--------------------------------------- | :----: | :----: | :--------------------------------------: | :--: |
| [Auto-Keras: An Efficient Neural Architecture Search System](https://arxiv.org/abs/1806.10282) |   -    | System | [github](https://github.com/keras-team/autokeras) | 2018 |
| [Neural Network Intelligence](https://nni.readthedocs.io/en/latest/) |   -    | System | [github](https://github.com/microsoft/nni) |  -   |
| [AdaNet: A Scalable and Flexible Framework for Automatically Learning Ensembles](https://arxiv.org/abs/1905.00080) | ICML-W | System | [github](https://github.com/tensorflow/adanet) | 2019 |
