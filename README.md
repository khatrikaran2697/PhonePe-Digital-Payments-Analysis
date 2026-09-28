# PhonePe Digital Payments Analysis

## Project Overview

This project analyzes PhonePe digital payment transaction, user, device, district, and demographic data across Indian states and districts.

The analysis follows the provided PhonePe Digital Payments case study and uses Python for data loading, exploratory data analysis, data-quality checks, merging, correlation analysis, visualization, and business insights.

## Objectives

- Understand transaction and user trends across states and quarters
- Analyze transaction types and device-brand usage
- Identify high-population districts by state
- Calculate average transaction value (ATV)
- Analyze app-open trends
- Reconcile district-level and state-level data
- Study relationships between demographic variables and transaction activity
- Calculate user/population and device-usage ratios
- Produce business-oriented insights and visualizations

## Datasets

The Excel workbook contains these analysis sheets:

1. `State_Txn and Users`
2. `State_TxnSplit`
3. `State_DeviceData`
4. `District_Txn and Users`
5. `District Demographics`

An additional `Admin` sheet is present in the workbook but is not required for the case-study analysis.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel / OpenPyXL

## Key Analysis Areas

### Data Understanding
- Dataset structure
- Data types
- Descriptive statistics
- Missing-value analysis
- State and district counts

### Exploratory Data Analysis
- Transaction volume by state
- Transaction amount by state
- Transaction-type analysis
- Device-brand analysis
- ATV analysis
- App-open trends
- District population analysis

### Data Quality
- District-level vs state-level reconciliation
- Identification of discrepancies

### Advanced Analysis
- Registered users to population ratio
- Population density vs transaction volume
- Average transaction amount per user
- Device-brand usage ratio
- Correlation analysis

### Visualization
- Time-series charts
- Bar charts
- Pie chart
- Scatter plot
- Population-density visualization

## Repository Structure

```text
PhonePe_Digital_Payments_Analysis/
│
├── PhonePe_Digital_Payments_Analysis.ipynb
├── README.md
├── requirements.txt

```

## How to Run

1. Clone or download this repository.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run `PhonePe_Digital_Payments_Analysis.ipynb`.

## Portfolio Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Aggregation
- GroupBy operations
- Data Merging
- Data Validation
- Correlation Analysis
- Data Visualization
- Business Analysis
- Python for Data Analysis
