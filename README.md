# Lifestyle Prediction and Classification Project

This repository contains the final assessment for the **Machine Learning Basics** course at UniBo (Bioinformatics), focusing on predicting obesity levels through both binary and multi-class machine learning frameworks.

## Project Overview
The project explores the predictive capacity of lifestyle habits, physical conditions, and demographic factors on obesity classification. It is broken down into two main objectives:
1. **Binary Classification:** Evaluating whether an individual falls into an 'Obese' category using a comprehensive feature set versus testing whether family history alone is sufficient.
2. **Multi-Class Classification:** Accurately predicting granular obesity levels (`NObeyesdad`) based on behavioral and physiological attributes using a Random Forest architecture, alongside hyperparameter tuning analysis.

### Pipeline
> **pipeline**: import data > EDA > visualization > analytical decisions > data preprocessing > modeling > evaluation of the model > final results

## Key Findings
* **Binary Classification:** Achieved an exceptional **AUC of 0.97** with a multi-variable feature set. In contrast, a single-feature baseline relying strictly on family history yielded an **AUC of 0.65**, proving that isolated genetic/environmental risk factors are insufficient on their own for robust prediction.
* **Multi-Class Classification:** The Random Forest model achieved an overall accuracy of **0.83** (macro average: **0.84**). Misclassifications were predominantly isolated to adjacent, overlapping intermediate weight categories rather than structural model failures. Furthermore, hyperparameter tuning revealed that default parameters were already robustly optimized for the dataset.

## Tech Stack & Libraries Used
This project was implemented using Python and relies on the following libraries:
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- scikit-learn (`sklearn.preprocessing`, `sklearn.feature_selection`, `sklearn.model_selection`, `sklearn.ensemble`, `sklearn.metrics`, `sklearn.svm`, `sklearn.neighbors`)
- plotly

---
**© 2026 [Visani Alessia]. All rights reserved.**  
*This work was produced for the final assessment of the course in Machine Learning Basics at UniBo (Bioinformatics).*
