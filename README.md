# 📈 Marketing Campaign Performance Analysis

## Project Overview

This project analyses and compares the performance of **Facebook and AdWords advertising campaigns** over 2019.

The objective is to determine which advertising platform performs better in terms of **views, clicks, conversions, engagement, and cost-effectiveness**, while also identifying relationships and trends within campaign performance.

The dataset contains **365 daily observations**, covering January 1, 2019 to December 31, 2019.

## 🎯 Business Objective

Determine which advertising platform delivers better campaign performance and identify factors that can help improve marketing efficiency and resource allocation.

## 📁 Dataset

The dataset contains daily performance metrics for both Facebook and AdWords, including:

* Ad views
* Ad clicks
* Ad conversions
* Advertising cost
* Click-through rate (CTR)
* Conversion rate
* Cost per click (CPC)

The dataset contains **365 rows and 17 columns**.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Statsmodels
* Jupyter Notebook

## 🔍 Analysis Performed

### Exploratory Data Analysis

* Data cleaning and type conversion
* Descriptive statistics
* Campaign performance comparison
* Conversion analysis
* Click and conversion relationships
* Cost-effectiveness analysis

### Statistical Analysis

* Correlation analysis
* Hypothesis testing
* Linear regression
* R² and prediction analysis
* Time-series analysis
* Seasonal decomposition
* Cointegration analysis

## 📊 Key Findings

Facebook generated a higher average number of daily conversions than AdWords:

| Metric                    |  Facebook |  AdWords |
| ------------------------- | --------: | -------: |
| Average daily clicks      |     44.05 |    60.38 |
| Average daily conversions | **11.74** | **5.98** |

The dataset therefore shows that AdWords generated more clicks on average, while Facebook generated substantially more conversions.

The analysis also investigates the relationship between clicks and conversions and applies linear regression to evaluate how well clicks explain conversion performance.

The regression model is further used to estimate expected Facebook conversions for different click volumes. For example:

* **50 clicks → approximately 13 expected conversions**
* **80 clicks → approximately 19.31 expected conversions**

Time-series techniques are used to examine campaign behaviour over the year, while a cointegration test is applied to investigate the long-term relationship between selected campaign variables.

## 💡 Business Insights

The analysis suggests that campaign evaluation should not rely on clicks alone.

AdWords generated a higher average number of daily clicks, but Facebook generated a higher average number of daily conversions. This highlights the importance of evaluating campaigns using multiple KPIs, including:

* Clicks
* Conversions
* Conversion rate
* Cost
* Cost per click
* Cost-effectiveness

The analysis also demonstrates how statistical modelling can be used to move from descriptive reporting toward predictive marketing analytics.

## 📌 Analytical Approach

The project combines:

```text
Data Cleaning
      ↓
Exploratory Analysis
      ↓
Campaign Comparison
      ↓
Correlation Analysis
      ↓
Hypothesis Testing
      ↓
Regression Analysis
      ↓
Prediction
      ↓
Time-Series Analysis
      ↓
Business Insights
```

## 📂 Repository Contents

```text
Marketing-Campaign-Performance-Analysis/
│
├── README.md
├── Marketing_Campaign_Analysis.ipynb
├── marketing_campaign.csv
└── images/
```

### Notebook

`Marketing_Campaign_Analysis.ipynb` contains the complete analysis, visualizations, statistical tests, regression models, predictions, and conclusions.

## 👤 Author

**Bharat Reddy**

MSc Data Analytics | Business Analytics | Python | SQL | Power BI
