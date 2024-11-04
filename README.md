# Sales-Forecasting
This project aims to improve sales forecasting methods using artificial intelligence, specifically focusing on predictive analysis. The goal is to provide a comprehensive, data-driven approach to forecast sales accurately, helping businesses form reliable strategies, manage resources, and respond proactively to market demands.

## Project Overview

Sales forecasting is essential for businesses aiming to predict revenue and make strategic decisions. Traditional sales forecasting often relies on single-type analysis, which can limit the effectiveness of predictions. This project, therefore, integrates multiple types of analysis using machine learning techniques, particularly Random Forest and XGBoost, to achieve a higher accuracy in sales forecasting.

## Dataset

The project uses the BigMart open-source dataset for training and testing. This dataset includes various attributes that impact sales, such as:

Item Type
Outlet Type
Item MRP (Maximum Retail Price)
Other sales-related factors
The dataset is cleaned, pre-processed, and used to train machine learning models for improved sales predictions.

## Machine Learning Models

The following machine learning models were used:

- Random Forest: A popular ensemble method that builds multiple decision trees and merges them to improve prediction accuracy and control over-fitting.
- XGBoost: An optimized gradient boosting model that enhances prediction speed and model performance through advanced tree-based algorithms.

## Results

After training, the models yield the following R-squared values:

XGBoost: 0.7456
Random Forest: 0.7426
These results indicate that XGBoost slightly outperforms Random Forest in sales prediction accuracy, showcasing its potential for robust sales forecasting in a business context.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
