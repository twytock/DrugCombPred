
## Repository Description
Source code for generating the figures in the paper "Repurposing Drug Combinations for the Treatment of Brain Cancers."

## System Requirements and Installation
The python code has been run with python 3.7 with the packages indicated in the `comb_pred_env.yml` file found at the top level of this repository. 
For the drug combination prediction method only, we require CPLEX () to solve the relevant mixed-integer quadratic programming problem.

The required version of python and the dependent packages can be downloaded here: https://www.anaconda.com/distribution/. 
Create a new anaconda environment and install from the default channels with `conda env create -f comb_pred_env.yml`.
Activate the environment with `conda activate comb_pred_env`, then install CPLEX from the conda-forge channel with `conda install -c conda-forge <CPLEX_PACKAGE_NAME>`.  

## Repository Organization
This repository is divided into 3 parts:

1. Documentation for [the nonadditivity prediction method (Computational Cross-Validation)](https://github.com/twytock/<REPOSITORY_NAME>/doc/Computational_Cross_Validation.md).
2. Documentation for [the drug combination prediction method (Drug Combination Prediction)](https://github.com/twytock/<REPOSITORY_NAME>/doc/Drug_Combination_Prediction.md).
3. Documentation for [analyzing the cell viability data (Experimental Results)](https://github.com/twytock/<REPOSITORY_NAME>/doc/Experimental_Results.md).

The source code is stored in the [code](https://github.com/twytock/<REPOSITORY_NAME>/code/) folder.
The require input data is stored in the [data](https://github.com/twytock/<REPOSITORY_NAME>/data/) folder.
The outputs generated from running the code are stored in the [output](https://github.com/twytock/<REPOSITORY_NAME>/output/) folder.