# Hidden Markov Models and Sequential Monte Carlo Methods  
## Replication of *Fast Filtering with Large Option Panels*

This repository contains a replication project based on the paper:

**Arnaud Dufays, Kris Jacobs, Yuguo Liu, Jeroen Rombouts (2022)**  
*Fast Filtering with Large Option Panels: Implications for Asset Pricing*  
March 24, 2022

The objective is to replicate and compare several filtering and parameter estimation methods for the state-space model considered in the paper, using S&P 500 data, within the framework of the Hidden Markov Models and Sequential Monte Carlo Methods course at Ecole Polytechnique supervised by **Nicolas Chopin** (Ensae - Ip Paris) 

---

## Project objectives

The project is structured in successive steps:

1. **Stochastic Volatility with Correlated Jumps Model**

2. **Bootstrap Particle Filter**

3. **PMMH (Particle Marginal Metropolis–Hastings)**

4. **Comparison with Orthogonal MCMC**

To simplify the implementation, some parameters may be fixed in intermediate steps in order to reduce the dimensionality of the estimation problem.

---

## Data

- **S&P 500 data**, publicly available and easy to obtain online.
- Data sources and preprocessing steps are documented in the repository.
- Large raw datasets are not committed directly; scripts are provided to download and preprocess the data.

---

## Repository structure

Please refer to Bootstrap_PMMH.ipynb for our implementation of Bootstrap Particle Filter and PMMH (Particle Marginal Metropolis–Hastings).  \
Please refer to Orthogonal_mcmc_uniform_distribution.ipynb for our implementation of the O-MCMC (Orthogonal particle Markov Chain Monte Carlo) with random parameters.  \
We also did an implementation of the O-MCMC with parameters near to the ones find in the studied paper in Orthogonal_mcmc_normal_distribution.

Martin Boucher,
Alexandre Zenou,
Valentin Senaux 

Ecole Polytechnique
