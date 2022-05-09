# Simultaneous Inference of Networks and their Covariates (SINC)

### Author: Nathan Osborne

SINC Algorithm to do simultaneous estimation of network of compisitional data and variable selection of additional covariates. The algorithm uses a novel Variational EM estimation scheme for computational efficiency. To increase compuation speed it is also built to support multiproccessor computing. A more detailed description of the model, algorithm, and applications can be found in 

> Osborne, N., Peterson, C.B. and Vannucci, M. (2022). Latent Network Estimation and Variable Selection for Compositional Data via 
Variational EM. *Journal of Computational and Graphical Statistics*. 31(1): 163-175

All functions needed to run SINC are found in SINC_functions.py

SINC depends on numpy, scipy, multiprocess, and multiprocessing, and will need to be installed before using

## SINC_functions.py

This file contains the SINC function and all other dependent functions to run SINC. These are dependent on the python modules numpy, scipy, multiprocess, and multiprocessing.

## small_example

A folder containing a small simulation tutorial on how the function may be used. In this folder you will find small simulation.ipynb, a notebook showing the models use, with supplementing synthetic data saved as csv files.

## Simulations

The simulations reported in section 4 of the paper can be found in this folder, labeled as Band, Cluster, Hub, and Random, corresponding to the graph structure.
