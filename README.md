# Sales Forecasting Project

## Project Overview
This project aims to forecast sales using machine learning techniques. It involves data preprocessing, feature engineering, and model training to predict future sales based on historical data.

## Project Structure
Sale_Forecasting.ipynb: The Jupyter Notebook containing the complete analysis, data preprocessing, model training, and evaluation.

data: https://www.kaggle.com/datasets/ldausl/store-sales-time-series-forecasting

### Dataset Import

This project uses the Kaggle API to download the dataset directly into the notebook. The dataset is imported as a ZIP file and extracted programmatically. To use this feature:

* Ensure you have the Kaggle API installed:

`pip install kaggle`

* Authenticate by placing your Kaggle API key (kaggle.json) in the appropriate directory:

`mkdir -p ~/.kaggle`
`mv kaggle.json ~/.kaggle/`
`chmod 600 ~/.kaggle/kaggle.json`

* Download the dataset using the API:

`!kaggle datasets download -d <dataset-name> -p ./data --unzip`


## Dependencies
Ensure you have the following Python packages installed:

pandas,
numpy,
matplotlib,
seaborn,
scikit-learn,
Jupyter Notebook

## Usage
Open the Jupyter Notebook and execute the cells to preprocess data and train the model.
Modify the parameters to experiment with different machine learning models.
Evaluate the model's performance and make predictions on new data.

## Results
The project includes evaluation metrics such as RMSE, MAE, and R-squared to assess the model's accuracy. Visualizations are provided to analyze trends and patterns in sales data.
