# Title
Hyperband: a novel bandit-based approach to hyperparameter optimization

## Venue
ICLR

## Author
Lisha Li, Kevin G Jamieson profile imageKevin Jamieson, Giulia  Desalvo profile imageGiulia DeSalvo, Afshin  Rostamizadeh profile imageAfshin Rostamizadeh, Ameet  Talwalkar profile imageAmeet Talwalkar

## Abstract
Performance of machine learning algorithms depends critically on identifying a good set of hyperparameters. While recent approaches use Bayesian optimization to adaptively select configurations, we focus on speeding up random search through adaptive resource allocation and early-stopping. We formulate hyperparameter optimization as a pure-exploration nonstochastic infinite-armed bandit problem where a predefined resource like iterations, data samples, or features is allocated to randomly sampled configurations. We introduce a novel algorithm, Hyperband, for this framework and analyze its theoretical properties, providing several desirable guarantees. Furthermore, we compare Hyperband with popular Bayesian optimization methods on a suite of hyperparameter optimization problems. We observe that Hyperband can provide over an order-of-magnitude speedup over our competitor set on a variety of deep-learning and kernel-based learning problems.

## Bib
@article{10.5555/3122009.3242042,
author = {Li, Lisha and Jamieson, Kevin and DeSalvo, Giulia and Rostamizadeh, Afshin and Talwalkar, Ameet},
title = {Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization},
year = {2017},
issue_date = {January 2017},
publisher = {JMLR.org},
volume = {18},
number = {1},
issn = {1532-4435},
abstract = {Performance of machine learning algorithms depends critically on identifying a good set of hyperparameters. While recent approaches use Bayesian optimization to adaptively select configurations, we focus on speeding up random search through adaptive resource allocation and early-stopping. We formulate hyperparameter optimization as a pure-exploration nonstochastic infinite-armed bandit problem where a predefined resource like iterations, data samples, or features is allocated to randomly sampled configurations. We introduce a novel algorithm, Hyperband, for this framework and analyze its theoretical properties, providing several desirable guarantees. Furthermore, we compare Hyperband with popular Bayesian optimization methods on a suite of hyperparameter optimization problems. We observe that Hyperband can provide over an order-of-magnitude speedup over our competitor set on a variety of deep-learning and kernel-based learning problems.},
journal = {J. Mach. Learn. Res.},
month = jan,
pages = {6765–6816},
numpages = {52},
keywords = {infinite-armed bandits, online optimization, model selection, deep learning, hyperparameter optimization}
}