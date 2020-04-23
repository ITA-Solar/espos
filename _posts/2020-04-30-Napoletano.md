---
layout:     post
title:      "On the parameters of Drag-Based ensemble models"
subtitle:   "by Gianluca Napoletano"
date:       2020-04-30 11:00:00
author:     "University of Rome Tor Vergata"
#header-img: "img/im_2020-04-30-Napoletano.jpg"
published:  true
---

## Abstract
ICMEs (Interplanetary Coronal Mass Ejections) are violent phenomena of solar activity that affect large regions of the heliosphere. The prediction of their impact on the Earth and other solar system bodies is one of the primary goals of the planetary space weather forecasting. The travel time of an ICME from the Sun to the Earth can be computed through the Drag-Based Model (DBM). A DBM is based on a simple equation of motion for the ICME defining its acceleration as a=-Γ(v-w)|v-w|, where a and v are the CME acceleration and speed, w is the ambient solar-wind speed and Γ is the so-called drag parameter (Vršnak et al., 2013). To run the codes, forecasters use empirical input values for Γ and w, derived by pre-existent knowledge of solar wind. In the 'Ensemble' approaches (Dumbovich et al., 2018; Napoletano et al. 2018), the uncertainty about the actual values of such inputs are rendered by Probability Distribution Functions (PDFs), accounting for their variability and our lack of knowledge. Employing a list of past ICME events, for which initial conditions when leaving the Sun and arrival conditions at the Earth are known, we apply a statistical approach to the DBM to determine a measure of Γ and w for each case. This allows to obtain distributions for the model parameters on an experimental basis and to test whether different conditions of relative velocity to the solar wind influence the value of the drag efficiency. This is a promising approach when considering the extremely short computation time needed by the model to propagate ICMEs, to forecast ICME arrival to planetary bodies or spacecraft in the whole heliosphere, with relevant application to space-mission short-term planning.
