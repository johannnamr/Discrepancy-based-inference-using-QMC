# Discrepancy-based-inference-for-generative-models-using-QMC
This repository contains the python code to recreate the numerical experiments in the paper "Discrepancy-based Inference for Generative Models using QMC" by Ziang Niu, Johanna Meier and François-Xavier Briol. It is optimised for the use with [Google Colab](https://colab.research.google.com/) and mounts the Google drive to load other required notebooks located in the default folder for Colab notebooks. For local use, file paths have to be adjusted where indicated.

## Content of sub-folders:

### Generating-vecs-and-mats
Generating vectors and matrices for lattices:<br> 
- *lattice_vec.600.20.npy* for order-2 lattice<br> 
- *lattice_vec.600.13.npy* for order-8 lattice<br> 

The vectors are taken from Dirk Nuyens' [Magic Point Shop](https://people.cs.kuleuven.be/~dirk.nuyens/qmc-generators/).

### Helper-functions
Helper functions:<br>
- *Utils.ipynb*: functions for convergence and optimisation experiments
- *Plot_fcts.ipynb*: plotting funtions
- *ot_slicedW.ipynb*: adapted source code of the [POT](https://pythonot.github.io/index.html) library for sliced Wasserstein distances

The first two notebooks are loaded in all other notebooks listed below, so that their file paths might need to be adjusted where indicated. The third notebook is loaded in all sliced Wasserstein distance applications.

### Sample complexity
#### Uniform
Results for the uniform distribution:

#### Gaussian
Results for the Gaussian distribution:

### Inference
#### Bivariate-beta-distribution
Results for the bivariate beta distribution:

#### MV-g-and-k-distribution
Results for the multivariate g-and-k distribution:

#### G-and-k-distribution
Results for the univariate g-and-k distribution:
- *gandk_check.ipynb*: test of kernel, generator and all partial derivatives
- *gandk_optim.ipynb*: optimisation procedure for squared MMD using MC, QMC and RQMC


