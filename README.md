# week-7
Introduction to Statistics for Data Science

# Statistical Business Analysis using Python

##  Project Overview

This project demonstrates the application of **statistics for data science** to analyze business data. The analysis focuses on **descriptive statistics, hypothesis testing, correlation analysis, confidence intervals, and regression modeling** to extract meaningful business insights and support data-driven decision-making.

The project follows a **structured, step-by-step statistical workflow** commonly used by data analysts and data scientists in real-world business scenarios.

## Objectives

* Summarize business data using descriptive statistics
* Analyze data distribution and normality
* Perform multiple hypothesis tests
* Identify correlations between business metrics
* Calculate confidence intervals for key measures
* Build and evaluate a regression model
* Translate statistical findings into actionable business insights

##  Project Structure

Statistical_Business_Analysis/
│
├── statistical_analysis.ipynb      # Complete statistical analysis notebook
├── business_data.csv               # Business dataset used for analysis
├── statistical_report.pdf          # Final statistical summary report
├── hypothesis_tests_results.txt    # Hypothesis testing outputs
├── requirements.txt                # Project dependencies
└── README.md                       # Project documentation

##  Tools & Technologies

 **Programming Language:** Python
 **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scipy
  * scikit-learn
 **Environment:** Jupyter Notebook

##  Statistical Concepts Covered

###  Descriptive Statistics

* Mean, Median, Mode
* Standard Deviation
* Data summary using `.describe()`

## Probability & Data Distribution

* Histograms
* Density plots
* Normality testing (Shapiro-Wilk)

## Correlation Analysis

* Pearson correlation coefficient
* Correlation heatmap
* Business metric relationship analysis

## Hypothesis Testing

* One-sample t-test
* Independent two-sample t-test
* ANOVA
* p-value interpretation

## Confidence Intervals

* 95% confidence intervals
* Margin of error calculation

## Regression Analysis

* Linear regression
* R-squared evaluation
* Marketing spend vs sales analysis

##  Sample Insights

Average Sales: $45,200 ± $3,400 (95% CI)
Correlation (Sales vs Marketing Spend): 0.78 (Strong Positive)
Hypothesis Test Result: p = 0.0012 → Statistically Significant
Regression R² Score: 0.61


## Business Insights & Recommendations

* Strong positive relationship observed between **marketing spend and sales**
* Marketing expenditure has a **statistically significant impact on revenue**
* Regression model explains a substantial portion of sales variability
* Data-driven recommendation to optimize marketing investment strategy


## How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/Statistical_Business_Analysis.git
```

2. Navigate to the project folder:

```
cd Statistical_Business_Analysis
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Open the notebook:

```
jupyter notebook statistical_analysis.ipynb
```

---

## Dataset

The dataset contains business metrics such as:

* Sales
* Marketing Spend
* Profit
* Region / Category information

*(Dataset is either simulated or anonymized for learning purposes.)*

---



