# Customer Churn Prediction Using K-Nearest Neighbors (KNN)

## Project Overview

This project focuses on predicting customer churn (customer categories) based on various features such as age, income, marital status, and more. We utilize the K-Nearest Neighbors (KNN) algorithm to build a classification model that can predict the customer category (`custcat`). The model's performance is evaluated using accuracy and a confusion matrix.

### Key Features:
- Customer data includes demographic and financial information.
- The `KNN` algorithm is used to classify customer categories.
- Data visualization using `matplotlib` for better insights.
- Model evaluation using accuracy and confusion matrix.

## Dataset

The dataset used in this project is the telecom customer dataset, which contains 1000 rows and 12 columns. The columns represent various features such as customer tenure, age, marital status, income, education level, and more. The target variable is the `custcat` column, which indicates the customer category.

### Columns in the Dataset:
- **region**: Region of the customer.
- **tenure**: Number of months the customer has been with the company.
- **age**: Age of the customer.
- **marital**: Marital status of the customer.
- **address**: Number of addresses the customer has had.
- **income**: Annual income of the customer.
- **ed**: Education level (encoded as integers).
- **employ**: Employment status of the customer.
- **retire**: Retirement status of the customer.
- **gender**: Gender of the customer.
- **reside**: Residential status (whether the customer resides in the region).
- **custcat**: Customer category (target variable).

## Requirements

To run this project, the following Python libraries need to be installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
