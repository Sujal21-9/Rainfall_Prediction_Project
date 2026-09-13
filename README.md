# 🌧️ Rainfall Prediction using Machine Learning

A machine learning project that predicts whether rainfall will occur
based on various weather conditions.

## 📌 Project Overview

This project uses historical weather data to build a machine learning
classification model for rainfall prediction.
## 🤖 Machine Learning Model

A Random Forest Classifier was trained to predict rainfall based on
weather-related features.

## 📊 Dataset

The dataset contains weather-related features such as:
- day
- Pressure
- Maximum Temperature
- Temperature
- Minimum Temperature
- Dew Point
- Humidity
- Cloud
- Sunshine
- Wind Direction
- Wind Speed

Target variable:

- Rainfall: Yes / No

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🚀 Workflow

1. Data collection
2. Data preprocessing
3. Missing value handling
4. Exploratory Data Analysis
5. Correlation analysis
6. Feature preparation
7. Model training
8. Model evaluation
9. Rainfall prediction


### Model Performance

- **Algorithm:** Random Forest Classifier
- **Test Accuracy:** 74.47%
- **Macro F1-Score:** 0.74

### Confusion Matrix

|              | Predicted 0 | Predicted 1 |
|--------------|-------------|-------------|
| Actual 0     | 17          | 7           |
| Actual 1     | 5           | 18          |

### Classification Report

| Class | Precision | Recall | F1-Score |
|------:|----------:|-------:|---------:|
| 0     | 0.77      | 0.71   | 0.74     |
| 1     | 0.72      | 0.78   | 0.75     |


## 👨‍💻 Author

Sujal Mahajan