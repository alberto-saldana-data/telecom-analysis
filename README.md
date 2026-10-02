
# Customer Analysis - ConnectaTel

## Project Objective

Analyze ConnectaTel's customer behavior to identify consumption patterns, user segments, and atypical behaviors that can support actionable business recommendations.

The analysis uses information recorded through 2024 and aims to support decision-making related to customer segmentation, service usage, retention, and improvement of the plans offered.

## Datasets Used

The project uses three datasets:

- `plans.csv`: information about the available plans, including prices, included minutes, included GB, and additional costs.
- `users.csv`: customer information, including age, city, registration date, plan, and churn status.
- `usage.csv`: information about actual service usage, mainly calls and text messages.

## Analysis Stages

The analysis was developed through the following stages:

1. Initial data loading and exploration.
2. Review of data types and missing values.
3. Identification and treatment of outliers and inconsistencies.
4. Statistical analysis of the variables.
5. Construction of customer-level usage metrics.
6. Identification of customer segments by age and usage level.
7. Detection of consumption patterns and users with extreme behavior.
8. Development of conclusions and business recommendations.

## Main Areas of Analysis

The analysis focused mainly on:

- Customer age distribution.
- Service usage levels.
- Number of calls and text messages.
- Call duration.
- Differences in behavior between plans.
- Users with extreme consumption levels.
- Usage patterns relevant to customer segmentation.
- Potential retention and plan differentiation opportunities.

## Business Recommendations

Based on the analysis, recommendations were developed around:

- Identifying high-consumption customers and subsequently analyzing their economic value.
- Segmenting customers according to age and usage level.
- Evaluating the differentiation between Basic and Premium plans.
- Analyzing opportunities to improve the value proposition of existing plans.
- Exploring potential customer retention strategies.
- Preserving and analyzing extreme behaviors as potential profiles of intensive users.

## How to Run the Project

The analysis was developed in Python using a Jupyter Notebook.

To reproduce the analysis:

1. Download or open the `S7 Ver_Est_Project_ConnectaTel.ipynb` notebook.
2. Open it in Google Colab or Jupyter Notebook.
3. Load the `plans.csv`, `users.csv`, and `usage.csv` datasets.
4. Run the notebook cells in order.
5. Review the results, visualizations, conclusions, and recommendations.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Google Colab

## 📁 Main File

`S7 Ver_Est_Project_ConnectaTel.ipynb`

This notebook contains the complete process of data exploration, data cleaning, statistical analysis, customer segmentation, and business recommendations.

## Copyright

© 2026 Alberto Saldana. All rights reserved.

This project is presented for portfolio and educational purposes. The code, analysis, and written content may not be reproduced, distributed, modified, or used commercially without permission.
