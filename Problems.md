# Introduction

# Model&Methods
alpha[1] ~ dunif(-1e-6, 1e-6)
alpha[i] ~ dnorm(alpha, variance)
alpha[i](country) + beta[i](year) + (inner product)
We treat each country as a cluster to build a hierarchical model
1. Residual analysis: Is it OK? Do we need knowledge in Lecture14?
2. Deal with the heavy-tailed distribution -- t prior? **How to choose degree of freedom**?
3. How to place prior, particularly the variance part? half-cauchy?
4. Variable selection -- latent variable and **col-linearity**
5. Model selection -- pseudo Bayes factor and DIC

# Data Analysis
4 figures and 2 tables (1 non-informative + 1 informative or 2 models)?
## Diagnostic


# Discussion

# References
