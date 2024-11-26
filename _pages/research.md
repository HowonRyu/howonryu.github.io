---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Physical activity recognition from accelerometer data using masekd autoencoder (MAE)
[<img src="/images/MAE.png" width="700"/>](/images/MAE.png)
* Theorized the effect of masking in transformer autoencoder model with multi-modality time-series inputs.
* Conducted experiments showcasing model performance in terms of model comparison, transfer learning with the pre-trained model, and ablation studies.
* Manuscript in preparation for conference submission: **Masked Autoencoder for Multi-modality Time-series input**


## Spatial confidence set on brain image (fMRI) data
[<img src="/images/confidenceset.png" width="500"/>](/images/confidenceset.png)
* Developed spatial confidence region framework for image data (fMRI) controlling for false discovery rate (Benjamini-Hochberg and two-step adaptive procedure).
* Conducted simulation and real data (HCP fMRI dataset) application for model validation and model performance.
demonstration with error rate control using Python NumPy
* Manuscript in preparation: **Spatial Confidence Regions for Excursion Sets with False Discovery Rate Control**


## Copy number signature GWAS with variational Bayes 
* Customized the zero-inflated variational Bayes model [(Ren 2023)](https://www.nature.com/articles/s42003-024-06504-y) which was originally designed for brain imaging data to fit the GWAS setting, achieving a tailored and optimized analysis pipeline for association analysis between genotypes and zero-inflated copy number signatures.
* Conducted batch run across SNPs on cluster computer, and performed simulation on valid threshold for coefficient effects.
