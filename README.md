# Time Series Machine Learning - Medical Equipment Sensor

*Predicting time series behavior for sensors in an equipment.*

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/matplotlib-%230078B5.svg?style=for-the-badge&logo=matplotlib&logoColor=white">
<img src="https://img.shields.io/badge/plotly-%23004DFF.svg?style=for-the-badge&logo=plotly&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/statsmodels-%23DC143C.svg?style=for-the-badge&logo=statsmodels&logoColor=white">
<img src="https://img.shields.io/badge/tensorflow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/keras-%23D00000.svg?style=for-the-badge&logo=keras&logoColor=white">
</div>

# 📖 Project

### 👨🏻‍🏫 Introduction

This project is a time series analysis and machine learning modeling to predict the levels of Helium and Bore temperature of a medical equipment. These two measures are essential to check the equipment safety and calibration.

The dataset contains five days of data with measurements distributed over time.

### 🎯 Goal

Explore and apply different machine learning models for time series prediction: Holt-Winters, ARIMA and RNNs.

### 📊 Results

Best performing models achieved an RMSE of **0.17** for Helium level and **7.46** for Bore temperature.

#### Visualizing results

![Results](references/results.png)

### 📈 Features

![Features](references/dataset.png)

# 🗺  Methodology

![Methodology](references/methodology.png)

# 🗄 Notebooks

- [1.0-eda.ipynb](notebooks/1.0-eda.ipynb)
- [2.0-ml_modeling.ipynb](notebooks/2.0-ml_modeling.ipynb)

# 📦 Folder Structure

    ├── LICENSE
    ├── poetry.lock        <- file with poetry packages from the environment
    ├── pyproject.toml     <- file with poetry specifications for the project environment
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         and a short `-` delimited description, e.g.
    │                         `1.0-initial-data-exploration`.
    │
    ├── references         <- Figures, manuals, and all other explanatory materials.
