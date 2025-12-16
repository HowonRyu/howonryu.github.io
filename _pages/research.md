---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Physical activity recognition from accelerometer data using masekd autoencoder (MAE)
* Self-supervised learning framework for physical activity classification with wearable device data input (MoCA) using transformer-based masked autoencoder model.
* Physical activity classification from accelerometer and gyroscope time series inputs using Masked Autoencoder model.
* Conducted experiments showcasing model performance over baseline models, transfer learning with the pre-trained model, and ablation studies.
* [[preprint]](https://arxiv.org/abs/2506.02260)
* [[code]](https://github.com/HowonRyu/MoCA)
<p align="center">
    <img src="/images/MAE.png" alt="MAE" style="width: 80%;">
</p>


## Spatial confidence set on brain image (fMRI) data
* Developed spatial confidence region framework for image data (fMRI) controlling for false discovery rate (Benjamini-Hochberg and two-step adaptive procedure).
* Conducted simulation and real data (HCP fMRI dataset) application for model validation and model performance.
demonstration with error rate control.
* [[preprint]](https://arxiv.org/abs/2504.13124)
* [[code]](https://github.com/HowonRyu/ConfidenceSet)
<p align="center">
    <img src="/images/confidenceset.png" alt="confset" style="width: 70%;">
</p>


## Step measurement and gait feature recognition from inertial measurement unit inputs.
* Parkinson's disease severity detection model with wearable device data (triaxial IMUs) input.
* Identified important kinetic and gait features and developed [step measurement](https://zenodo.org/records/17253807) model to derive gait features. 
<embed src="{{ '/files/IMU_poster.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px" />


## Sedentary behavior intervention effect measurement through wearable sensors
* Sedentary behavior recognition model on a clinical trials dataset (RISE for Health) to produce labels to replace activPAL
* Mixed effects model to compare intervention effects between different activity recognition algorithms
<p align="center">
    <img src="/images/RISE_1.png" alt="RISE" style="width: 80%;">
</p>
