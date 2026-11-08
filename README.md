# Explainable AI for Heart Disease Prediction

A Random Forest model that predicts heart disease, explained with SHAP, LIME and what-if analysis.
Built as a demo for a university Machine Learning module

## What it shows
- Training and evaluating a Random Forest (test accuracy 85%, 5-fold cross-validation about 81%)
- **SHAP (global):** which features matter most overall
- **SHAP (local):** why the model gave one patient 43% risk and another 99%
- **LIME:** a second method that agrees with SHAP on the same patient
- **What-if analysis:** how predicted risk changes when a value changes

## Run it
1. Open `xai_heart_disease.ipynb` in Google Colab.
2. Run all cells. The data loads from `processed.cleveland.data` if present, otherwise it is fetched from UCI.


## Dataset
Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). Heart Disease [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X

## Limitations
297 patients, data from the 1980s. This is an educational demo and is **not suitable for clinical use**.
