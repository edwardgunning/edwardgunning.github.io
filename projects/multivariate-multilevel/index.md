---
title: "A Multivariate Multilevel Longitudinal Functional Model for Repeatedly Observed Human Movement Data"
date: "2024-08-16"
author: <b>Edward Gunning</b>, Steven Golovkine, Andrew J. Simpkin, Aoife Burke, Sarah Dillon, Shane Gore, Kieran Moran, Siobhan O'Connor, Enda Whyte, Norma Bargary
arxiv: 2408.08481 
github: edwardgunning/RISC1-longitudinal-manuscript-code
categories: Working papers
---

Biomechanics and human movement research often involves measuring multiple kinematic or kinetic variables regularly throughout a movement, yielding data that present as smooth, multivariate, time-varying curves and are naturally amenable to functional data analysis. It is now increasingly common to record the same movement repeatedly for each individual, resulting in curves that are serially correlated and can be viewed as longitudinal functional data. We present a new approach for modelling multivariate multilevel longitudinal functional data, with application to kinematic data from recreational runners collected during a treadmill run. For each stride, the runners' hip, knee and ankle angles are modelled jointly as smooth multivariate functions that depend on subject-specific covariates. Longitudinally varying multivariate functional random effects are used to capture the dependence among adjacent strides and changes in the multivariate functions over the course of the treadmill run. A basis modelling approach is adopted to fit the model -- we represent each observation using a multivariate functional principal components basis and model the basis coefficients using scalar longitudinal mixed effects models. The predicted random effects are used to understand and visualise changes in the multivariate functional data over the course of the treadmill run. In our application, our method quantifies the effects of scalar covariates on the multivariate functional data, revealing a statistically significant effect of running speed at the hip, knee and ankle joints. Analysis of the predicted random effects reveals that individuals' kinematics are generally stable but certain individuals who exhibit strong changes during the run can also be identified. A simulation study is presented to demonstrate the efficacy of the proposed methodology under realistic data-generating scenarios.


