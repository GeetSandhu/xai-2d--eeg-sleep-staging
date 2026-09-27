# XAI for EEG Sleep Staging Across Healthy and OSA Severity Cohorts

This repository contains the source code for the paper:

**"Towards Explainable Sleep Stage Classification using Single-Channel Electroencephalogram"**  
*AgIA4BioHealth Workshop, IEEE BIBM 2026, Dallas, USA*

## Overview
This work extends the SleepXAI framework (Dutt et al., 2023) by evaluating five gradient-based XAI attribution methods across four OSA severity groups using the DREAMT dataset.

## Methods Evaluated
- Modified Grad-CAM
- Vanilla Saliency
- DeepLIFT
- SHAP GradientExplainer
- Integrated Gradients (IG)

## Datasets
- Sleep-EDF (publicly available on PhysioNet)
- DREAMT (available on PhysioNet under restricted access)

## Requirements
- Python 3.8+
- PyTorch
- Captum
- NumPy, SciPy, Pandas, Matplotlib

## Citation
If you use this code, please cite our paper:
[Citation to be added upon publication]

## Acknowledgment
This work was supported in part by the NSF AI Institute for Foundations of Machine Learning (IFML).
