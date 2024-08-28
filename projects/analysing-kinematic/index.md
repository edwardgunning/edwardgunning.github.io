---
title: "Analysing kinematic data from recreational runners using functional data analysis"
date: "2024-08-15"
author: <b>Edward Gunning</b>, Steven Golovkine, Andrew J. Simpkin, Aoife Burke, Sarah Dillon, Shane Gore, Kieran Moran, Siobhan O'Connor, Enda Whyte, Norma Bargary
arxiv: 2408.08200
github: edwardgunning/RISC1-fda-manuscript-01-code
categories: Working papers
---

We present a multivariate functional mixed effects model for kinematic data from a large number of recreational runners. The runners' sagittal plane hip and knee angles are modelled jointly as a bivariate function with random effects functions used to account for the dependence among measurements from either side of the body. The model is fitted by first applying multivariate functional principal component analysis (mv-FPCA) and then modelling the mv-FPCA scores using scalar linear mixed effects models. Simulation and bootstrap approaches are introduced to construct simultaneous confidence bands for the fixed effects functions, and covariance functions are reconstructed to summarise the variability structure in the data and thoroughly investigate the suitability of the proposed model. In our scientific application, we observe a statistically significant effect of running speed on both the hip and knee angles. We also observe strong within-subject correlations, reflecting the highly idiosyncratic nature of running technique. Our approach is more generally applicable to modelling multiple streams of smooth kinematic or kinetic data measured repeatedly for multiple subjects in complex experimental designs.
