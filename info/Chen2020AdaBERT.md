# Title
AdaBERT: Task-Adaptive BERT Compression with Differentiable Neural Architecture Search

## Author
Daoyuan Chen, Yaliang Li, Minghui Qiu, Zhen Wang, Bofang Li, Bolin Ding, Hongbo Deng, Jun Huang, Wei Lin, Jingren Zhou

## Abstract
Large pre-trained language models such as BERT have shown their effectiveness in various natural language processing tasks. However, the huge parameter size makes them difficult to be deployed in real-time applications that require quick inference with limited resources. Existing methods compress BERT into small models while such compression is task-independent, i.e., the same compressed BERT for all different downstream tasks. Motivated by the necessity and benefits of task-oriented BERT compression, we propose a novel compression method, AdaBERT, that leverages differentiable Neural Architecture Search to automatically compress BERT into task-adaptive small models for specific tasks. We incorporate a task-oriented knowledge distillation loss to provide search hints and an efficiency-aware loss as search constraints, which enables a good trade-off between efficiency and effectiveness for task-adaptive BERT compression. We evaluate AdaBERT on several NLP tasks, and the results demonstrate that those task-adaptive compressed models are 12.7x to 29.3x faster than BERT in inference time and 11.5x to 17.0x smaller in terms of parameter size, while comparable performance is maintained.

## Bib
@inproceedings{ijcai2020-0341,
  title     = {AdaBERT: Task-Adaptive BERT Compression with Differentiable Neural Architecture Search},
  author    = {Chen, Daoyuan and Li, Yaliang and Qiu, Minghui and Wang, Zhen and Li, Bofang and Ding, Bolin and Deng, Hongbo and Huang, Jun and Lin, Wei and Zhou, Jingren},
  booktitle = {Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},             
  editor    = {Christian Bessiere},	
  pages     = {2463--2469},
  year      = {2020},
  month     = {7},
  note      = {Main track}
  doi       = {10.24963/ijcai.2020/341},
  url       = {https://doi.org/10.24963/ijcai.2020/341},
}
