# Title
Evolving Space-Time Neural Architectures for Videos

## Author
AJ Piergiovanni, Anelia Angelova, Alexander Toshev, Michael S. Ryoo

## Abstract
We present a new method for finding video CNN architectures that more optimally capture rich spatio-temporal information in videos. Previous work, taking advantage of 3D convolutions, obtained promising results by manually designing CNN video architectures. We here develop a novel evolutionary algorithm that automatically explores models with different types and combinations of layers to jointly learn interactions between spatial and temporal aspects of video representations. We demonstrate the generality of this algorithm by applying it to two meta-architectures. Further, we propose a new component, the iTGM layer, which more efficiently utilizes its parameters to allow learning of space-time interactions over longer time horizons. The iTGM layer is often preferred by the evolutionary algorithm and allows building cost-efficient networks. The proposed approach discovers new diverse and interesting video architectures that were unknown previously. More importantly they are both more accurate and faster than prior models, and outperform the state-of-the-art results on four datasets: Kinetics, Charades, Moments in Time and HMDB. We will open source the code and models, to encourage future model development.


## Bib
@InProceedings{Piergiovanni_2019_ICCV,
author = {Piergiovanni, AJ and Angelova, Anelia and Toshev, Alexander and Ryoo, Michael S.},
title = {Evolving Space-Time Neural Architectures for Videos},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}