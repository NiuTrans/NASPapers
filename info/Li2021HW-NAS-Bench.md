# Title
HW-NAS-Bench: Hardware-Aware Neural Architecture Search Benchmark

## Author
Chaojian Li, Zhongzhi Yu, Yonggan Fu, Yongan Zhang, Yang Zhao, Haoran You, Qixuan Yu, Yue Wang, Cong Hao, Yingyan Lin

## Abstract
HardWare-aware Neural Architecture Search (HW-NAS) has recently gained tremendous attention for automating the design of DNNs to be deployed into more resource-constrained daily life devices. Despite their promising performance, developing optimal HW-NAS solutions can be prohibitively challenging as it requires cross-disciplinary knowledge in the algorithm, micro-architecture, and device-specific compilation. First, to construct the hardware cost to be incorporated into the NAS process, existing works mostly adopt either pre-collected cost look-up tables or device-specific hardware cost models. The former can be time-consuming due to the needed learning about the device's compilation method and how to set up the measurement pipeline, while the latter is often a barrier for non-hardware experts like NAS researchers. Both of them limit the development of HW-NAS innovations and impose a barrier-to-entry to non-hardware experts. Second, similar to generic NAS, it can be notoriously difficult to benchmark HW-NAS algorithms due to the required significant computational resources and the differences in their adopted search space, hyperparameters, and hardware devices. To this end, we develop HW-NAS-Bench, the first public dataset for HW-NAS research which aims to democratize HW-NAS research to non-hardware experts and make HW-NAS research more reproducible and accessible. To design HW-NAS-Bench, we carefully collected the measured/estimated hardware performance (e.g., energy cost and latency) of all the networks in the search space of both NAS-Bench-201 and FBNet, considering six hardware devices that fall into three categories (i.e., commercial edge devices, FPGA, and ASIC). Furthermore, we provide a comprehensive analysis of the collected measurements in HW-NAS-Bench to provide insights for HW-NAS research. Finally, we demonstrate exemplary user cases when HW-NAS-Bench (1) allows non-hardware experts to perform HW-NAS by simply querying our pre-measured dataset and (2) verify that dedicated device-specific HW-NAS can indeed often provide optimal accuracy-cost trade-offs. The code is available at https://github.com/RICE-EIC/HW-NAS-Bench.

## Bib
@inproceedings{
li2021hwnasbench,
title={{\{}HW{\}}-{\{}NAS{\}}-Bench: Hardware-Aware Neural Architecture Search Benchmark},
author={Chaojian Li and Zhongzhi Yu and Yonggan Fu and Yongan Zhang and Yang Zhao and Haoran You and Qixuan Yu and Yue Wang and Cong Hao and Yingyan Lin},
booktitle={International Conference on Learning Representations},
year={2021},
url={https://openreview.net/forum?id=_0kaDkv3dVf}
}