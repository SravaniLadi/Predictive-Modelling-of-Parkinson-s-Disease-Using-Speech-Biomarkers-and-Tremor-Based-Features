# Predictive-Modelling-of-Parkinson-s-Disease-Using-Speech-Biomarkers-and-Tremor-Based-Features
Multimodal machine learning framework for early Parkinson’s Disease prediction using speech biomarkers and hand tremor features with ensemble learning and deep learning models.
## Overview
This project presents a multimodal machine learning framework for early prediction of Parkinson’s Disease by combining speech biomarkers and hand tremor features.

Traditional Parkinson’s detection methods often rely on clinical diagnosis after visible symptom progression. This project aims to support earlier, non-invasive, and cost-effective screening by integrating voice-based acoustic measurements with tremor-related motor features.

The system performs:
- Data preprocessing and missing value handling
- Label encoding and feature scaling
- Multimodal feature fusion of voice and tremor datasets
- Training of multiple machine learning models
- Ensemble learning using Voting Classifier
- Deep learning model implementation
- Model evaluation and visualization

## Features
- Voice biomarker analysis
- Hand tremor feature analysis
- Feature importance visualization
- ROC curve generation
- Confusion matrix analysis
- Performance comparison across models

## Algorithms Used
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Voting Ensemble Classifier
- Multi-Layer Perceptron (Deep Learning)

## Dataset Information
The combined dataset contains:
- 563 samples
- 41 total features
- Voice features: jitter, shimmer, HNR, RPDE, DFA, PPE, spread1, spread2
- Tremor features: RMS, MRT, MAX_HT, MIN_HT, STD_HT

## Results
Best model performance:
- Accuracy: 99.11%
- AUC Score: 1.0000

Top performing models:
- XGBoost
- CatBoost
- Voting Ensemble

## Project Structure
```bash
Parkinson-Disease-Prediction/
│── PD.ipynb
│── project.ipynb
│── PD_Paper.pdf
│── README.md
```

## Applications
- Early Parkinson’s Disease screening
- Clinical decision support systems
- Remote patient monitoring
- AI-based healthcare analytics

## Future Scope
- Integration of gait analysis
- Handwriting analysis
- Web/mobile deployment
- Real-time monitoring system
- Explainable AI integration
