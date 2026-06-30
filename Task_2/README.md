# Task 2: Experimentation & Trial Store Evaluation

## Overview

This task focuses on evaluating the effectiveness of a retail store trial conducted across three selected trial stores. The objective is to determine whether the new in-store layout resulted in measurable improvements in sales performance by comparing each trial store with a carefully selected control store.

A data-driven methodology was used to identify comparable control stores, evaluate trial performance, and provide business recommendations based on the observed results.

---

## Business Problem

The Category Manager wants to determine whether the new store layout should be implemented across additional stores.

To answer this question, the following business problems were addressed:

- Which stores are most comparable to each trial store?
- How should suitable control stores be selected?
- Did the trial stores outperform their respective control stores?
- Was the increase in sales driven by more customers or changes in purchasing behaviour?
- Which trial stores demonstrated the strongest business impact?

---

## Objectives

The analysis was completed through the following stages:

- Monthly store performance aggregation
- Feature engineering
- Trial period identification
- Control store selection
- Correlation analysis
- Magnitude similarity analysis
- Trial performance evaluation
- Business recommendation generation

---

## Dataset

This task uses the processed dataset generated in **Task 1**.

| Dataset | Description |
|----------|-------------|
| **QVI_data.csv** | Cleaned monthly retail dataset containing store-level performance metrics used for trial evaluation. |

---

## Methodology

The trial evaluation was completed using the following analytical approach:

### 1. Monthly Performance Metrics

Monthly store-level metrics were calculated, including:

- Total Sales
- Total Customers
- Average Transactions per Customer

These metrics formed the basis for comparing trial and candidate control stores.

---

### 2. Control Store Selection

A reusable comparison function was developed to identify the most suitable control store for each trial store.

The comparison considered:

- Sales correlation
- Customer correlation
- Transaction correlation
- Magnitude similarity

The final similarity score combined both trend similarity and absolute performance similarity.

Selected Control Stores:

| Trial Store | Control Store |
|-------------|---------------|
| Store 77 | Store 17 |
| Store 86 | Store 155 |
| Store 88 | Store 237 |

---

### 3. Trial Assessment

Each trial store was compared against its corresponding control store during the trial period.

Performance was evaluated using:

- Sales Growth
- Customer Growth
- Average Transactions per Customer
- Overall Trial Impact

---

## Key Business Insights

The analysis identified several important findings:

- Store 77 demonstrated the strongest positive trial impact with noticeable improvements in both sales and customer growth.
- Store 86 showed moderate improvements, indicating a positive but less pronounced trial effect.
- Store 88 delivered only limited improvement, suggesting the trial layout had minimal impact at this location.
- Customer growth was the primary driver of improved sales performance rather than increased purchasing frequency.

---

## Deliverables

This folder contains:

```
Task_2
│
├── Analysis.ipynb
├── Analysis_Task02.pdf
└── QVI_data.csv
```

---

## Skills Demonstrated

- Retail Analytics
- Experimental Design
- Trial Store Evaluation
- Control Store Selection
- Correlation Analysis
- Similarity Measurement
- Statistical Analysis
- Business Analytics
- Data Visualization
- Python
- Pandas
- NumPy
- Matplotlib

---

## Conclusion

A structured trial evaluation framework was developed to assess the effectiveness of the new store layout. By selecting statistically comparable control stores and measuring performance across multiple business metrics, the analysis provided evidence-based recommendations regarding the success of each trial store.

The insights generated in this task form the analytical foundation for the executive business presentation developed in **Task 3**.