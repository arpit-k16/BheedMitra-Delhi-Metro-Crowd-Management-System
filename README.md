# 🚇 Delhi Metro Passenger Flow & Crowd Management System

## 📌 Overview

The **Delhi Metro Passenger Flow & Crowd Management System** is a
data-driven machine learning solution designed to analyze, simulate, and
predict metro crowd levels across stations and time periods.

This project demonstrates how AI-driven predictive modeling can support
smarter urban transportation management by forecasting congestion before
it occurs.

------------------------------------------------------------------------

## 🎯 Problem Statement

Delhi Metro handles millions of passengers daily, with congestion spikes
caused by:

-   Morning & evening peak hours\
-   High-traffic interchange stations\
-   Weather disruptions\
-   Festivals & public events

Traditional monitoring systems are reactive.\
This project builds a **predictive crowd intelligence system** that
enables proactive congestion management.

------------------------------------------------------------------------

## 🏗 System Workflow

Data Generation / Collection\
→ Data Preprocessing\
→ Feature Engineering\
→ Exploratory Data Analysis\
→ Machine Learning Model Training\
→ Model Evaluation\
→ Streamlit Dashboard Deployment

------------------------------------------------------------------------

## 📊 Dataset Description

Due to the unavailability of public AFC (Automatic Fare Collection)
logs, this project uses a **high-fidelity synthetic dataset** designed
to replicate real-world Delhi Metro patterns.

### Key Features

-   Station Name\
-   Metro Line\
-   Boarding Time Category\
-   Day Type (Weekday / Weekend / Festival)\
-   Weather Condition\
-   Station Category (Interchange / Commercial / Residential)\
-   Ridership Weight\
-   Train Headway Effect\
-   Event Impact Indicator\
-   Platform Crowd Level (1--5 scale)

The dataset maintains statistical consistency with real metro crowd
behavior while preserving privacy.

------------------------------------------------------------------------

## 🧠 Machine Learning Models

### 🎯 Objective

Predict platform crowd level (1--5 ordinal scale)

### Models Implemented

-   Logistic Regression\
-   Random Forest\
-   XGBoost (Best Performer)

### 📈 Model Performance

  Metric              Score
  ------------------- --------
  Accuracy            \~90%
  Balanced Accuracy   \~90%
  Macro F1 Score      \~0.89

XGBoost achieved the highest accuracy due to its ability to model
complex non-linear spatial and temporal patterns.

------------------------------------------------------------------------

## 🔍 Feature Importance (Top Predictors)

-   Ridership Weight (Station Popularity)\
-   Boarding Time Category\
-   Station Category Index\
-   Weather Multiplier\
-   Train Headway Effect\
-   Special Event Indicator

These features strongly influence crowd density variations across
stations.

------------------------------------------------------------------------

## 📊 Exploratory Data Analysis

EDA includes:

-   Time-of-day crowd distribution plots\
-   Station-wise congestion heatmaps\
-   Weather vs Ridership correlation\
-   Wait-time vs Crowd level relationship\
-   Peak vs Off-Peak comparison

Libraries used: - Pandas\
- NumPy\
- Matplotlib\
- Seaborn\
- Plotly

------------------------------------------------------------------------

## 🖥 Streamlit Dashboard Features

### 👨‍💼 Admin View

-   Real-time crowd simulation\
-   Station-wise congestion forecasts\
-   Event impact simulation\
-   Peak-hour analysis\
-   Visual analytics dashboard

### 🚉 Passenger View

-   Predicted crowd level\
-   Estimated wait time\
-   Suggested optimal travel time

------------------------------------------------------------------------

## ⚙️ Tech Stack

-   Python\
-   Pandas\
-   NumPy\
-   Scikit-learn\
-   XGBoost\
-   Matplotlib\
-   Seaborn\
-   Plotly\
-   Streamlit

------------------------------------------------------------------------

## 📂 Project Structure

Delhi-Metro-Crowd-Management/ │ ├── data/ │ ├── synthetic_dataset.csv │
└── station_metadata.csv │ ├── notebooks/ │ ├── EDA.ipynb │ └──
Model_Training.ipynb │ ├── models/ │ ├── crowd_classifier.pkl │ └──
encoder.pkl │ ├── app.py ├── requirements.txt └── README.md

------------------------------------------------------------------------

## 🚀 Installation

### 1️⃣ Clone the Repository

git clone
https://github.com/yourusername/delhi-metro-crowd-management.git\
cd delhi-metro-crowd-management

### 2️⃣ Install Dependencies

pip install -r requirements.txt

### 3️⃣ Run the Application

streamlit run app.py

------------------------------------------------------------------------

## 📈 Impact

✔ Predicts congestion before escalation\
✔ Supports data-driven scheduling decisions\
✔ Enhances commuter planning\
✔ Scalable to other urban metro systems

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   Integration with real AFC logs\
-   IoT-based passenger counting\
-   CCTV-based crowd density estimation\
-   LSTM-based time-series forecasting\
-   Multi-city urban transport scalability

------------------------------------------------------------------------

## 📜 Academic Context

This project was developed as a Machine Learning and Data Science
initiative focused on intelligent transportation systems and smart city
infrastructure.

------------------------------------------------------------------------

## 📬 Contact

Arpit Kumar
Student
Department of Computer Science\
Bennett University

------------------------------------------------------------------------

## 👥 Contributors

- Arpit Kumar
- Lakshay Bansal

------------------------------------------------------------------------

⭐ If you find this project interesting, consider giving it a star!
