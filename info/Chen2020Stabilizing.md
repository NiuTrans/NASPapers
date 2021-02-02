# Title
Stabilizing Differentiable Architecture Search via Perturbation-based Regularization

## Author
Xiangning Chen, Cho-Jui Hsieh

## Abstract
Differentiable architecture search (DARTS) is a prevailing NAS solution to identify architectures. Based on the continuous relaxation of the architecture space, DARTS learns a differentiable architecture weight and largely reduces the search cost. However, its stability has been challenged for yielding deteriorating architectures as the search proceeds. We find that the precipitous validation loss landscape, which leads to a dramatic performance drop when distilling the final architecture, is an essential factor that causes instability. Based on this observation, we propose a perturbation-based regularization - SmoothDARTS (SDARTS), to smooth the loss landscape and improve the generalizability of DARTS-based methods. In particular, our new formulations stabilize DARTS-based methods by either random smoothing or adversarial attack. The search trajectory on NAS-Bench-1Shot1 demonstrates the effectiveness of our approach and due to the improved stability, we achieve performance gain across various search spaces on 4 datasets. Furthermore, we mathematically show that SDARTS implicitly regularizes the Hessian norm of the validation loss, which accounts for a smoother loss landscape and improved performance.

## Bib
@inproceedings{chen2020stabilizing,
  title={Stabilizing differentiable architecture search via perturbation-based regularization},
  author={Chen, Xiangning and Hsieh, Cho-Jui},
  booktitle={International Conference on Machine Learning},
  pages={1554--1565},
  year={2020},
  organization={PMLR}
}