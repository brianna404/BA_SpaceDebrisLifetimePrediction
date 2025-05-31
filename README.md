# 🚀 Orbital Lifetime Prediction with Machine Learning

This repository provides a full pipeline for **predicting the orbital decay (remaining lifetime) of space debris** using machine learning methods. The approach is based on publicly available data from **[Space-Track.org](https://www.space-track.org)**, utilizing information from the **SATCAT** and **OMM (Orbit Mean-Elements Message)** datasets.

---

## 📌 Project Structure

### Code Directory

#### 1. Data Preparation Notebooks

A series of **five chronologically numbered Jupyter notebooks** guide the preprocessing and cleaning steps, including:

- DataPreparation1_SATCAT.ipynb
- DataPreparation2_ELSET.ipynb
- DataPreparation3_Combine.ipynb
- DataPreparation4_Preprocessing.ipynb
- DataPreparation5_Analysis.ipynb

#### 2. Lifetime Prediction Notebooks

Three main modeling notebooks provide ML-based predictions:

- LifetimePrediction1_LinReg.ipynb – Baseline linear regression
- LifetimePrediction2_RF.ipynb – Ensemble model with Random Forest
- LifetimePrediction3_MLP.ipynb – Deep learning approach using a Multilayer Perceptron (MLP)

### Data Directory

Contains all intermediate results, as well as the training and testing datasets in .csv files.

### Models Directory

Contains all serialized model files.


## 🔐 Data Access

To fetch data directly from [Space-Track.org](https://www.space-track.org), an active account is required.
Place your **username** and **password** in a local `SpaceTrackCredentials.txt` file.
