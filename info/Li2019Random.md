# Title
Random Search and Reproducibility for Neural Architecture Search

## Author
Liam Li, Ameet Talwalkar

## Abstract
Neural architecture search (NAS) is a promising research direction that has the potential to replace expert-designed networks with learned, task-specific architectures. In this work, in order to help ground the empirical results in this field, we propose new NAS baselines that build off the following observations: (i) NAS is a specialized hyperparameter optimization problem; and (ii) random search is a competitive baseline for hyperparameter optimization. Leveraging these observations, we evaluate both random search with early-stopping and a novel random search with weight-sharing algorithm on two standard NAS benchmarks---PTB and CIFAR-10. Our results show that random search with early-stopping is a competitive NAS baseline, e.g., it performs at least as well as ENAS, a leading NAS method, on both benchmarks. Additionally, random search with weight-sharing outperforms random search with early-stopping, achieving a state-of-the-art NAS result on PTB and a highly competitive result on CIFAR-10. Finally, we explore the existing reproducibility issues of published NAS results. We note the lack of source material needed to exactly reproduce these results, and further discuss the robustness of published results given the various sources of variability in NAS experimental setups. Relatedly, we provide all information (code, random seeds, documentation) needed to exactly reproduce our results, and report our random search with weight-sharing results for each benchmark on multiple runs.

## Bib
@inproceedings{li2020random,
  title={Random search and reproducibility for neural architecture search},
  author={Li, Liam and Talwalkar, Ameet},
  booktitle={Uncertainty in Artificial Intelligence},
  pages={367--377},
  year={2020},
  organization={PMLR}
}