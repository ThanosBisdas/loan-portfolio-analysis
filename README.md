# US Loan Portfolio Analysis — Power BI + Python

An end-to-end portfolio project that combines **Power BI dashboarding** with **Python-based data analysis and machine learning** on a US loan portfolio dataset.

This project was designed to showcase both:
- **business intelligence, reporting, and storytelling**
- **data cleaning, exploratory analysis, predictive modeling, and interpretation**

---

## Project Overview

This project analyzes a US loan portfolio from multiple perspectives:

- portfolio volume and repayment performance
- geographic distribution of lending activity
- borrower credit and risk segmentation
- loan status composition and default behavior
- default prediction using machine learning

The project is split into two complementary parts:

### Power BI
A multi-page interactive dashboard for business and portfolio analysis.

### Python
A notebook-based analytical workflow covering:
- data cleaning
- exploratory data analysis
- supervised default prediction
- model interpretation

---

## Power BI Report Pages

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

### `01_data_cleaning_eda.ipynb`
- data loading
- cleaning and feature engineering
- exploratory analysis
- state-level and risk visualizations

### `02_default_prediction.ipynb`
- binary target creation
- preprocessing pipelines
- Logistic Regression baseline
- Random Forest model
- model evaluation

### `03_model_interpretation.ipynb`
- logistic regression coefficient interpretation
- random forest feature importance
- business interpretation of risk drivers

---

## Machine Learning Framing

For predictive modeling, the default problem was framed as a **binary classification task**:

- `Fully Paid` → 0
- `Charged Off` → 1

`Current` loans were excluded because they do not represent a final observed loan outcome.

To avoid **target leakage**, repayment-related variables known only after origination were excluded from the predictive feature set.

---

## Key Skills Demonstrated

### Power BI
- Power Query data preparation
- calculated columns and measures
- KPI reporting
- time-based analysis
- geographic mapping
- slicers and interactivity
- dashboard design and visual storytelling

### Python / Data Science
- pandas-based data cleaning
- feature engineering
- exploratory data analysis
- binary classification
- scikit-learn preprocessing pipelines
- Logistic Regression
- Random Forest
- model interpretation

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
