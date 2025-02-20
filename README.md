# TMB-LabCore
TMB-LabCore: A space dedicated to practicing, exploring, and developing skills in TMB programming.

This folder contains TMB examples. If "examp.cpp" and "examp.R" both exists then "examp" is a valid example. Test automation is provided by the files "Makefile" and "unittest.R". The purpose of the test is to verify correctness of results and to verify that the timings are reasonable. Each example is associated with a file "examp.expected.RData" with correct output from a reference test machine (For new examples this file is automatically generated, and correctness must be manually verified). Perform a full test by running

Example overview:
Examples in '.':

"adaptive_integration": Adaptive integration using
                        'tiny_ad'
"ar1_4D":               Separable covariance on 4D lattice
                        with AR1 structure in each
                        direction.
"hmm":                  Inference in a 'double-well'
                        stochastic differential equation
                        using HMM filter.
"laplace":              Laplace approximation from scratch
                        demonstrated on 'spatial' example.
"linreg_parallel":      Parallel linear regression.
"linreg":               Simple linear regression.
"longlinreg":           Linear regression - 10^6
                        observations.
"lr_test":              Illustrate map feature of TMB to
                        perform likelihood ratio tests on a
                        ragged array dataset.
"matern":               Gaussian process with Matern
                        covariance.
"mvrw":                 Random walk with multivariate
                        correlated increments and
                        measurement noise.
"mvrw_sparse":          Identical with random walk example.
                        Utilizing sparse block structure so
                        efficient when the number of states
                        is high.
"nmix":                 nmix example from
                        https://groups.nceas.ucsb.edu/non-linear-modeling/projects/nmix
"orange_big":           Scaled up version of the Orange
                        Tree example (5000 latent random
                        variables)
"sam":                  State space assessment model from
                        Nielsen and Berg 2014, Fisheries
                        Research.
"sde_linear":           Inference in a linear scalar
                        stochastic differential equation.
"sdv_multi_compact":    Compact version of sdv_multi
"sdv_multi":            Multivatiate SV model from Skaug
                        and Yu 2013, Comp. Stat & data
                        Analysis (to appear)
"socatt":               socatt from ADMB example
                        collection.
"spatial":              Spatial poisson GLMM on a grid,
                        with exponentially decaying
                        correlation function
"spde_aniso":           Anisotropic version of "spde.cpp".
"spde":                 Illustration SPDE/INLA approach to
                        spatial modelling via Matern
                        correlation function
"thetalog":             Theta logistic population model
                        from Pedersen et al 2012, Ecol.
                        Modelling.
"transform2":           Beta distributed random effects
                        using copulas.
"transform_parallel":   Parallel version of transform
"transform":            Gamma distributed random effects
                        using copulas.
"tweedie":              Estimating parameters in a Tweedie
                        distribution.
