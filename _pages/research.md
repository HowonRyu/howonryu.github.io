---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Physical activity recognition from accelerometer data using masekd autoencoder (MAE)
* Self-supervised learning framework for physical activity classification with wearable device data input (MoCA) using transformer-based masked autoencoder model.
* Physical activity classification from accelerometer and gyroscope time series inputs using Masked Autoencoder model.
* Conducted experiments showcasing model performance over baseline models, transfer learning with the pre-trained model, and ablation studies. (PyTorch)
* [[preprint]](https://arxiv.org/abs/2506.02260)
* [[code]](https://github.com/HowonRyu/MoCA)
<p align="center">
    <img src="/images/MAE.png" alt="MAE" style="width: 80%;">
</p>


## Spatial confidence set on brain image (fMRI) data
* Developed spatial confidence region framework for image data (fMRI) controlling for false discovery rate (Benjamini-Hochberg and two-step adaptive procedure).
* Conducted simulation and real data (HCP fMRI dataset) application for model validation and model performance.
demonstration with error rate control (NumPy)
* [[preprint]](https://arxiv.org/abs/2504.13124)
* [[code]](https://github.com/HowonRyu/ConfidenceSet)
<p align="center">
    <img src="/images/confidenceset.png" alt="confset" style="width: 70%;">
</p>


## Step measurement and gait feature recognition from inertial measurement unit inputs.
* Parkinson's disease severity detection model with wearable device data (triaxial IMUs) input.
* Identified important kinetic and gait features and developed step measurement model to derive gait features. (PyTorch)
* [[link]](https://zenodo.org/records/17178619)



## Copy number signature GWAS with variational Bayes 
* Customized the zero-inflated variational Bayes model [(Ren 2023)](https://www.nature.com/articles/s42003-024-06504-y) which was originally designed for brain imaging data to fit the GWAS setting, achieving a tailored and optimized analysis pipeline for association analysis between genotypes and zero-inflated copy number signatures.
* Conducted batch run across SNPs on cluster computer, and performed simulation on valid threshold for coefficient effects.
