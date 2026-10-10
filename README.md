# Customer Churn & Retention Analysis
### End-to-End Exploratory Data Analysis (EDA) using Python

## Project objective
Explore customer churn patterns in a telecommunications dataset and identify data-supported opportunities to improve customer retention. This project focuses on EDA and business insights; it does **not** build a machine-learning model.

## Dataset
Use the IBM Telco Customer Churn sample dataset (commonly distributed as `WA_Fn-UseC_-Telco-Customer-Churn.csv`).

Download source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

After downloading, extract the CSV and place it in the `data/` folder. Keep the original column names.

## Project structure
- `notebooks/customer_churn_eda.ipynb` — complete analysis notebook
- `data/` — place the downloaded CSV here
- `reports/EDA_Summary_Template.md` — final report template
- `requirements.txt` — Python dependencies

## Run the project
1. Install Python and Jupyter, or use Google Colab.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Put the dataset CSV in `data/`.
4. Open `notebooks/customer_churn_eda.ipynb`.
5. Run the notebook cells from top to bottom.

If using Google Colab, upload the CSV when prompted by the notebook, or update `DATA_PATH` to the file location.

## Important notes
- The notebook checks for missing values, duplicate rows, data types and potential outliers.
- Cleaning choices are documented rather than applied blindly.
- Churn percentages are calculated from the available data. Do not claim a cause-and-effect relationship from EDA alone.
- Run all cells and replace report-template placeholders with your actual findings before submitting.
