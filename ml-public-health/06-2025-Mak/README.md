# PEDIL-Forge: Machine Learning for Public Health – Diabetes Prediction

Welcome to the official repository for the **Day 2 session** of the **PEDIL-Forge Workshop on ML for Public Health**, hosted by the Population and Epidemiology Data Innovation Lab (PEDIL) on 06-2025 at Makerere. This hands-on module introduces participants to applied machine learning using real-world data from the CDC's Behavioral Risk Factor Surveillance System (BRFSS), focusing on predicting **diabetes** risk.

---

## Overview

This workshop equips learners with practical skills to:

- Load and preprocess large public health datasets
- Handle class imbalance in health outcomes
- Build and evaluate classification models
- Interpret model predictions using SHAP and partial dependence plots
- Apply best practices in feature selection and tuning

The emphasis is on **applied learning**, reproducibility, and the responsible use of machine learning in epidemiology.

---

## Dataset

We use a subset of the **2011 BRFSS dataset**, publicly available from the [CDC](https://www.cdc.gov/brfss/index.html), focusing on key predictors such as:

- Age, Sex, BMI
- Income and Education
- Smoking and Physical Activity

The target variable is `DIABETE3`, indicating whether a respondent has been diagnosed with diabetes.

---

## Files Included

| File | Description |
|------|-------------|
| `PEDIL_Forge_Day2_Diabetes_Rebuilt.ipynb` | Main Colab notebook used in the live session |
| `brfss_diabetes_clean.csv` | Cleaned subset of the BRFSS dataset |
| `PEDIL_Forge_Day2_Student_Notebook.ipynb` | Minimal version for student hands-on practice |
| `model_outputs/` | Folder for saved models and visualizations (optional) |

---

## How to Use

1. Open the main notebook in [Google Colab](https://colab.research.google.com/)  
   [Click here to launch](https://colab.research.google.com/github/drdmakau/PEDIL-Forge/blob/main/ml-public-health/06-2025-Mak/PEDIL_Forge_Day2_Diabetes_Rebuilt.ipynb)

2. Run cells step by step as guided. Code comments and markdown cells provide context.

3. Optionally, use the student version for independent practice.

---

## Learning Objectives

By the end of this module, participants will be able to:

- Apply machine learning methods to a public health dataset
- Recognize and mitigate bias from class imbalance
- Interpret model results using SHAP and Partial Dependence
- Export trained models and insights for reuse

---

## Feedback & Contribution

Feedback or ideas?  
Please open an [issue](https://github.com/drdmakau/PEDIL-Forge/issues) or [pull request](https://github.com/drdmakau/PEDIL-Forge/pulls).

We welcome collaboration on extending this module to additional health outcomes!

---

## License

This repository is shared for educational purposes under the MIT License. Please credit **PEDIL** if reusing materials.

