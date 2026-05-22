# 🎙️ Predict Podcast Listening Time

Machine Learning Regression project built for the 2025 Kaggle Playground Series - Season 5, Episode 4 to predict the listening duration of podcast episodes.

### 🚀 Live Demo
Test the model here: [Podcast Listening Time Prediction App](https://huggingface.co/spaces/bdaser/Podcast)

### 📌 Problem
Predict the listening time of a podcast episode based on attributes like genre, host/guest popularity, and metadata.

### 📊 Dataset
* 750,000 training entries
* 250,000 test entries
* Mixed features: Categorical (Genre, Publication day/time) and Numerical (Host/Guest popularity, Episode length)

### ⚙️ Workflow
* **Data Preprocessing & Cleaning**: 
    * Systematic handling of missing values across multiple features to ensure data integrity.
    * Statistical imputation techniques applied to resolve gaps in key demographic and episode-specific attributes.
    * Utilization of linear correlations between variables to accurately estimate and fill missing values, enhancing model input quality.
* **Model Comparison**: Evaluated multiple regressors including Gradient Boosting, CatBoost, XGBoost, and LGBM.
* **Optimization**: Targeted RMSE minimization.

### 🏆 Best Model
* **LGBMRegressor**
* **R-Squared:** 0.869732
* **RMSE:** 9.790526
* **MAE:** 7.394434
