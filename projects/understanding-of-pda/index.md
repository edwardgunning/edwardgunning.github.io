---
title: "An Understanding of Principal Differential Analysis"
date: "2024-06-27"
author: <b>Edward Gunning</b>, Giles Hooker
arxiv: 
github: edwardgunning/UnderstandingOfPDAManuscript
categories: Working papers
---

In functional data analysis, replicate observations of a smooth functional process and its derivatives offer a unique opportunity to flexibly estimate continuous-time ordinary differential equation models.
Ramsay (1996) first proposed to estimate a linear ordinary differential equation from functional data in a technique called Principal Differential Analysis, by formulating a functional regression in which the highest-order derivative of a function is modelled as a time-varying linear combination of its lower-order derivatives. 
Principal Differential Analysis was introduced as a technique for data reduction and representation, using solutions of the estimated differential equation as a basis to represent the functional data.
In this work, we re-formulate PDA as a generative statistical model in which functional observations arise as solutions of a deterministic ODE that is forced by a smooth random error process.
This viewpoint defines a flexible class of functional models based on differential equations and leads to an improved understanding and characterisation of the sources of variability in Principal Differential Analysis.
It does, however, result in parameter estimates that can be heavily biased under the standard estimation approach of PDA. Therefore, we introduce an iterative bias-reduction algorithm that can be applied to improve parameter estimates.
We also examine the utility of our approach when the form of the deterministic part of the differential equation is unknown and possibly non-linear, where Principal Differential Analysis is treated as an approximate model based on time-varying linearisation.
We demonstrate our approach on simulated data from linear and non-linear differential equations and on real data from human movement biomechanics.
Supplementary `R` code for this manuscript is available at [https://github.com/edwardgunning/UnderstandingOfPDAManuscript](https://github.com/edwardgunning/UnderstandingOfPDAManuscript).
