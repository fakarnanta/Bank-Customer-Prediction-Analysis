# Bank Marketing Campaign Analysis

[![Python](https://img.shields.io/badge/Python-Data%20Science-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/groups/me/reports/21f021f4-2498-4a0b-b6a8-c904c53f6864/a8b599842c38c8b303e0?experience=power-bi)

<img width="955" height="493" alt="image" src="https://github.com/user-attachments/assets/5e6ba76a-fc8c-4cfb-868d-1fcebb819641" />

## Executive Summary
This project employs Machine Learning classification algorithms to optimize bank telemarketing campaigns. By analyzing a dataset of over 11,000 client interactions, the project aims to predict term deposit subscriptions with high accuracy.

The resulting model achieves an **accuracy of approximately 83%**, demonstrating a strong capability to distinguish between potential subscribers and non-subscribers. The analysis highlights that operational efficiency can be drastically improved by prioritizing client engagement metrics (call duration) and leveraging historical interaction data, rather than relying on volume-based cold calling.

## 1. Project Background
Telemarketing campaigns in the banking sector are often resource-intensive and suffer from low conversion rates due to inefficient targeting.
**Objective:**
* To analyze the demographic and behavioral factors influencing a client's decision to subscribe to a term deposit.
* To build a binary classification model that identifies high-probability prospects.
* To provide actionable strategies for reducing operational costs while maximizing conversion rates.

**Methodology:**
* **Algorithm:** Classification Models (Random Forest / Decision Tree).
* **Validation:** Classification Report (Precision, Recall, F1-Score) and Confusion Matrix.
* **Data Processing:** Encoding categorical variables, handling feature scaling, and converting target variables to binary format.

## 2. Key Analysis & Insights
The exploratory data analysis (EDA) revealed critical patterns driving customer decisions.

<img width="904" height="837" alt="image" src="https://github.com/user-attachments/assets/d9cdb835-8589-4a1a-9534-d3604303eff4" />


### Factor 1: Call Duration (Engagement Metric)
* **Observation:** Call duration acts as the most significant predictor of subscription success.
* **Behavior:** There is a direct positive correlation between the length of the conversation and the likelihood of a deposit. Short interactions typically result in rejections.
* **Implication:** The quality of interaction is a more critical KPI than the quantity of calls made.

### Factor 2: Previous Campaign Outcome
* **Observation:** The success of previous marketing campaigns is a strong indicator of future behavior.
* **Behavior:** Customers who previously subscribed or had successful interactions are significantly more likely to accept new offers compared to cold leads.
* **Implication:** Retargeting "warm" leads yields a higher return on investment than acquiring new prospects.

### Factor 3: Socio-Economic Indicators
* **Observation:** Variables such as job type, housing loan status, and balance levels impact decision-making.
* **Behavior:** Specific segments, such as retired individuals or those without housing debt, show a higher propensity for term deposits due to higher liquidity.
* **Implication:** Marketing lists should be segmented based on financial freedom and liquidity profiles.

## 3. Strategic Business Recommendations
Based on the model's performance and data insights, the following strategies are proposed:

1.  **Quality-Over-Quantity Approach:**
    * Shift the operational focus from maximizing daily call volume to maximizing call duration. Train agents to engage customers in meaningful financial discussions, as the probability of conversion increases significantly with call length.

2.  **Smart Lead Prioritization:**
    * Implement a tiered calling list where customers with successful previous campaign outcomes are contacted first.
    * Use the model's prediction probability to rank remaining leads, ensuring the most likely subscribers are prioritized.

3.  **Targeted Segmentation:**
    * Develop specialized scripts and offers for high-conversion demographic groups (e.g., retirees, students) and those with higher average balances.

## Tools & Libraries Used
* **Python:** Core programming language for analysis.
* **Scikit-Learn:** Building and evaluating machine learning models.
* **Pandas & NumPy:** Data manipulation and preprocessing.
* **Matplotlib & Seaborn:** Visualization of data distributions and correlation matrices.
