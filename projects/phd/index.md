---
author: <b>Edward Gunning</b>
Status: Published
date: 2023-11-17 00:00:00+00:00
slug: phd
title: Statistical Modelling of Second-Generation Functional Data with Application in Biomechanics and Human Movement Research
status: Published
categories: PhD thesis
# file: PhDThesis.pdf
details: "PhD thesis, University of Limerick"
tag:
- functional data analysis
---

In recent years, the data being collected in human movement biomechanics have increased in size and complexity.
Improvements in data acquisition and processing mean that more data can be recorded and extracted for each individual, producing datasets of increased volume that are multivariate in nature and exhibit complex dependence structures due to repeated measurements.

Functional data analysis is a branch of statistics that is well suited to the analysis of continuous biomechanical data, e.g., kinematics or kinetics that are recorded throughout a movement, because it treats the measured data streams as smooth, time-varying functions.
Traditional functional data analysis tools have been developed for independent, univariate samples of functional data, so they are not flexible enough to fully leverage the richness of modern biomechanical datasets.
There is a growing need to adapt and extend these tools to modern data structures and characteristics.
To address this challenge, this thesis develops new statistical approaches for structured functional data, as motivated by a large study on running-related injuries, where kinematic data from recreational runners were captured during a treadmill run with the goal of understanding running technique and its links to injury.
The motivating biomechanical dataset is rich in size and structure as it contains repeated measurements of multiple kinematic variables from a large number of individuals. Thus, it presents methodological and computational challenges and facilitates the development of novel statistical methodology that is generally applicable in a variety of fields.

The first challenge addressed in this thesis is the development of multivariate functional mixed effects modelling techniques, to allow the kinematic data from multiple body parts (e.g., hip and knee) to be analysed simultaneously.
The mixed effects modelling framework readily incorporates covariate information and facilitates appropriate modelling of the complex dependence structure between observations from each individual (i.e., each individual has multiple repetitions of the movement/strides, measurements are made on both sides of the body). 
This work is divided into two sequential contributions.
Firstly, a multivariate functional mixed effects model is developed for a subset of the motivating dataset, which contains average hip angle and knee angle curves for each individual on either side of the body.
As the second contribution, the modelling framework is extended to handle the full collection of strides in the motivating dataset, resulting in a multivariate multilevel longitudinal functional model which uses a longitudinal functional data analysis approach to capture temporal dependence among the adjacent strides.

The second challenge addressed in this thesis is the estimation of continuous-time ordinary differential equations from functional data.
A re-formulation of Principal Differential Analysis, a classical technique for estimating differential equations from functional data, is developed.
The new formulation is based on a generative statistical model, providing a better understanding of the technique from a statistical perspective and broadening its applicability.
The methodology is demonstrated on simulated data from ordinary differential equation models and on a subset of kinematic data from the motivating dataset for this thesis.