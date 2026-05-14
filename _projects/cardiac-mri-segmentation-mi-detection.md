---
layout: page
title: Cardiac MRI Segmentation and Myocardial Infarction Detection
description: Deep learning pipelines for LGE-MRI segmentation, classification, and explainability.
img: assets/img/cardiac_mri_project.jpg
importance: 1
category: medical imaging ai
related_publications: false
---

## Overview

This project focused on late gadolinium enhancement cardiac MRI analysis, including segmentation, myocardial infarction identification, inference, native-space evaluation, and explainability using Grad-CAM.

## Problem

Cardiac MRI provides rich structural and tissue-characterisation information, but manual analysis can be time-consuming and requires specialist expertise. Automated segmentation and classification methods can support more scalable and reproducible assessment.

## Approach

I developed deep learning workflows covering preprocessing, model training, validation, inference, and structured evaluation. The work included segmentation and classification experiments using cardiac MRI data, with emphasis on reproducibility and clinically meaningful interpretation.

## Technical contributions

- Built end-to-end training and inference workflows for cardiac MRI analysis.
- Developed segmentation and classification experiments using deep learning models.
- Evaluated model performance using clinically relevant metrics.
- Applied Grad-CAM to assess whether classification models attended to plausible anatomical regions.
- Considered processed-space and native-space evaluation to reduce geometry-related errors.

## Tools and methods

Python, PyTorch, MONAI, SimpleITK, NumPy, pandas, scikit-learn, Matplotlib, Grad-CAM, Dice, HD95, AUC, sensitivity, specificity, F1-score.

## Code

[GitHub repository](https://github.com/HenryOn2021/LGE_MRI_Myocardium_Segmentation_and_Myocardial_Infarction_Classification)

## Relevance

This project demonstrates my ability to build reproducible AI pipelines for complex medical imaging data, from preprocessing and model development to validation, interpretation, and reporting.
