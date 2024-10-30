# 🌊🚢 Titanic Survival Prediction | ML Insights 🚢🌊

This project dives into the famous Titanic Survival Prediction dataset to analyze factors influencing passenger survival during the disaster. Leveraging exploratory data analysis (EDA), data visualization, and machine learning, this project uncovers insights and builds a predictive model on survival probabilities.

## 📊 Project Overview
This notebook performs a thorough Exploratory Data Analysis (EDA) and builds a machine learning model to predict survival rates. Here’s what you’ll find in this project:

## Data Cleaning:
Handle missing values for key columns like Age, Cabin, and Embarked.
Transform data types for efficient analysis and processing.

## Univariate Analysis:
Analyze the distribution of individual features such as Age, Fare, Pclass, and Sex.
Visualize distributions to identify potential issues like skewness and outliers.

## Bivariate and Multivariate Analysis:
Explore relationships between Survived and features such as Sex, Pclass, and Embarked.
Visualize correlations with bar plots, box plots, and heatmaps.
Identify combined effects of multiple features on survival outcomes.

## Predictive Modeling:
Build a machine learning model based on EDA insights to predict survival.
Evaluate model performance and tune for accuracy.

## 📁 Project Structure

├── Titanic-Survival-Prediction-ML-Insights.ipynb  # Main analysis notebook

├── README.md                                      # Project documentation

└── data                                           # Dataset (place Titanic dataset here)

## 🔑 Key Insights
Age and Survival: Age is nearly normally distributed, though some values are missing. Younger passengers showed a higher survival rate.
Passenger Class and Gender: Clear survival differences based on Pclass and Sex.
Fare: Higher fare often correlated with higher survival chances, suggesting passengers in higher classes had better odds of survival.

## 🚀 Getting Started

Clone the repository:

git clone https://github.com/AreejPanhwer/Titanic-Survival-Prediction-ML-Insights

## Install required libraries:
Run pip install -r requirements.txt if there’s a requirements file, or manually install common libraries:
python
pip install pandas numpy matplotlib seaborn scikit-learn

## Run the Notebook:
Open and run Titanic-Survival-Prediction-ML-Insights.ipynb in Jupyter Notebook or JupyterLab.

## 📌 Conclusion
Through thorough EDA and a machine learning approach, this project reveals crucial factors affecting survival on the Titanic. These insights can aid in building a reliable model that effectively forecasts passenger survival outcomes.

Feel free to contribute, open issues, or suggest improvements to make this project more robust and insightful!
