# Title
A Flexible Approach to Automated RNN Architecture Generation

## Author
Martin Schrimpf, Stephen Merity, James Bradbury, Richard Socher

## Abstract
The process of designing neural architectures requires expert knowledge and extensive trial and error.
While automated architecture search may simplify these requirements, the recurrent neural network (RNN) architectures generated by existing methods are limited in both flexibility and components.
We propose a domain-specific language (DSL) for use in automated architecture search which can produce novel RNNs of arbitrary depth and width.
The DSL is flexible enough to define standard architectures such as the Gated Recurrent Unit and Long Short Term Memory and allows the introduction of non-standard RNN components such as trigonometric curves and layer normalization.  Using two different candidate generation techniques, random search with a ranking function and reinforcement learning, 
we explore the novel architectures produced by the RNN DSL for language modeling and machine translation domains.

## Bib
@misc{
schrimpf2018a,
title={A Flexible Approach to Automated {RNN} Architecture Generation},
author={Martin Schrimpf and Stephen Merity and James Bradbury and Richard Socher},
year={2018},
url={https://openreview.net/forum?id=SkOb1Fl0Z},
}