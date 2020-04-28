# STA360project: Stop and Frisk Data
## Authors: Cindy Wang, Evelyn Yun, Lynn Fan
Dataset on arrests during the Stop and Frisk policy in NYC

Does the New York City Police Department (NYPD) stop pedestrians of some races disproportionately, relative to the racial distribution of NYC?
the conditional probability of being arrested given each race

to model proportion of stops and predict proportion of stops in different precincts (precinct based on black population percentage)

## Hypothesis 
Police stop pedestrians based solely on past arrest rate in different racial groups, controlling for precinct and crime type

## Prior
last year's arrest rate as prior?

## Model
If variance inflated -> negative binomial instead of Poisson
If missing predictor -> inflated variance
if variance >> mean, can we conclude that the variance is inflated?
Should we use overdispersed Poisson instead of Negative Binomial when we observe inflated variance?

why do we use metropolis within gibbs?

optimal acceptance ratio: 25%-50%

## Sampling
How do we do negative binomial regression inside MCMC?
Metropolis?
Why don't we use MCMC instead
How do we get predictive?
