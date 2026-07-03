
# NYC Taxi Fare Prediction using Apache Spark

This project predicts NYC Yellow Taxi total fare amount using Apache Spark, Databricks, SparkML, and Power BI.

## Project Overview
The dataset contains over 1 million NYC Yellow Taxi trip records from January 2025. The objective is to predict `total_amount` using trip-level features such as trip distance, passenger count, pickup hour, and trip duration.

## Tools Used
- Apache Spark
- Databricks Community Edition
- SparkSQL
- Spark DataFrames
- SparkML
- Delta Lake
- Power BI

## Dataset
Source: NYC Taxi and Limousine Commission Trip Record Data  
Dataset used: Yellow Taxi Trip Data, January 2025

## Project Pipeline
1. Data ingestion using Spark DataFrames
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature engineering
5. Model training using SparkML
6. Model evaluation using RMSE, R2, and MAE
7. Hyperparameter tuning
8. Power BI dashboards

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosted Trees Regressor

## Model Comparison

| Model | RMSE | R² | MAE |
|:------|------:|------:|------:|
| Linear Regression | 3.31 | 0.71 | 2.49 |
| Decision Tree | 3.16 | 0.74 | 2.38 |
| Random Forest | 3.08 | 0.75 | 2.32 |
| **Gradient Boosted Trees** | **3.07** | **0.75** | **2.31** |

## Repository Structure
```text
notebook/       Spark/Databricks notebook
report/         Final project report
presentation/   Final presentation deck
dashboards/     Power BI dashboard screenshots
data/           Sample data only
