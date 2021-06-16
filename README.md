# Discrepancy-based-inference-for-generative-models-using-QMC
This repository contains the python code to recreate the numerical experiments in the paper "Discrepancy-based Inference for Generative Models using QMC" by Ziang Niu, Johanna Meier and François-Xavier Briol. It is optimised for the use with [Google Colab](https://colab.research.google.com/) and mounts the Google drive to load other required notebooks located in the default folder for Colab notebooks. For local use, file paths have to be adjusted where indicated.

## Content of sub-folders:

### Generating-vecs-and-mats
Generating vectors and matrices for lattices:<br> 
- *lattice_vec.600.20.npy* for order-2 lattice<br> 
- *lattice_vec.600.13.npy* for order-8 lattice<br> 
The files are taken from Dirk Nuyens' [Magic Point Shop](https://people.cs.kuleuven.be/~dirk.nuyens/qmc-generators/)
