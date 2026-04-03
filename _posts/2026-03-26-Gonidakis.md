---
layout:     post
title:      "Comparing Solar Structure Detection Methods in SDO/AIA Observations for Onboard Spacecraft Deployment"
subtitle:   "Panagiotis Gonidakis"
date:       2026-03-26 11:00:00
author:     "Centre for mathematical Plasma Astrophysics, KU Leuven, BE"
published:  true
---

## Abstract
Recent advances in solar physics increasingly rely on automated identification of coronal structures using machine learning. Yet most studies emphasise scientific performance without evaluating feasibility for onboard deployment to prioritise downlink observations. We investigate the automated identification of active regions and coronal holes by applying segmentation and detection techniques to Solar Dynamics Observatory (SDO) data. We compare three approaches: SCSS-Net, a deep learning model for semantic segmentation; YOLOv8n, a lightweight object detector; and a traditional pipeline based on basic computer vision operations (BCVO). Each method is assessed for its scientific accuracy and its suitability for deployment in future resource-limited missions. While no direct hardware benchmarking has been performed yet, we assess the feasibility of an onboard implementation based on the number of trainable parameters, the architecture, and the associated hardware requirements. Training and evaluation are first conducted on well-calibrated SDO images. We then extend the evaluation to raw and uncalibrated SDO images affected by instrumental artefacts. Performance is mainly measured using the Intersection over Union (IoU) and Dice score. Results show that while SCSS-Net achieves the highest segmentation quality, YOLOv8n offers a strong balance between accuracy and efficiency. The BCVO pipeline remains viable under strict hardware limitations. Interestingly, our models retain compatibility on Level-0 observations. This is the first study comparing these widely used methods from the perspective of onboard deployment. Our findings provide a foundation for designing frameworks tailored to onboard hardware configurations.

## Recorded video
[https://doi.org/10.6084/m9.figshare.31902859](https://doi.org/10.6084/m9.figshare.31902859.v1)

