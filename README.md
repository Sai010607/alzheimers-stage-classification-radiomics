# Alzheimer's Stage Classification using Radiomics

## Overview

This project presents a machine learning framework for Alzheimer's disease stage classification using MRI-derived radiomic features.

The framework classifies subjects into five stages:

- Normal
- EMCI (Early Mild Cognitive Impairment)
- MCI (Mild Cognitive Impairment)
- LMCI (Late Mild Cognitive Impairment)
- AD (Alzheimer's Disease)

## Dataset

- Total Subjects: 2500
- Classes: 5
- Radiomic Features: 56
- Balanced Dataset (500 subjects per class)

## Models

- Random Forest
- XGBoost

## Results

| Model | Test Accuracy | Cross Validation Accuracy |
|---------|---------|---------|
| Random Forest | 97.4% | 94.2% |
| XGBoost | 98.0% | 96.24% |

## Key Findings

- XGBoost achieved the highest classification performance.
- LMCI and Normal subjects were classified with near-perfect accuracy.
- Most classification errors occurred between MCI and AD stages.
- Radiomic features demonstrated strong discriminative power for disease staging.

## Future Work

- ROI-wise feature contribution analysis
- SHAP explainability
- MRI image-to-stage prediction pipeline
- Deep learning model comparison
