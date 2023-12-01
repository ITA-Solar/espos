---
layout:     post
title:      "A Bayesian approach to the drag-based modelling of ICMEs"
subtitle:   "Simone Chierichini"
date:       2023-12-14 11:00:00
author:     "Solar Physics and Space Plasma Research Centre, University of Sheffield, UK"
#header-img: "img/2023-12-14-Chierichini.jpg"
published:  true
---

## Abstract
Coronal Mass Ejections (CMEs) are huge clouds of magnetised plasma expelled from the solar corona that can travel towards the Earth and cause significant space weather effects.The Drag-Based Model (DBM) describes the propagation of CMEs in an ambient solar wind as analogous to an aerodynamic drag.The drag-based approximation is popular because it is a simple analytical model that depends only on two parameters, the drag parameter &gamma; and the solar wind speed _w_. DBM thus allows us to obtain reliable estimates of CME transit time at low computational cost.
Previous works proposed a probabilistic version of DBM, the Probabilistic Drag Based Model (P-DBM), which enables the evaluation of the uncertainties associated with the predictions.
In this work, we infer the "a-posteriori" probability distribution functions (PDFs) of the &gamma; and _w_ parameters of the DBM by exploiting a well-established Bayesian inference technique: the Monte Carlo Markov Chains (MCMC) method. By utilizing this Bayesian method through two different approaches, an ensemble and an individual approach, we obtain specific DBM parameter PDFs for two ensembles of CMEs: those travelling with fast and slow solar wind, respectively. Subsequently, we assess the operational applicability of the model by forecasting the arrival time of CMEs. While the ensemble approach displays notable limitations, the individual approach yields promising results, demonstrating competitive performances compared to the current state-of-the-art, with a mean absolute error (MAE) of 9.86 ± 4.07 hours achieved in the best-case scenario.
