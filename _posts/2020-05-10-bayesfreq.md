---
layout: post
title: Bayesian vs Frequentist ideology. 
comments: true
---
Bayesian: The rationale behind using a bayesian framework is not only the Bayes update rule or the availability of (subjective)prior if any exists, but is mainly due to marginalization and conditioning(of unknown on the known), which drive the modeling process in a Bayesian framework.

The unknown parameters are treated as random variables and are jointly modeled with the known data--any uncertainty associated with unknown parameters is taken into account over here; the posterior distribution of unknown parameters conditioned on known data is determined, and wherever required the distribution of parameters are acquired by marginalizing appropriately.

In addition, with hierarchical modeling, we can incorporate uncertainty associated with hyperparameters, too.

Frequentists: On the other hand, Frequentists model the unknown parameters(treating as just unknown values and not random variables) conditioned on the known data; although frequentists condition the unknown parameters on known data they do not consider any uncertainty associated with the unknown parameters while modeling, unlike Bayesians, which is achieved by considering the distribution of the parameters while modeling implying unknown parameters as Random Variables rather than just unknown.

This difference of whether or not to consider the uncertainty of parameters(distribution vs just value) lies at the root cause of dissension between the two ideologies.
