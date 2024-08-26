# ✈️ Flight Fare Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Sklearn-yellow.svg)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20Numpy-green.svg)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)

## 🚀 Project Overview

Flight fare prediction is a critical task that involves estimating the cost of flight tickets based on various factors. This repository focuses on building an end-to-end machine learning pipeline that predicts flight fares using historical data.

**Key Highlights:**
- **Data Analysis & Visualization:** In-depth exploratory data analysis (EDA) using Pandas, Matplotlib, and Seaborn to uncover patterns and insights.
- **Data Cleaning & Preprocessing:** Automated processes to handle missing values, outliers, and feature engineering.
- **Machine Learning Models:** Model training and hyperparameter tuning using algorithms like Linear Regression, Decision Trees, and Random Forests.
- **Automation & Modularity:** The project includes a Python script to automate tasks like data cleaning and model training.

## 📊 Data Analysis and Cleaning

The project begins with an extensive data analysis phase:

- **Visualizations:** Understand the relationship between features like airline, source, destination, and price.
- **Feature Engineering:** Extract useful features from date-time fields (e.g., journey day, month) and perform one-hot encoding.
- **Data Cleaning:** Handle missing values, correct inconsistencies, and remove outliers to improve model accuracy.

## 🤖 Machine Learning Pipeline

The project implements a full machine learning pipeline with:

- **Model Selection:** Compare multiple algorithms including Linear Regression, Decision Trees, and Ensemble methods.
- **Hyperparameter Tuning:** Optimize model performance using techniques like GridSearchCV.
- **Evaluation:** Measure model accuracy using metrics like RMSE, MAE, and R².

## 🛠️ Automation Features

The `flight_fare_prediction.py` script automates the following tasks:

- Data preprocessing and feature engineering.
- Model training and evaluation.
- Saving and loading trained models for future predictions.

## 🧑‍💻 How to Run

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/Flight-Fare-Prediction.git
    cd Flight-Fare-Prediction
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebook or execute the Python script:**

    ```bash
    jupyter notebook Notebooks/Flight_fare_prediction.ipynb
    # or
    python Scripts/flight_fare_prediction.py
    ```

## 📈 Results & Insights

This project achieves a reasonably accurate prediction of flight fares by leveraging historical data. The notebook provides detailed insights into model performance and recommendations for future improvements.


---

## 🙌 Thanks & Happy Coding!

Thank you for exploring this project! If you found it helpful or interesting, feel free to ⭐ the repository.

Remember: *"Code is like humor. When you have to explain it, it’s bad."* – *Cory House*

Happy coding! 🚀👨‍💻
