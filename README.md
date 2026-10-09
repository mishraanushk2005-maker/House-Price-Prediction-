# Bengaluru House Price Prediction

A machine learning project that predicts house prices in Bengaluru based on property features such as location, total square footage, BHK, and number of bathrooms.

This project was created to understand and implement an end-to-end machine learning workflow, from data cleaning and exploratory data analysis to model training, hyperparameter tuning, and evaluation.

## Project Objective

The main objective of this project is to build a regression model that can predict Bengaluru house prices using historical property data.
Through this project, I explored how different property features affect house prices and learned how to prepare real-world data for machine learning models.

## Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning
* **Jupyter Notebook** – Development and analysis

## Dataset

The dataset contains information about Bengaluru residential properties, including:

* Location
* Total square footage
* Number of bedrooms (BHK)
* Number of bathrooms
* House price

The dataset contains real-world issues such as missing values, inconsistent records, and outliers, which were handled during preprocessing.

##  Project Workflow

The project follows these major steps:

1. **Data Loading**
2. **Data Cleaning**
3. **Handling Missing Values**
4. **Exploratory Data Analysis (EDA)**
5. **Outlier Detection and Removal**
6. **Feature Engineering**
7. **Categorical Feature Encoding**
8. **Feature Preparation**
9. **Train-Test Split**
10. **Model Training**
11. **Hyperparameter Tuning**
12. **Model Evaluation**
13. **Feature Importance Analysis**

##  Exploratory Data Analysis

EDA was performed to understand the dataset and identify important patterns.

Some of the analysis includes:

* Price distribution
* BHK distribution
* Location-wise price analysis
* Relationship between area and price
* Bathroom and price analysis
* Correlation analysis
* Outlier analysis
* Actual vs. predicted prices
* Residual analysis
* Model performance comparison

More than **10 visualizations** were created during the analysis.

## Machine Learning Models

The following regression models were trained and compared:

* Linear Regression
* Decision Tree Regression
* Random Forest Regression

The models were evaluated to determine which approach performed better on the dataset.

## Hyperparameter Tuning
For model optimization, I used:

* **RandomizedSearchCV**
* **GridSearchCV**
* Cross-validation

These techniques were used to find suitable hyperparameters and improve the model's performance and generalization.

##  Model Evaluation

The models were evaluated using:

* **R² Score** – Measures how well the model explains the variation in house prices.
* **Mean Absolute Error (MAE)** – Measures the average absolute prediction error.
* **Root Mean Squared Error (RMSE)** – Measures prediction error while giving more weight to larger errors.

### Results

| Model             |  R² Score |       MAE |      RMSE |
| ----------------- | --------: | --------: | --------: |
| Linear Regression | Add value | Add value | Add value |
| Decision Tree     | Add value | Add value | Add value |
| Random Forest     | Add value | Add value | Add value |

> Replace the values above with the actual results from your notebook.

## Key Learnings

Through this project, I gained practical experience in:

* Working with real-world datasets
* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Categorical encoding
* Regression algorithms
* Hyperparameter tuning
* Cross-validation
* Model evaluation
* Data visualization
* Interpreting model results and feature importance

## Project Structure

```text
Bengaluru-House-Price-Prediction/
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── Bengaluru_House_Price_Prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

> Update the folder and file names according to your actual repository.

##  How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Bengaluru-House-Price-Prediction
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

##  Future Improvements

Some possible improvements for this project are:

* Deploy the model as a web application using Streamlit or Flask
* Experiment with additional regression algorithms
* Improve feature engineering
* Perform more extensive hyperparameter tuning
* Use additional real-estate features
* Build an interactive house-price prediction interface

##  About

This project is part of my **machine learning learning journey**, where I am building practical projects to strengthen my understanding of data analysis, machine learning, and model evaluation.

⭐ If you find this project useful, feel free to explore the repository.
