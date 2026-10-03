# Agricultural ML Project

## Project Overview

This project focuses on applying machine learning and data analysis techniques to agriculture and agribusiness.

The main idea of the project is to explore historical agricultural data and develop a machine learning approach for crop yield prediction. The project will consider factors such as crop, location, season, year, area, production, and relevant weather conditions.

The first stage of the project focuses on understanding the available data, identifying useful features, planning the data cleaning process, and deciding how the data can be analyzed before developing the machine learning models.

## Problem Statement

Crop yield can vary depending on several factors such as crop type, location, season, year, rainfall, temperature, and other agricultural conditions. Understanding these factors from historical data can help in developing a predictive machine learning model.

This project aims to study these patterns and prepare a suitable dataset for crop yield prediction.

## Objectives

The main objectives of this project are:

- Research suitable public agricultural datasets
- Understand historical crop production data
- Identify factors that may influence crop yield
- Study the relationship between agricultural and weather variables
- Clean and preprocess the selected datasets
- Perform exploratory data analysis
- Prepare the data for machine learning
- Develop and evaluate regression models in the later stages

## Datasets

The project plans to use two public data sources:

### 1. Government of India Open Government Data (OGD)

The selected agricultural dataset is:

**District-wise, Season-wise Crop Production Statistics from 1997**

It contains information related to factors such as year, state/region, district, crop, season, area, and production.

Source: Government of India Open Government Data (OGD)

### 2. NASA POWER

NASA POWER will be explored for relevant weather and climate information such as temperature, precipitation, relative humidity, and solar radiation.

The weather data may be used later for feature engineering after checking whether it can be properly matched with the agricultural data by location and time.

## Research Questions

The project will explore questions such as:

- How does crop production vary across different years?
- Which crops have higher or lower yields?
- How does agricultural production vary across different regions?
- Is rainfall related to crop yield?
- Is temperature associated with agricultural production?
- Which features are useful for predicting crop yield?
- Can agricultural and weather data be used together for machine learning?
- Do different crops and seasons show different predictive patterns?

## Data Analysis Plan

Before model development, the data will be examined through exploratory data analysis.

The analysis will include:

- Basic statistical summaries
- Missing value analysis
- Crop-wise analysis
- Year-wise trends
- Seasonal analysis
- Regional comparisons
- Distribution of important variables
- Relationship between weather and agricultural variables
- Correlation analysis

Visualizations such as bar charts, line charts, histograms, box plots, scatter plots, and correlation heatmaps will be considered.

## Data Cleaning Plan

The data cleaning process will include:

- Checking missing values
- Checking duplicate records
- Correcting data types
- Standardizing category names
- Checking units and measurement formats
- Identifying unusual or extreme values
- Handling outliers where appropriate
- Preparing the target variable for crop yield prediction

## Planned Machine Learning Models

The project will initially consider the following regression models:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting

The models will be trained and compared after the data preparation and exploratory analysis stages.

## Evaluation Metrics

The planned evaluation metrics are:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics will be used to understand how well the models perform in predicting crop yield.

## Project Workflow

The planned workflow for the project is:

1. Research
2. Dataset Selection
3. Data Collection
4. Data Cleaning
5. Data Integration
6. Exploratory Data Analysis
7. Feature Engineering
8. Model Development
9. Model Evaluation
10. Documentation

## Project Structure

```text
Agricultural-ML-Project
│
├── data
├── notebooks
├── reports
│   └── Week-1-Strategic-Plan.docx
├── src
└── README.md