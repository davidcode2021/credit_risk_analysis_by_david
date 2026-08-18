# credit_risk_analysis_by_david

# Credit Risk Analysis

## Project Objective

The objective of this project is to identify patterns associated with **low-, medium-, and high-risk customers** using current and previous loan application data.

## Data Preparation

The **current application data** and **previous application data** were cleaned separately in different Jupyter Notebooks. Data cleaning and preparation included handling missing values, correcting data types, and preparing variables for analysis.

Relevant features were also **engineered** from the available data to provide additional information for the analysis.

The cleaned datasets were then merged using the **customer ID** to create a final analytical dataset.

## Risk Classification

A predictive model was developed to estimate the **probability of credit risk** rather than producing only a binary 0/1 prediction.

The predicted probabilities were subsequently classified into three risk categories:

- **Low risk**
- **Medium risk**
- **High risk**

## Pattern Analysis

The risk categories were used to investigate characteristics associated with different levels of credit risk.

The analysis included:

- Percentage distributions across risk levels
- **Chi-square tests** to determine whether categorical variables were statistically associated with risk level
- **Cramér's V** to measure the strength of association
- Comparison of numerical loan characteristics across risk categories

The analysis focused on identifying patterns that distinguish **low-risk and high-risk customers**.

## Key Findings

Several patterns were observed across the risk categories. High-risk customers were relatively more represented among **males, customers with secondary education, working customers, laborers, drivers, and customers without cars**. In contrast, **females, customers with higher education, pensioners, and some professional occupations** were relatively more represented among low-risk customers.

However, although many features showed statistically significant associations with risk level, their **Cramér's V values were generally weak**. This indicates that the individual characteristics examined have limited ability to distinguish between low- and high-risk customers independently.

## Recommendation

The identified characteristics should be treated as **supporting indicators rather than standalone measures of credit risk**. Credit risk assessment should consider multiple customer, financial, behavioral, and loan characteristics together rather than relying on any single feature.

## Conclusion

The analysis identified several characteristics associated with different customer risk profiles. However, no individual feature demonstrated a strong association with risk level. The findings provide useful insights into the characteristics of low- and high-risk customers while highlighting the importance of considering multiple factors when assessing credit risk.


## Data Source

The datasets used in this project were obtained from the following Kaggle dataset:

**Source:** [Credit Analysis Dataset – Kaggle](https://www.kaggle.com/datasets/kapoorshivam/credit-analysis/data)

The project uses two main datasets:

- **Current application data**
- **Previous application data**

The two raw datasets are relatively large and were therefore **not uploaded to this GitHub repository** due to file-size limitations. Instead, the original datasets can be accessed through the Kaggle source provided above.

The cleaned and processed data used for the analysis was generated from these original datasets through the data preparation, feature engineering, and data integration steps described in this project.

