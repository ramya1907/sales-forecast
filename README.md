# Sales Forecasting 

## Overview

This project aims to forecast future sales trends and demand for products using historical sales data. The dataset contains information about transactions, including InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

## Dataset

The dataset used in this project is a transnational data set containing all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts, and many customers are wholesalers.

This dataset is sourced from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).

## Features

- **InvoiceNo**: A unique identifier for each transaction.
- **StockCode**: A unique identifier for each distinct product.
- **Description**: The name of the product.
- **Quantity**: The quantities of each product per transaction.
- **InvoiceDate**: The date and time when each transaction was generated.
- **UnitPrice**: The price per unit of the product.
- **CustomerID**: A unique identifier for each customer.
- **Country**: The country where the transaction took place.

## Methodology

1. Data Cleaning: Cleaned the dataset by handling missing values and removing rows with negative quantities.
2. Feature Engineering: Extracted features like Year, Month, Day, and WeekOfYear from InvoiceDate and converted categorical variables to numerical ones.
3. Model Selection: Used linear regression to train the model and predict future sales.
5. Model Evaluation: Evaluated the model using Mean Squared Error (MSE) and R-squared values.

## Results

- Mean Squared Error (MSE): 16605.48
- R-squared: 0.14

## Conclusion

Based on these metrics, it can be concluded that the linear regression model currently has limited predictive power for forecasting sales revenue. Possible next steps to improve the model include:

- **Feature Engineering**: Identify and include more relevant features that might have a stronger impact on sales revenue prediction.
- **Model Selection**: Try different regression models or machine learning algorithms to see if they can provide better performance.
- **Hyperparameter Tuning**: Fine-tune the parameters of the chosen model to optimize its performance.
- **Data Enhancement**: Collect more data or refine existing data to improve the model's training and predictive capabilities.

By iteratively refining the model and incorporating these improvements, you can work towards developing a more accurate sales forecasting model.
