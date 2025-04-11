# 🌾 Soil Moisture Estimation using SAR and Machine Learning

A data-driven pipeline for estimating soil moisture by combining Synthetic Aperture Radar (SAR) data and ground truth observations, using machine learning models and geospatial analysis.

---

## 🔍 Project Overview

1. **SAR Data Preprocessing**: Acquire and process Sentinel-1 SAR imagery.
2. **Backscatter Extraction**: Extract VV backscatter coefficients using **Google Earth Engine (GEE)**.
3. **Data Fusion**: Combine SAR features with ground truth soil moisture data.
4. **Machine Learning**: Train regression models to predict soil moisture.
5. **Spatial Mapping**: Generate continuous soil moisture maps using interpolation techniques(IDW) in **ArcGIS Pro**.

---

## 🧰 Tools & Technologies

- 🛰️ **Google Earth Engine** (for SAR data extraction)
- 🐍 **Python** (for preprocessing and model training)
- 🤖 **Scikit-learn** / **Decision tree** / **Random Forest**/ **Gradient Boost** / **ANN** /
- 🗺️ **ArcGIS Pro** (for spatial interpolation and map creation)
- 📊 **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**

---

## 📦 Workflow

```plaintext
Step 1: SAR Data Collection (Google Earth Engine)
Step 2: Ground Truth Collection (In-situ moisture readings)
Step 3: Data Cleaning & Merging
Step 4: Feature Engineering
Step 5: Model Training & Evaluation
Step 6: Spatial Prediction & Mapping (ArcGIS Pro)

