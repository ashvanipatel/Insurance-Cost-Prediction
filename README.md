# 💰 Insurance Cost Prediction using Machine Learning

## 📌 Overview

MedCost Insight is a machine learning project that predicts medical insurance charges based on user demographics and health factors. It demonstrates a complete data science workflow from data preprocessing to model evaluation.

## 🎯 Objectives

* Analyze factors affecting insurance costs
* Perform feature engineering and data preprocessing
* Build regression models for prediction
* Evaluate model performance

## 📂 Dataset

* File: `insurance.csv`
* Contains ~1300 records

### Features

* `age`: Age of individual
* `sex`: Gender
* `bmi`: Body Mass Index
* `children`: Number of dependents
* `smoker`: Smoking status
* `region`: Residential area
* `charges`: Insurance cost (target)

## ⚙️ Workflow

1. Data loading and inspection
2. Data cleaning
3. Feature engineering
4. Exploratory Data Analysis
5. Correlation analysis
6. Model building
7. Model evaluation

## 🔧 Feature Engineering

* Converted categorical variables
* Created `is_smoker` and `is_female`
* Applied one-hot encoding on regions
* Created BMI categories

## 📊 Key Insights

* Smoking strongly increases insurance charges
* BMI and age positively affect cost
* Region has minimal impact
* Children count has low influence


## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

## ▶️ Run Project

```bash
git clone https://github.com/your-username/medcost-insight.git
pip install -r requirements.txt
jupyter notebook
```

## 📁 Structure

```
project/
│-- insurance.csv  
│-- insurancel.ipynb  
│-- README.md  
```

## 🚀 Future Work

* Hyperparameter tuning
* Model deployment
* Dashboard creation

## 👨‍💻 Author

Ashvani Patel

## ⭐ Support

If you like this project, give it a star ⭐
