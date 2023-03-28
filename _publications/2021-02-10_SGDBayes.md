---
title: "Is SGD a Bayesian Sampler?"
collection: publications
permalink: /publication/2021-SGDBayes
excerpt: 'This paper investigates how similar SGD trained networks are to their Gaussian Processes'
date: 2021-10-02
venue: 'JMLR'
citation: 'Mingard, Chris, et al. "Is SGD a Bayesian sampler? Well, almost." The Journal of Machine Learning Research 22.1 (2021): 3579-3642.'
---

Deep neural networks (DNNs) generalise remarkably well in the overparameterised
regime, suggesting a strong inductive bias towards functions with low generalisation error.
We empirically investigate this bias by calculating, for a range of architectures and datasets,
the probability $P_{SGD}(f\mid S)$ that an overparameterised DNN, trained with stochastic gradient
descent (SGD) or one of its variants, converges on a function f consistent with a training set
S. We also use Gaussian processes to estimate the Bayesian posterior probability $P_B(f\mid S)$
that the DNN expresses f upon random sampling of its parameters, conditioned on S.
Our main findings are that $P_{SGD}(f\mid S)$ correlates remarkably well with $P_B(f\mid S)$ and
that $P_B(f\mid S)$ is strongly biased towards low-error and low complexity functions. These
results imply that strong inductive bias in the parameter-function map (which determines
$P_{B}(f|S)$), rather than a special property of SGD, is the primary explanation for why DNNs
generalise so well in the overparameterised regime.
While our results suggest that the Bayesian posterior $P_B(f\mid S)$ is the first order determinant of $P_{SGD}(f\mid S)$, there remain second order differences that are sensitive to hyperparameter
tuning. A function probability picture, based on $P_{SGD}(f\mid S)$ and/or $P_B(f\mid S)$, can shed light
on the way that variations in architecture or hyperparameter settings such as batch size,
learning rate, and optimiser choice, affect DNN performance.
Keywords: stochastic gradient descent, Bayesian neural network

[Download paper here](http://c1510.github.io/files/SGDBayes.pdf)
