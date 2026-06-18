# House Price Prediction

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze housing characteristics such as area, number of bedrooms, bathrooms, stories, parking facilities, and other amenities to estimate property prices accurately. The project also identifies the key factors that have the greatest influence on housing prices.

## Dataset

The dataset used for this project is the **Housing Prices Dataset** obtained from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

The dataset contains information about residential properties, including both numerical and categorical features that affect house prices.

## Project Tasks

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas.
* Examined the first few records.
* Checked dataset dimensions and column information.
* Identified missing values and data types.

### 2. Data Cleaning and Preprocessing

* Removed duplicate records.
* Handled missing values where necessary.
* Converted categorical variables into numerical format using one-hot encoding.
* Prepared the dataset for machine learning models.

### 3. Model Development

Two regression models were implemented:

#### Linear Regression

A baseline model used to establish relationships between property features and house prices.

#### Random Forest Regressor

An ensemble learning model used to improve prediction accuracy by capturing complex patterns in the data.

### 4. Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The performance of both models was compared to determine the better-performing approach.

### 5. Data Visualization

The project includes the following visualizations:

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

These visualizations help understand data distribution, feature relationships, and model performance.

## Technologies Used

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Project Structure

```text
HousePricePrediction_suryachaitanya
│
├── analysis.ipynb
├── Housing.csv
├── README.md
├── summary.docx
│
└── charts
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

## Key Findings

* Property area was identified as the most influential factor affecting house prices.
* Bathrooms, stories, parking facilities, and location-related amenities also contributed significantly.
* The Random Forest Regressor achieved better predictive performance compared to Linear Regression.
* Housing amenities and preferred locations had a noticeable impact on property valuation.

## Business Recommendation

Real estate businesses can leverage predictive analytics to estimate property values more accurately and support pricing decisions. Focusing on larger properties in preferred locations with modern amenities can improve market value and profitability.

##
