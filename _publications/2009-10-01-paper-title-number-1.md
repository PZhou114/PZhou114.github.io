---
title: "M3R thesis: sampling from log-concave distributions through MCMC methods"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper and presentation comprise my M3R undergraduate project thesis and the accompanying slides for my final year.'
date: 2024-06-10
venue: 'Journal 1'
slidesurl: 'http://PZhou114.github.io/files/M3R_Presentation.pdf'
paperurl: 'http://PZhou114.github.io/files/M3R_Thesis.pdf'
citation: 'Peiyi Zhou. (2024). &quot;Sampling from log-concave distributions through MCMC methods.'
---

This report aims to discuss the behaviour of Markov Chain Monte Carlo (MCMC) methods for dealing with sampling problems, involving (i) the implementation of unadjusted Langevin algorithm derived from overdamped Langevin stochastic differential equation, and (ii) underdamped Langevin samplers derived from underdamped Langevin stochastic differential equation, with two different discretisations. For visualisation and evaluation of each algorithm’s sampling performance, we focus on analysing the behaviour for sampling from the 1D Gaussian distributions, as an example of a log-concave distribution, which will be used as the target distribution throughout this report. Particularly, we will derive analytic expressions for the stationary distributions of these discretisations, some of which are known in the literature whereas some are not. Of particular importance are the stationary distributions of underdamped Langevin algorithms, which are not given as examples in the literature before, which we find important to derive. We will also discuss the convergence properties of these algorithms.
