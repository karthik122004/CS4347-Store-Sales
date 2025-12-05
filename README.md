# Store Sales - Time Series Forecasting

## Project Overview and Goals
This project aims to predict daily sales for thousands of product families at Corporación Favorita stores in Ecuador. Using time-series forecasting techniques, we analyze historical store sales data to build a machine learning model that anticipates future demand. Accurate forecasting helps optimize inventory management and reduce waste.

The project compares multiple modeling approaches, including a Baseline model, Ridge Regression, and LightGBM (Gradient Boosting), with the final tuned LightGBM model achieving the best performance.

## Dependencies
The following libraries are required to run this project:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (sklearn)
- lightgbm

## Installation and Usage
1. **Clone the repository:**
git clone https://github.com/karthik122004/CS4347-Store-Sales.git

2. **Install dependencies:**
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm

3. **Run the code:**
- Navigate to the `Code` folder.
- Open the Jupyter Notebook `Store_Sales_Forecasting.ipynb`.
- Run all cells to reproduce the data preprocessing, feature engineering, and model training steps.

## Data Source
The dataset is sourced from the **Store Sales - Time Series Forecasting** competition on Kaggle.
*Note: Due to file size limits, the raw data is not included in this repository. You can download it directly from [Kaggle](https://www.kaggle.com/c/store-sales-time-series-forecasting/data) and place the CSV files in a `Data/` folder.*

## Results
Our tuned LightGBM model achieved an RMSLE of **0.5464**, significantly outperforming the baseline model (0.6876).

## License
This project is licensed under the MIT License - see the LICENSE file for details.


