# MosquitoSSM
*Estimating Mosquito Abundance and Population Suppression*

This repository contains:
- ModelDescription.stan: a file that contains a description of a Bayesian state-space model that can be applied to data from the Debug Innisfail Project.
- MultiRegionData: a file that contains data from Debug Innisfail that is readable by the stan model description.
- runModel.txt: a file that has the single line needed to run the model using cmdstan (see mc-stan.org)

The stan model can be run using rstan, cmdstan, pystan and many other interfaces to stan.  Please visit mc-stan.org for instructions on how to install stan on your machine and guidance on how to run the model for your specific implementation (R, Python, Command Line).
