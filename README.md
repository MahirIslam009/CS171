# CS171
## Project Title:  Predicting Car Prices and Fuel Efficiency Using Machine Learning


### Authors:
- Kaulan Serzhanuly – Fuel Efficiency Prediction  
- Mahir Islam – Car Price Prediction  

### Project Overview
This project investigates how different machine learning models—both classical and neural network–based—perform on **real-world automotive regression tasks**.

We study two prediction problems:
1. **Used Car Price Prediction** (Mahir)  
2. **Fuel Efficiency (MPG) Prediction** (Kaulan)
For each dataset, we compare a **traditional ML model** with a **Multi-Layer Perceptron (MLP)** neural network to evaluate how nonlinear learning affects performance.  
Our goal is to determine **which model generalizes better**, understand why, and interpret key predictive factors.

### Project File Structure (Mahir)
CS171
│
├── data/
│ ├── CarPrice_Assignment.csv
│ └── auto-mpg.csv
│
├── notebooks/
│ ├── preprocessing_car_price.ipynb
│ ├── model_car_price.ipynb
│ ├── analysis_car_price.ipynb
│ ├── preprocessing_mpg.ipynb
│ ├── model_mpg.ipynb
│ └── analysis_mpg.ipynb
│
├── images/
└── README.md

### Environment Setup & Reproducibility
This project was run using the cs171 Conda environment set up at the beginning of the course using the professor’s instructions.
The environment includes Python 3.12, numpy, pandas, matplotlib, seaborn, scikit-learn, and torch. The notebook runs top-to-bottom without configuration changes.


### Description of Question and Research Topic (5 Sentences):
This project looks at using the machine learning tools we used in class to predict used car prices and car fuel efficiency based off real-world datasets.
Each team member focuses on one dataset:
- **Author 1:** Car Price Prediction
- **Author 2:** Fuel Efficiency Prediction
For car prices, we will compare a Decision Tree with a Multi-Layer Perceptron.
For fuel efficiency, we compare a Linear Regression model with a MLP to see how non-linear learning affects accuracy.
We want to see which model performs better for each task and understand how they differ in accuracy.

***Project Outline/Plan:***
	Data Collection Plan (two parts, one for each author):
	- **Car Price Dataset:** [Kaggle Car Price Prediction](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
    - **Fuel Efficiency Dataset:** [Kaggle Auto Mpg Data Set](https://www.kaggle.com/datasets/uciml/autompg-dataset?resource=download)
	
***Model Plans (two parts, one for each author):***

#### Author 1 – Car Price Prediction
- **Models:**
  1. Multi-Layer Perceptron
  2. Decision Tree
- **Goal:** Compare and contrast two models
#### Author 2 – Fuel Efficiency (MPG) Prediction
- **Models:**
  1. Linear Regression
  2. Multi-Layer Perceptron
- **Goal:** Compare and contrast two models

	
***Project Timeline:***
November 30 or December 1
	
