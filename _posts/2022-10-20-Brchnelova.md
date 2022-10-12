---
layout:     post
title:      "Coronal modelling: the good, the bad and the ugly"
subtitle:   "Michaela Brchnelova"
date:       2022-10-20 11:00:00
author:     "KU Leuven, Belgium"
#header-img: "img/2022-10-20-Brchnelova.jpg"
published:  true
---

## Abstract
Space weather forecasting is a complex problem which involves modeling of the solar plasma all the way from the solar corona down to the Earth’s atmosphere. To simulate this energy transfer, a cascade of various models is required, such as the coronal model, the heliospheric model and various models to estimate the Kp and Dst indices. European efforts to create such a framework of connected tools have resulted in the launch of the Virtual Space Weather Modeling Center (VSWMC) (Poedts et al., 2019) - a platform we will briefly introduce in the beginning of this talk. 
One of the biggest sources of errors in this framework has been the semi-empirical coronal WSA model so far applied to predict the plasma conditions at 0.1AU. Thus, over the last few years, our department has been developing a new coronal model COCONUT (Perri & Leitner et al., 2022). However, despite this model having been for years in development, it still suffers from several limitations constraining its accuracy, just like many other state-of-art coronal models do. These limitations frequently stem from assumptions which have to be made on the boundaries of the domain, approximations regarding the physics applied and the general lack of methods of validation (Perri et al. 2022). The ways in which we are trying to overcome some of these obstacles while keeping the code robust and fast will be addressed in this talk. We will also point at the areas where much development and work are still needed and will be very grateful to receive feedback and further suggestions from the community.
