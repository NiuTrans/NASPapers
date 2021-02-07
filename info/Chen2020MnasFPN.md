# Title
MnasFPN: Learning Latency-Aware Pyramid Architecture for Object Detection on Mobile Devices

## Author
Bo Chen, Golnaz Ghiasi, Hanxiao Liu, Tsung-Yi Lin, Dmitry Kalenichenko, Hartwig Adam, Quoc V. Le

## Abstract
Despite the blooming success of architecture search for vision tasks in resource-constrained environments, the design of on-device object detection architectures have mostly been manual. The few automated search efforts are either centered around non-mobile-friendly search spaces or not guided by on-device latency. We propose MnasFPN, a mobile-friendly search space for the detection head, and combine it with latency-aware architecture search to produce efficient object detection models. The learned MnasFPN head, when paired with MobileNetV2 body, outperforms MobileNetV3+SSDLite by 1.8 mAP at similar latency on Pixel. It is both 1 mAP more accurate and 10\% faster than NAS-FPNLite. Ablation studies show that the majority of the performance gain comes from innovations in the search space. Further explorations reveal an interesting coupling between the search space design and the search algorithm, for which the complexity of MnasFPN search space is opportune.

## Bib
@INPROCEEDINGS{9156863,  author={B. {Chen} and G. {Ghiasi} and H. {Liu} and T. -Y. {Lin} and D. {Kalenichenko} and H. {Adam} and Q. V. {Le}},  booktitle={2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},   title={MnasFPN: Learning Latency-Aware Pyramid Architecture for Object Detection on Mobile Devices},   year={2020},  volume={},  number={},  pages={13604-13613},  doi={10.1109/CVPR42600.2020.01362}}