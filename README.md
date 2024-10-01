# PowerCo SME Churn Analysis for BCG DS

## Project Overview
PowerCo, a major utility provider in the gas and electricity sectors, is facing significant customer churn in their SME (Small and Medium Enterprise) segment. They have partnered with BCG, The Bosoton Consulting Group to identify the key drivers behind this churn and reduce customer turnover. Our hypothesis is that **price sensitivity** plays a major role, and we aim to build a predictive model to help PowerCo retain its SME customers.

## Objective
The goal of this project is to:
- **Analyze** historical customer and pricing data.
- **Test** the hypothesis that price changes drive SME customer churn.
- **Build** a predictive model to identify customers most at risk of churning.
- **Propose** strategies to reduce churn, including a potential **20% discount** to retain price-sensitive customers.

---

## Task 1: Business Understanding and Hypothesis Testing

### Problem Statement
The key hypothesis is that **price changes are a significant factor in SME customer churn**. My approach includes:
- **Understanding** key factors for churn, such as pricing, usage patterns, and contract terms.
- **Formulating** the problem as a data science task: predicting churn likelihood based on historical data.
- **Collecting** necessary data: customer records, usage data, pricing history, and churn indicators.
- **Analyzing** customer behavior using key factors like usage patterns and contract tenure.

---

## Task 2: Exploratory Data Analysis (EDA)

### Key Data Provided:
- **Historical customer data**: Usage patterns, sign-up dates, forecasted usage.
- **Historical pricing data**: Fixed and variable price structures.
- **Churn indicator**: Whether a customer has churned.

### Exploratory Steps:
- **Data Inspection**: Examined types, statistics, and distributions.
- **Correlation Check**: Verified relationship between price changes and churn behavior.
- **Pattern Identification**: Explored how usage patterns may impact sensitivity to price.

### Findings:
- A strong correlation between **price increases** and **customer churn** was observed.
- High-usage customers were particularly **price-sensitive**.
- **Data augmentation** opportunities include customer satisfaction data and market price comparisons.

---

## Task 3: Feature Engineering and Modelling

### Key Features Engineered:
- **Price elasticity**: Sensitivity of a customer’s churn behavior to price changes.
- **Usage fluctuation**: The effect of usage variations over time on churn.
- **Customer tenure**: How long-term customers behave in relation to churn.

### Model Training:
- Trained a **Random Forest Classifier** on engineered features.

### Evaluation:
- **Advantages**: Handles non-linear relationships and interactions between variables effectively.
- **Disadvantages**: Model complexity makes interpretation harder, and it requires significant computational power.

### Financial Impact:
The model suggests that offering a **20% discount** to high-risk customers could substantially **reduce churn** and **retain revenue** for PowerCo.

---

## Task 4: Findings and Recommendations

### Key Takeaways:
- The **churn prediction model** provides actionable insights into customer retention.
- **Discount strategy**: A 20% discount could effectively reduce churn among price-sensitive customers.

### Summary Slide:
A synthesized abstract slide has been created, highlighting the **churn prediction accuracy** and its potential **business impact**.

---

## Conclusion
This project supports PowerCo in reducing churn by identifying price-sensitive SME customers. Through data-driven insights and predictive modelling, we can **minimize customer turnover** and implement strategic **discount offers** to retain high-value clients.

