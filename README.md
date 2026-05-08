# NBA Shot Prediction

**Predicting NBA Shot Outcomes (Made/Missed) using Spatial + Player Biometric Data (2004–2024)**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-5C2D91?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Team Members
- Ryan Styron
- Harman Aujla
- Joseph Fodera
- Matthew Voynovich


---

## Overview

This project develops and evaluates machine learning and deep learning models to predict whether an NBA shot will be made or missed. We combine comprehensive shot context data (location, game time, shot type, etc.) with player biometric attributes (height, weight, age) across **20 NBA seasons (2004–2024)**.

**Key Highlights:**
- Highest test accuracy: **62.2%** (custom PyTorch Neural Network — ShotNet)
- Extensive temporal analysis showing surprising stability across eras (minimal recency bias)
- Novel integration of player biometrics with spatial shot data
- Full reproducibility with public datasets and code

**[Read the Full Paper →](https://github.com/RyanStyron/NBAShotPredictor/blob/main/docs/NBA-Shot-Prediction-Report.pdf)**

---

## Repository Contents

- `shot_prediction_models.ipynb` — Main modeling pipeline (data processing, EDA, all models, temporal analysis)
- `nba_api_pull_overview.ipynb` — Biometric data retrieval using `nba_api`
- `NBA_Shot_Prediction.pdf` — Full research paper (conference format)
- Data processing and feature engineering scripts




