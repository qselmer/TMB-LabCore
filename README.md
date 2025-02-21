# TMB-LabCore
TMB-LabCore: A space dedicated to practicing, exploring, and developing skills in TMB programming.

## Description
Each folder contains a TMB example. If both examp.cpp and examp.Rmd exist, then examp is considered a valid example. Each example is associated with a file named examp.expected.RData, which contains the correct output from a reference test machine.

Example overview:

| **N°** | **Example**           | **Description**                     |**Implemented**|
|--------|-----------------------|-------------------------------------|---------------|
|   1    |*linreg*:              |Simple linear regression.            |  **X**   |
|   1    |*adaptive_integration*:| Adaptive integration using 'tiny_ad'|          |     
|   1    |*ar1_4D*:              |  Separable covariance on 4D lattice with AR1 structure in each direction.                                                        |          |   
|   1    |*hmm*:                 |Inference in a 'double-well' stochastic differential equation using HMM filter.                                             |          |   
|   1    |*laplace*:             |Laplace approximation from scratch demonstrated on 'spatial' example.                                                     |          |
|   1    |*linreg_parallel*:     |Parallel linear regression.          |          |
|   1    |*longlinreg*:          |Linear regression -10^6 observations.|          |
|   1    |*lr_test*:             |Illustrate map feature of TMB to perform likelihood ratio tests on a ragged array dataset.                                       |          |
|   1    |*matern*:              |Gaussian process with Matern covariance.|          |
|   1    |*mvrw*:                |Random walk with multivariate correlated increments and measurement noise.                                                     |          |
|   1    |*mvrw_sparse*:         |Identical with random walk example. Utilizing sparse block structure so efficient when the number of states is high.              |          |
|   1    |*nmix*:                |nmix example from NCEAS.             |          |         
|   1    |*orange_big*:          |Scaled up version of the Orange Tree example (5000 latent random variables)                                                      |          |         
|   1    |*sam*:                 |State space assessment model from Nielsen and Berg 2014, Fisheries Research.                                                    |          |
|   1    |*sde_linear*:          |Inference in a linear scalar stochastic differential equation.                                                              |          |
|   1    |*sdv_multi_compact*:   |Compact version of sdv_multi.        |          |
|   1    |*sdv_multi*:           |Multivatiate SV model from Skaug and Yu 2013, Comp. Stat & data Analysis (to appear)                                                   |          |
|   1    |*socatt*:              |socatt from ADMB example collection.          |          |
|   1    |*spatial*:             |Spatial poisson GLMM on a grid, with exponentially decaying correlation function.                                                  |          |
|   1    |*spde_aniso*:          |Anisotropic version of *spde.cpp*.            |          |
|   1    |*spde*:                |Illustration SPDE/INLA approach to spatial modelling via Matern correlation function.                                         |          |
|   1    |*thetalog*:            |Theta logistic population model from Pedersen et al 2012, Ecol. Modelling.                                                    |          |
|   1    |*transform2*:          |Beta distributed random effects using copulas.|          |
|   1    |*transform_parallel*:  |Parallel version of transform.       |          |
|   1    |*transform*:           |Gamma distributed random effects using copulas.|          |
|   1    |*tweedie*:             |Estimating parameters in a Tweedie distribution.|          |
