# Task 1: Data Preparation & Customer Analytics

## Overview

This task focuses on preparing the retail transaction data for analysis and exploring customer purchasing behaviour within the **Chips** category.

The objective is to clean and integrate multiple datasets, identify meaningful customer segments, analyze purchasing trends, and generate business insights that support strategic decision-making.

---

## Business Problem

The Category Manager wants to better understand:

- Which customer segments contribute the most to chip sales?
- What purchasing patterns exist across different customer groups?
- Which factors influence customer spending?
- What business recommendations can improve future category performance?

The findings from this analysis provide the foundation for the subsequent trial store evaluation and business presentation.

---

## Objectives

The analysis was completed through the following stages:

- Data quality assessment
- Missing value and outlier detection
- Data cleaning and preprocessing
- Feature engineering
- Dataset merging
- Exploratory Data Analysis (EDA)
- Customer segmentation
- Business insight generation

---

## Dataset

The analysis uses two datasets provided by Quantium.

| Dataset | Description |
|----------|-------------|
| **QVI_transaction_data.xlsx** | Customer transaction records including products, quantities and sales. |
| **QVI_purchase_behaviour.csv** | Customer demographic information including life stage and premium customer segments. |

These datasets were cleaned, validated and merged to produce the final analysis dataset.

---

## Data Preparation

The following preprocessing steps were performed:

- Examined data structure and summary statistics
- Checked for missing values
- Removed invalid and inconsistent records
- Corrected data formats
- Extracted product brand names
- Derived chip packet sizes
- Merged transaction and customer datasets
- Exported the cleaned dataset for further analysis

---

## Exploratory Data Analysis

The analysis included:

- Monthly sales trend analysis
- Customer segment analysis
- Brand performance
- Packet size analysis
- Sales contribution by life stage
- Sales contribution by premium customer segment
- Purchasing behaviour across customer groups

Multiple visualizations were created to better understand purchasing behaviour and identify meaningful trends.

---

## Key Business Insights

Some of the major findings include:

- Monthly chip sales remained relatively stable throughout the analysis period.
- Mainstream customers contributed the highest overall sales across several customer groups.
- Family households represented an important customer segment for the Chips category.
- Customer purchasing behaviour varied across different life stages and affluence segments.
- These insights help identify customer groups that can be targeted through future marketing strategies.

---

## Deliverables

This folder contains:

```
Task_1
│
├── Analysis.ipynb
├── Analysis_PDF.pdf
├── QVI_transaction_data.xlsx
├── QVI_purchase_behaviour.csv
└── QVI_Merged_Cleaned_Data.csv
```

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Customer Analytics
- Customer Segmentation
- Retail Analytics
- Data Visualization
- Business Insight Generation
- Python
- Pandas
- NumPy
- Matplotlib

---

## Conclusion

The cleaned and integrated dataset enabled a detailed analysis of customer purchasing behaviour within the Chips category. The insights generated in this task serve as the analytical foundation for evaluating trial store performance in Task 2 and developing business recommendations in Task 3.