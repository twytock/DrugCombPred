
## Repository Description
Source code for generating the figures in the paper "Repurposing Drug Combinations for the Treatment of Brain Cancers."

## System Requirements and Installation
The python code has been run with python 3.7 with the packages indicated in the `comb_pred_env.yml` file found at the top level of this repository. 
For the drug combination prediction method only, we require CPLEX () to solve the relevant mixed-integer quadratic programming problem.

The required version of python and the dependent packages can be downloaded here: https://www.anaconda.com/distribution/. 
Create a new anaconda environment and install from the default channels with `conda env create -f comb_pred_env.yml`.
Activate the environment with `conda activate comb_pred_env`

## Repository Organization
This repository includes a jupyter notebook for reproducing the experimental analysis:

1. Documentation for [analyzing the cell viability data (Experimental Results)](https://github.com/twytock/DrugCombPred/doc/Experimental_Results.md).

The source code is stored in the [code](https://github.com/twytock/DrugCombPred/code/) folder.
The require input data is stored in the [data](https://github.com/twytock/DrugCombPred/data/) folder.
The outputs generated from running the code are stored in the [output](https://github.com/twytock/DrugCombPred/output/) folder.