---
layout:     post
title:      "Learning to Invert Solar Flares with RADYN Physics"
subtitle:   "by John Armstrong"
date:       2020-02-20 11:00:00
author:     "University of Glasgow"
#header-img: "img/im_2019-12-05-Murabito.jpg"
published:  true
---

## Abstract
During a solar flare, it is believed that reconnection takes place in the corona followed by fast energy transport to the chromosphere. The resulting intense heating strongly disturbs the chromospheric structure and induces complex radiation hydrodynamic effects. Interpreting the physics of the flaring solar atmosphere is one of the most challenging tasks in solar physics. We present a novel deep learning approach, an invertible neural network, to understanding the chromospheric physics of a flaring solar atmosphere via the inversion of observed solar line profiles in H&alpha; and Ca II &lambda;8542. The network is trained using flare simulations from the 1D radiation hydrodynamic code RADYN as the expected atmosphere and line profile. This model is then applied to whole images from an observation of an M1.1 solar flare taken with the Swedish 1 m Solar Telescope/CRisp Imaging SpectroPolarimeter instrument. The inverted atmospheres obtained from observations provide physical information on the electron number density, temperature and bulk velocity flow of the plasma throughout the solar atmosphere ranging in height from 0 to 10 Mm. Our method can invert a 1k x 1k field-of-view in approximately 30 minutes and we show results from the whole image inversions and error calculations on the inversions. Furthermore, we delve into the mammoth task of analysing the wealth of data we have accumulated through these inversions.
