# Data_Analysis_Automation_Pipeline Using Python & AI

This repository contains two fully automated data-analysis pipelines designed to streamline exploratory data analysis (EDA), data cleaning, feature engineering, and summary reporting for any structured dataset.

These pipelines were built after completing my foundational training in traditional data analysis, and now I am extending those skills by integrating AI-powered automation to significantly reduce manual effort and improve analytical efficiency.

Overview of Pipelines
ML_Pipeline_Automation
A fully generalized machine-learning preprocessing pipeline that prepares any tabular dataset for modeling.

✔ Key Features

Automatic data cleaning

Missing-value handling (numeric & categorical)

Automated encoding for categorical features

Outlier detection & optional removal

Feature scaling (MinMax / StandardScaler)

Train–test split automation

Model-ready dataset output

Modular architecture allowing plug-and-play ML models

Typical Workflow
Load dataset (CSV, Excel, SQL extract)

Standardize column formats

Clean data

Detect & handle missing values

Encode categorical variables

Scale numeric variables

Export ML-ready dataset

Ideal Use Cases
Speeding up ML experimentation

Automating preprocessing for new datasets

Reusable template for ML projects

Data_Analyst_Automation (EDA + Cleaning + Reporting Pipeline)
A more analyst-focused pipeline that generates a complete structured EDA output without writing any code manually.

✔ Key Features

Automatic schema detection

Missing-value profiling

Data-type correction

Duplicate detection & removal

Summary statistics for all numeric columns

Frequency analysis for all categorical columns

Outlier profiling

Downloadable clean dataset

Summary dictionary for documentation

Typical Workflow
Load dataset

Detect issues (missing, duplicates, types)

Clean the dataset

Generate analytics report

Surface insights (skewed variables, anomalies, distributions)

Ideal Use Cases
Exploratory analysis

Preparing dashboards for BI tools

Automated reporting for new datasets

QA of incoming data pipelines

Why These Pipelines Were Created
After completing my foundational learning in traditional data analysis (SQL, Excel, statistics, manual EDA), I wanted to:

✔ Reduce repetitive work in cleaning & profiling datasets ✔ Eliminate manual errors ✔ Speed up my analytics workflow ✔ Build reusable components ✔ Apply AI-driven automation to real-world processes

These pipelines are the result-designed to handle dataset, generate insights automatically, and drastically minimize manual intervention.

Tech Stack
Component Technology Language Python 3.10+ Libraries Pandas, NumPy, Scikit-learn, Seaborn/Matplotlib (optional) Automation AI-generated dynamic functions + modular Python scripts Input Types CSV, Excel, SQL Exports Output Types Cleaned Dataset, Report Dictionary, Encoded ML Dataset

Repository Structure (Recommended)
├── ML_Pipeline_Automation.ipynb ├── Data_Analyst_Automation.ipynb ├── sample_datasets/ │ ├── finance_data.csv │ ├── retail_sales.csv │ └── customer_churn.xlsx ├── README.md └── outputs/ ├── cleaned_dataset.csv ├── profiling_report.json └── encoded_ml_dataset.csv

How to Use
Clone Repository
git clone https://github.com/your-username/data-analysis-automation

Install Dependencies
pip install -r requirements.txt

Run Pipeline
Open either notebook

Upload dataset

Run all cells → automated output

Both notebooks will detect your dataset structure and automatically execute the appropriate process.
