# US Loan Portfolio Analysis — Power BI + Python

An end-to-end portfolio project that combines **business intelligence in Power BI** with **data analysis and credit risk modeling in Python** on a US loan dataset.

This project was designed to showcase both:
- **dashboarding, reporting, and storytelling**
- **data cleaning, exploratory analysis, predictive modeling, and interpretation**

---

## Project Overview

The goal of this project is to analyze a US loan portfolio from multiple perspectives:

- portfolio volume and repayment performance
- geographic distribution of lending activity
- borrower credit and risk segmentation
- loan status composition and default behavior
- default prediction using machine learning

The project is split into two complementary parts:

### 1. Power BI
A multi-page interactive dashboard for business and portfolio analysis.

### 2. Python
A notebook-based analytical workflow covering:
- data cleaning
- exploratory data analysis
- supervised default prediction
- model interpretation

---

## Power BI Report Pages

The Power BI dashboard includes the following pages:

### 1. Executive Overview
High-level business view of:
- total loans
- total funded amount
- total payment received
- default rate
- funded amount trend
- loan status breakdown
- geographic distribution of funded volume

### 2. Geographic Analysis
State-level portfolio view showing:
- top states by funded amount
- top states by default rate
- map-based portfolio distribution

### 3. Portfolio Performance
Performance and repayment analysis including:
- payment trend
- funded volume trend
- loan status composition
- payment received by status group

### 4. Borrower Credit & Risk Profile
Borrower segmentation by:
- grade
- purpose
- debt-to-income band
- interest rate band
- home ownership

### 5. Loan Detail Explorer
Detailed exploration page with:
- slicers
- loan-level table
- selected portfolio KPIs

---

## Python Workflow

The Python side of the project is organized into three notebooks:

### `01_data_cleaning_eda.ipynb`
Covers:
- dataset loading
- feature cleaning
- helper column creation
- target framing
- exploratory analysis
- geographic and risk visualizations

### `02_default_prediction.ipynb`
Covers:
- binary target creation
- train/test split
- preprocessing pipelines
- Logistic Regression baseline
- Random Forest model
- model evaluation

### `03_model_interpretation.ipynb`
Covers:
- logistic regression coefficient interpretation
- random forest feature importance
- business interpretation of risk drivers

---

## Machine Learning Framing

For predictive modeling, the default problem was framed as a **binary classification task**:

- `Fully Paid` → 0
- `Charged Off` → 1

`Current` loans were excluded from the target definition because they do not represent a final observed repayment outcome.

This notebook workflow was intentionally designed to avoid **target leakage**, excluding repayment-related fields that would not be known at origination.

---

## Key Skills Demonstrated

### Power BI
- Power Query data preparation
- calculated columns and measures
- KPI cards
- time-based reporting
- geographic mapping
- slicers and interactive filtering
- dashboard design and color theming
- report storytelling across multiple pages

### Python / Data Science
- pandas-based data cleaning
- feature engineering
- EDA with matplotlib and plotly
- binary classification
- scikit-learn preprocessing pipelines
- Logistic Regression
- Random Forest
- model evaluation and interpretation

---

## Tech Stack

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Python**
- **pandas**
- **numpy**
- **matplotlib**
- **plotly**
- **scikit-learn**

---
