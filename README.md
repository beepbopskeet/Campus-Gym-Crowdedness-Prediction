# 🏋️ Campus Gym Crowdedness Prediction

## 📌 Project Overview

This project analyzes gym attendance patterns and develops machine learning models to predict campus gym occupancy.

The objective is to understand how time-based and environmental factors influence gym crowdedness and to evaluate multiple regression models for occupancy prediction.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Dataset Description

The dataset contains information related to gym attendance and occupancy, including:

* Date and Time
* Hour of the Day
* Day of the Week
* Temperature
* Occupancy Counts
* Environmental Variables

Target Variable:

* Number of People in the Gym

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Datetime conversion
* Feature extraction from timestamps
* Handling missing values
* Removal of unnecessary columns
* Feature scaling
* Train-test splitting

---

## 📈 Exploratory Data Analysis

Analysis included:

* Occupancy distribution analysis
* Hourly attendance trends
* Day-of-week comparisons
* Temperature vs occupancy relationships
* Correlation analysis

### Key Findings

* Peak attendance occurs during specific hours of the day.
* Weekday and weekend patterns differ significantly.
* Certain environmental variables show measurable influence on gym occupancy.
* Historical attendance data provides strong predictive power.

---

## 🤖 Machine Learning Models

The following regression algorithms were implemented and compared:

* Linear Regression
* Ridge Regression
* Lasso Regression
* K-Nearest Neighbors Regressor
* Decision Tree Regressor
* Random Forest Regressor

---

## 📊 Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Performance comparison was used to identify the most effective prediction model.

---

## 🎯 Real-World Applications

Potential applications include:

* Gym capacity planning
* Resource allocation
* Peak-hour management
* Staff scheduling
* Facility optimization

---

## 🚀 How to Run

```bash
git clone https://github.com/beepbopskeet/Campus-Gym-Crowdedness-Prediction.git

cd Campus-Gym-Crowdedness-Prediction

pip install -r requirements.txt

jupyter notebook
```

---

## 🔮 Future Improvements

* XGBoost Regression
* Hyperparameter Tuning
* Time-Series Forecasting
* Real-Time Occupancy Prediction
* Interactive Dashboard Development
