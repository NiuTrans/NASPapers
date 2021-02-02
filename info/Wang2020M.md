# Title
M-NAS: Meta Neural Architecture Search

## Author
Jiaxing Wang, Jiaxiang Wu, Haoli Bai, Jian Cheng

## Abstract
Neural Architecture Search (NAS) has recently outperformed hand-crafted networks in various areas. However, most prevalent NAS methods only focus on a pre-defined task. For a previously unseen task, the architecture is either searched from scratch, which is inefficient, or transferred from the one obtained on some other task, which might be sub-optimal. In this paper, we investigate a previously unexplored problem: whether a universal NAS method exists, such that task-aware architectures can be effectively generated? Towards this problem, we propose Meta Neural Architecture Search (M-NAS). To obtain task-specific architectures, M-NAS adopts a task-aware architecture controller for child model generation. Since optimal weights for different tasks and architectures span diversely, we resort to meta-learning, and learn meta-weights that efficiently adapt to a new task on the corresponding architecture with only several gradient descent steps. Experimental results demonstrate the superiority of M-NAS against a number of competitive baselines on both toy regression and few shot classification problems.

## Bib
@article{Wang_Wu_Bai_Cheng_2020, title={M-NAS: Meta Neural Architecture Search}, volume={34}, url={https://ojs.aaai.org/index.php/AAAI/article/view/6084}, DOI={10.1609/aaai.v34i04.6084}, abstractNote={&lt;p&gt;Neural Architecture Search (NAS) has recently outperformed hand-crafted networks in various areas. However, most prevalent NAS methods only focus on a pre-defined task. For a previously unseen task, the architecture is either searched from scratch, which is inefficient, or transferred from the one obtained on some other task, which might be sub-optimal. In this paper, we investigate a previously unexplored problem: whether a universal NAS method exists, such that task-aware architectures can be effectively generated? Towards this problem, we propose Meta Neural Architecture Search (M-NAS). To obtain task-specific architectures, M-NAS adopts a task-aware architecture controller for child model generation. Since optimal weights for different tasks and architectures span diversely, we resort to meta-learning, and learn meta-weights that efficiently adapt to a new task on the corresponding architecture with only several gradient descent steps. Experimental results demonstrate the superiority of M-NAS against a number of competitive baselines on both toy regression and few shot classification problems.&lt;/p&gt;}, number={04}, journal={Proceedings of the AAAI Conference on Artificial Intelligence}, author={Wang, Jiaxing and Wu, Jiaxiang and Bai, Haoli and Cheng, Jian}, year={2020}, month={Apr.}, pages={6186-6193} }