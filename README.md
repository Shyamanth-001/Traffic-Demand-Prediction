# 🚦 Traffic Demand Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict traffic demand using machine learning techniques by leveraging temporal, geospatial, and environmental features. The workflow includes data preprocessing, advanced feature engineering, model training, cross-validation, and performance evaluation.

The project demonstrates real-world machine learning practices and focuses on extracting meaningful patterns from time and location-based data.

---

## 🎯 Objectives

- Predict traffic demand accurately using machine learning models.
- Engineer informative temporal and geospatial features.
- Compare ensemble learning algorithms for regression.
- Improve model performance through feature engineering and cross-validation.

---

## 📂 Dataset

The dataset contains traffic-related information such as:

- Timestamp
- Geohash location
- Weather conditions
- Temperature
- Traffic demand (target variable)

**Target Variable:** Traffic Demand

---

## ⚙️ Workflow

1. Data Cleaning and Preprocessing
2. Missing Value Handling
3. Feature Engineering
4. Geospatial Data Processing
5. Model Training
6. Cross Validation
7. Model Evaluation
8. Prediction Generation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- PyGeoHash

---

## 🔧 Feature Engineering

The project includes advanced feature engineering techniques such as:

### Temporal Features
- Hour extraction
- Minute extraction
- Day of week
- Peak hour identification
- Time slot creation

### Cyclic Encoding
To preserve cyclical relationships in time data:

- Hour Sin/Cos Encoding
- Day Sin/Cos Encoding

### Geospatial Features
- Geohash decoding into latitude and longitude
- KMeans-based location clustering

### Interaction Features
- Weather interactions
- Temperature bins
- Hour bins

---

## 🤖 Models Used

- LightGBM Regressor
- CatBoost Regressor

---

## 🔄 Cross Validation

The project uses:

- 5-Fold Cross Validation

to ensure robust and reliable model evaluation.

---

## 📊 Evaluation Metrics

The models are evaluated using regression metrics such as:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

## 📈 Key Highlights

✅ Advanced Feature Engineering

✅ Geospatial Machine Learning

✅ Cyclic Time Encoding

✅ Ensemble Learning Models

✅ Cross Validation

✅ Reproducible Workflow

---

## 🚀 How to Run

Clone the repository:

```bash
git clone <https://github.com/Shyamanth-001/Traffic-Demand-Prediction.git>
cd Traffic-Demand-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
TrafficDemandPrediction.ipynb
```

and run all cells sequentially.

---

## 📁 Repository Structure

```text
Traffic-Demand-Prediction/
│
├── TrafficDemandPrediction.ipynb
├── train.csv
├── test.csv
├── requirements.txt
└──  README.md
```

---

## 👨‍💻 Author

**P Durgashyamanth**

GitHub: https://github.com/Shyamanth-001
