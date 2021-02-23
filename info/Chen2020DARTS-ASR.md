# Title
DARTS-ASR: Differentiable Architecture Search for Multilingual Speech Recognition and Adaptation

## Author
Yi-Chen Chen, Jui-Yang Hsu, Cheng-Kuang Lee, Hung-yi Lee

## Abstract
In previous works, only parameter weights of ASR models are optimized under fixed-topology architecture. However, the design of successful model architecture has always relied on human experience and intuition. Besides, many hyperparameters related to model architecture need to be manually tuned. Therefore in this paper, we propose an ASR approach with efficient gradient-based architecture search, DARTS-ASR. In order to examine the generalizability of DARTS-ASR, we apply our approach not only on many languages to perform monolingual ASR, but also on a multilingual ASR setting. Following previous works, we conducted experiments on a multilingual dataset, IARPA BABEL. The experiment results show that our approach outperformed the baseline fixed-topology architecture by 10.2% and 10.0% relative reduction on character error rates under monolingual and multilingual ASR settings respectively. Furthermore, we perform some analysis on the searched architectures by DARTS-ASR.





## Bib
@inproceedings{Chen2020,
  author={Yi-Chen Chen and Jui-Yang Hsu and Cheng-Kuang Lee and Hung-yi Lee},
  title={{DARTS-ASR: Differentiable Architecture Search for Multilingual Speech Recognition and Adaptation}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={1803--1807},
  doi={10.21437/Interspeech.2020-1315},
  url={http://dx.doi.org/10.21437/Interspeech.2020-1315}
}