# 📊 Telco Customer Churn — Exploratory Data Analysis (EDA)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Project-EDA-orange" alt="EDA"/>
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Project Status"/>
</p>

## 📌 Project Overview

Customer churn occurs when customers stop using a company's services. Understanding why customers leave helps businesses improve customer satisfaction, strengthen customer retention, and make better decisions.

This project performs **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset to understand customer characteristics, explore churn patterns, and identify factors associated with customer churn.

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Inspect data types and summary statistics.
- Identify missing values and duplicate records.
- Analyse customer churn distribution.
- Explore relationships between customer attributes and churn.
- Visualise important patterns using charts and graphs.
- Derive useful business insights from the analysis.

## 🛠️ Tools & Technologies

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" alt="Python" title="Python"/>
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="50" alt="Pandas" title="Pandas"/>
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="50" alt="NumPy" title="NumPy"/>
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="50" alt="Matplotlib" title="Matplotlib"/>
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="50" alt="Jupyter Notebook" title="Jupyter Notebook"/>
  &nbsp;
  <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="90" alt="Seaborn" title="Seaborn"/>
</p>

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive analysis |
| VS Code | Development environment |
| GitHub | Project hosting and version control |

## 📂 Project Structure

```text
Telco-Customer-Churn-EDA/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── customer_churn_eda.ipynb
│
├── reports/
│
└── README.md
```

*Note: The dataset filename and folder structure above should match the files actually present in your repository.*

## 📁 Dataset Description

The Telco Customer Churn dataset contains customer information related to telecommunications services, account details, service subscriptions, billing, and churn status.

Example attributes include:

- CustomerID
- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- InternetService
- Contract
- MonthlyCharges
- TotalCharges
- Churn

The exact columns depend on the version of the dataset used in the project.

## 🔍 Exploratory Data Analysis

The analysis covers the following areas:

### 1. Data Inspection
- Display the first and last few records.
- Examine the number of rows and columns.
- Inspect column names and data types.
- Generate descriptive statistics.

### 2. Data Quality Checks
- Check for missing values.
- Identify duplicate records.
- Inspect inconsistent or unexpected values.
- Review data types that may require correction.

### 3. Customer Churn Analysis
- Examine the distribution of customers who churned and those who stayed.
- Compare churn patterns across selected customer attributes.
- Explore the relationship between contract type and churn.
- Examine tenure and monthly charges in relation to churn.

### 4. Data Visualisation
- Use bar charts to compare categories.
- Use histograms to explore numerical distributions.
- Use count plots to compare churn groups.
- Use other suitable visualisations to understand relationships in the data.

## 💡 Key Business Questions

1. What proportion of customers have churned?
2. Which contract types are associated with higher churn?
3. How does customer tenure relate to churn?
4. Do monthly charges differ between churned and retained customers?
5. Which internet service categories have different churn patterns?
6. Is churn associated with payment method?
7. How do additional services relate to customer retention?
8. Are there differences in churn across customer groups?
9. Which customer attributes appear most strongly associated with churn?
10. What insights could help the company improve customer retention?

## 📈 Key Findings

The key findings should be based on the actual outputs of the notebook, including the tables, charts, and comparisons.

Use this section to summarise the most important patterns observed during the analysis. Avoid claiming that a particular factor causes churn unless the analysis supports that conclusion.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use VS Code with the Jupyter extension.

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL.

### Step 2: Open the project folder

```bash
cd YOUR_PROJECT_FOLDER
```

Replace `YOUR_PROJECT_FOLDER` with the actual folder name.

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Add the dataset

Place the Telco Customer Churn CSV file inside the `data/` folder.

Ensure that the filename and file path match the path used in the notebook.

### Step 5: Open the notebook

Open the following file in VS Code or Jupyter Notebook:

`notebooks/customer_churn_eda.ipynb`

### Step 6: Run the analysis

Run the notebook cells in order to reproduce the data inspection, analysis, visualisations, and findings.

## 🌟 Learning Outcomes

Through this project, I gained practical experience in:

- Exploring real-world datasets using Python.
- Performing data inspection and quality checks.
- Manipulating data using Pandas and NumPy.
- Creating meaningful visualisations.
- Asking business-relevant analytical questions.
- Interpreting data patterns and communicating insights.
- Managing and showcasing a project using GitHub.

## 🔮 Future Improvements

- Perform deeper statistical analysis.
- Build an interactive dashboard.
- Develop a machine learning model to predict customer churn.
- Evaluate model performance using appropriate metrics.
- Suggest data-driven customer retention strategies.

## 👩‍💻 Author

**Dhilruba M**

B.Tech — Artificial Intelligence and Data Science

Interested in Data Analytics, Artificial Intelligence, and Software Development.

## 📜 Disclaimer

This project is intended for educational and learning purposes. The analysis and conclusions depend on the dataset and methods used.

---

⭐ If you find this project useful, consider giving the repository a star!

