# Title 
Learning to Compose Domain-Specific Transformations for Data Augmentation
## Author 
Alexander J. Ratner, Henry Ehrenberg, Zeshan Hussain, Jared Dunnmon, Christopher Ré
## Key Words 

## Abstract 
Data augmentation is a ubiquitous technique for increasing the size of labeled training sets by leveraging task-specific data transformations that preserve class labels. While it is often easy for domain experts to specify individual transformations, constructing and tuning the more sophisticated compositions typically needed to achieve state-of-the-art results is a time-consuming manual task in practice. We propose a method for automating this process by learning a generative sequence model over user-specified transformation functions using a generative adversarial approach. Our method can make use of arbitrary, non-deterministic transformation functions, is robust to misspecified user input, and is trained on unlabeled data. The learned transformation model can then be used to perform data augmentation for any end discriminative model. In our experiments, we show the efficacy of our approach on both image and text datasets, achieving improvements of 4.0 accuracy points on CIFAR-10, 1.4 F1 points on the ACE relation extraction task, and 3.4 accuracy points when using domain-specific transformation operations on a medical imaging dataset as compared to standard heuristic augmentation approaches.
## Bib
 @inproceedings{NIPS2017_f26dab9b,
 author = {Ratner, Alexander J and Ehrenberg, Henry and Hussain, Zeshan and Dunnmon, Jared and Ré, Christopher},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {I. Guyon and U. V. Luxburg and S. Bengio and H. Wallach and R. Fergus and S. Vishwanathan and R. Garnett},
 pages = {3236--3246},
 publisher = {Curran Associates, Inc.},
 title = {Learning to Compose Domain-Specific Transformations for Data Augmentation},
 url = {https://proceedings.neurips.cc/paper/2017/file/f26dab9bf6a137c3b6782e562794c2f2-Paper.pdf},
 volume = {30},
 year = {2017}
}