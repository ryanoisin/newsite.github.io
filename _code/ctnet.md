---
title: "ctnet (R Package)"
excerpt: "Tools for Continuous-Time Dynamical Network Analysis. Github page: <https://github.com/ryanoisin/ctnet>"
collection: code
---

An `R` package to aid researchers in analyzing experience sampling data using a Continuous-Time Dynamical Network approach.
More details can be found in [Ryan, O., & Hamaker, E. L. (2021). Time to intervene: A continuous-time approach to network analysis and centrality. *Psychometrika*, 1-39.](https://link.springer.com/article/10.1007/s11336-021-09767-0)
The github page for this package can be found [here](https://github.com/ryanoisin/ctnet) 

The package takes either a drift matrix or estimated CT-VAR model object from the [`ctsem` package](https://github.com/cdriveraus/ctsem) and processes the output, allowing researchers to:
  - a) obtain estimated path-specific effects and centrality measures 
  - b) quantify the uncertainty around those measures in the form of confidence/credible intervals (depending on the procedure used to estimated the model with `ctsem`) 
  - c) to simulate interventions based on the estimated model
  - d) plot point estimates and credible intervals for different metrics as a function of the time-interval, as shown below
  
