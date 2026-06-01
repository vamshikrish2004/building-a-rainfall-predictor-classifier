# Rainfall Prediction Classifier 🌧️

An end-to-end Machine Learning classification project utilizing historical Australian weather data to predict whether it will rain tomorrow. 

## 📌 Project Overview
This project focuses on building a robust binary classifier to forecast rainfall. Predicting weather patterns accurately is highly critical for agriculture, aviation, and disaster management. Using a comprehensive dataset of daily weather observations from various locations across Australia, this model processes key environmental factors to make accurate predictions.

## 📊 Dataset Description
The model is trained on the **Australian Weather Dataset** (`FinalProject_AUSWeather`). The dataset contains multiple meteorological features, including:
* **Temperature:** Minimum and maximum daily temperatures.
* **Moisture:** Humidity levels at 9 AM and 3 PM.
* **Atmospheric Pressure:** Pressure readings recorded at 9 AM and 3 PM.
* **Wind Metrics:** Wind gust direction, speed, and sustained wind speeds.
* **Precipitation:** Rainfall amounts recorded for the day.
* **Target Variable:** `RainTomorrow` (Yes/No) - Whether the automated weather station recorded 1mm or more of rain the following day.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn

## 🚀 Workflow & Key Steps

### 1. Data Cleaning & Preprocessing
* Handled missing value imputations for both numerical and categorical variables.
* Encoded categorical features (such as Wind Direction and Location) using One-Hot Encoding and Label Encoding.
* Managed class imbalance in the target variable to prevent model bias.

### 2. Feature Engineering & Scaling
* Dropped redundant or highly correlated features to minimize multicollinearity.
* Scaled numerical features using standardizing techniques (`StandardScaler` or `MinMaxScaler`) to optimize distance-based algorithm performance.

### 3. Model Training & Evaluation
Multiple classification algorithms were trained and compared, including:
* Logistic Regression
* Decision Trees
* Random Forest Classifier
* Support Vector Machines (SVM)

Models were evaluated based on **Accuracy**, **Precision**, **Recall**, and **F1-Score** to ensure balanced performance on predicting both rainy and dry days.

## 📈 Results Summary
*(Optional: You can fill this section out with your model's actual performance numbers)*
* **Best Performing Model:** [e.g., Random Forest Classifier]
* **Test Accuracy:** [e.g., 85%]
* **F1-Score:** [e.g., 0.82]

## 💻 How to Run the Project
1. Clone this repository:
```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
