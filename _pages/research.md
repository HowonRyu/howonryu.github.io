---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Physical activity recognition from accelerometer data using masekd autoencoder (MAE)
<p align="center">
    <img src="/images/MAE.png" alt="MAE" style="width: 80%;">
</p>

* Theorized the effect of masking in transformer autoencoder model with multi-modality time-series inputs.
* Conducted experiments showcasing model performance in terms of model comparison, transfer learning with the pre-trained model, and ablation studies. (Pytorch)
* ICML 2025 submission: **MoCA: Multi-modal Cross-masked Autoencoder for Digital Health Measurements**




## Spatial confidence set on brain image (fMRI) data
<p align="center">
    <img src="/images/confidenceset.png" alt="confset" style="width: 60%;">
</p>

* Developed spatial confidence region framework for image data (fMRI) controlling for false discovery rate (Benjamini-Hochberg and two-step adaptive procedure).
* Conducted simulation and real data (HCP fMRI dataset) application for model validation and model performance.
demonstration with error rate control using Python NumPy
* Manuscript in preparation: **Spatial Confidence Regions for Excursion Sets with False Discovery Rate Control**


## Inertial Measurement Unit Input and step and gait feature recognition
* Parkinson's disease severity detection model with wearable device data (triaxial IMUs) input.
* Identifying important kinetic and gait features.
* Extensive literature review on the use of physiological signals from wearable devices for Parkinson's disease (PD) and machine learning methodologies.



## Copy number signature GWAS with variational Bayes 
* Customized the zero-inflated variational Bayes model [(Ren 2023)](https://www.nature.com/articles/s42003-024-06504-y) which was originally designed for brain imaging data to fit the GWAS setting, achieving a tailored and optimized analysis pipeline for association analysis between genotypes and zero-inflated copy number signatures.
* Conducted batch run across SNPs on cluster computer, and performed simulation on valid threshold for coefficient effects.
