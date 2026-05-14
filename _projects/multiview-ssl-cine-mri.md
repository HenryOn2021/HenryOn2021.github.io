---
layout: page
title: Multi-view Self-supervised Learning for Cine Cardiac MRI
description: Representation learning from complementary long-axis cardiac MRI views.
img: assets/img/multiview_ssl_project.jpg
importance: 3
category: self-supervised learning
related_publications: false
---

## Overview

This project explored self-supervised and multi-view representation learning for cardiac cine MRI, using complementary long-axis views to learn patient-level representations for downstream disease classification.

## Problem

Labelled medical imaging datasets are often limited, while unlabelled imaging data may be more available. Self-supervised learning can help learn useful representations before downstream fine-tuning, particularly in limited-labelled-data settings.

## Approach

The project investigated contrastive and multi-view learning strategies using cine MRI views from the same subject as related views of the same underlying cardiac phenotype.

## Technical contributions

- Designed multi-view representation learning experiments for cine MRI.
- Explored within-subject view relationships as a source of self-supervised signal.
- Developed staged pretraining and fine-tuning workflows.
- Considered domain shift between large-scale healthy-biased datasets and clinical downstream cohorts.
- Used offline diagnostics to assess whether learned representations captured meaningful view-level and subject-level structure.

## Tools and methods

Python, PyTorch, MONAI, NumPy, pandas, TensorBoard, contrastive learning, self-supervised learning, transfer learning, multi-view learning.

## Code

[GitHub repository](https://github.com/HenryOn2021/Multi_Long_Axis_View_CineMRI_Mitral_Regurgitation_Classification)

## Relevance

This project demonstrates my interest in modern representation learning methods and their use in clinically realistic limited-labelled-data settings.
