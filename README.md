# Retail Sales Demand Prediction

## Project Overview

The Retail Sales Demand Prediction project analyses retail store sales data to understand sales patterns, compare products and outlets, and predict item-level outlet sales using machine learning regression models.

The project is developed using Python in a Jupyter Notebook and can be executed in Google Colab.

## Objectives

* Analyse retail sales data and identify important patterns.
* Clean missing, inconsistent, and duplicate data.
* Perform Exploratory Data Analysis (EDA).
* Study sales performance across products and outlets.
* Engineer useful features for predictive modelling.
* Train and compare regression models.
* Evaluate model performance using standard regression metrics.
* Identify important features that influence predicted sales.

## Technologies Used

* **Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Environment:** Jupyter Notebook / Google Colab

## Machine Learning Models

The notebook compares the following models:

1. **Baseline Regressor** – predicts the mean sales value.
2. **Linear Regression** – provides an interpretable regression benchmark.
3. **Random Forest Regressor** – captures nonlinear relationships between input features and sales.

The notebook uses cross-validation and hyperparameter tuning to evaluate and compare model performance.

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R-squared (R²)

It also includes a robustness check in which entire items are held out from model training.

## Dataset

The notebook expects a CSV file named `data.csv`.

The dataset contains item-level and outlet-level information, including product attributes, outlet attributes, and `Item_Outlet_Sales`, which is the target variable.

**Note:** The notebook does not contain customer identifiers, transaction dates, or quantity-sold information. Therefore, customer-level RFM analysis and time-series demand forecasting are not performed.

## Project Structure

```text
retail_sales_demand_prediction/
├── retail_sales_demand_prediction.ipynb
├── data.csv
├── requirements.txt
└── README.md
```

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/retail_sales_demand_prediction.git
```

### 2. Open the project folder

```bash
cd retail_sales_demand_prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `retail_sales_demand_prediction.ipynb` using Jupyter Notebook or upload it to Google Colab.

### 5. Load the dataset

Place `data.csv` next to the notebook, or upload it when prompted in Google Colab.

### 6. Execute the notebook

Run the cells in order to perform data cleaning, analysis, feature engineering, model training, evaluation, and export the results.

## Output Files

The notebook exports:

* `cleaned_retail_sales.csv` – cleaned retail sales dataset.
* `model_comparison.csv` – regression model evaluation results.

## Conclusion

This project demonstrates how data analysis and machine learning can be applied to retail sales data to generate business insights and estimate item-level sales at retail outlets.

## Author

S.Priyadharshini
