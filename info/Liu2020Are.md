# Title
Are Labels Necessary for Neural Architecture Search?

## Author
Chenxi Liu, Piotr Dollár, Kaiming He, Ross Girshick, Alan Yuille, Saining Xie

## Abstract
Existing neural network architectures in computer vision -- whether designed by humans or by machines -- were typically found using both images and their associated labels. In this paper, we ask the question: can we find high-quality neural architectures using only images, but no human-annotated labels? To answer this question, we first define a new setup called Unsupervised Neural Architecture Search (UnNAS). We then conduct two sets of experiments. In sample-based experiments, we train a large number (500) of diverse architectures with either supervised or unsupervised objectives, and find that the architecture rankings produced with and without labels are highly correlated. In search-based experiments, we run a well-established NAS algorithm (DARTS) using various unsupervised objectives, and report that the architectures searched without labels can be competitive to their counterparts searched with labels. Together, these results reveal the potentially surprising finding that labels are not necessary, and the image statistics alone may be sufficient to identify good neural architectures.

## Bib
@inproceedings{liu2020labels,
  title={Are labels necessary for neural architecture search?},
  author={Liu, Chenxi and Doll{\'a}r, Piotr and He, Kaiming and Girshick, Ross and Yuille, Alan and Xie, Saining},
  booktitle={European Conference on Computer Vision},
  pages={798--813},
  year={2020},
  organization={Springer}
}