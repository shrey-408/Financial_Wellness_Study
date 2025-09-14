# Financial_Wellness_Study

# Behavioral and Financial Indicators of Wellness: A Machine Learning Study

### Overview

[cite_start]This project applies data science and machine learning to predict an individual's financial wellness based on their financial and demographic data[cite: 15]. [cite_start]The study addresses the challenge that many people lack awareness of their financial health, which can lead to poor financial habits and long-term negative outcomes like high debt and low savings[cite: 14, 235]. [cite_start]By developing a predictive model, this research aims to provide a data-driven foundation for creating automated, personalized financial assessment tools[cite: 26, 252].

---

### Project Goals

* [cite_start]**Analyze User Financial Data**: Create a machine learning model that analyzes user financial data, including income, savings, expenses, debt, and investment habits[cite: 16].
* [cite_start]**Classify Financial Wellness**: Categorize individuals into predefined financial wellness categories such as "Good," "Average," or "Poor"[cite: 16].
* [cite_start]**Provide Actionable Insights**: Generate insights and recommendations to help individuals improve their financial health[cite: 224].

---

### Methodology

[cite_start]The project uses a two-step modeling approach combining both unsupervised and supervised learning[cite: 552].

#### 1. Unsupervised Learning (K-Means Clustering)
* [cite_start]**Objective**: To identify natural groupings of individuals based on their financial behaviors[cite: 400].
* [cite_start]**Process**: The K-Means algorithm was used to segment survey respondents into three clusters, which were then labeled as "Financially At-Risk," "Financially Stable," and "Financially Well" based on their characteristics[cite: 403].
    * [cite_start]**Cluster 0 (Financially At-Risk)**: Characterized by low income, low savings, and high debt[cite: 403].
    * [cite_start]**Cluster 1 (Financially Stable)**: Characterized by moderate income, moderate savings, and some investments[cite: 403].
    * [cite_start]**Cluster 2 (Financially Well)**: Characterized by high income, high savings, and diversified investments[cite: 403].
* [cite_start]**Key Finding**: Savings rate, emergency funds, and debt were found to be strong differentiators between the clusters[cite: 410].

#### 2. Supervised Learning (Random Forest & Logistic Regression)
* [cite_start]**Objective**: To build a predictive model that can classify new individuals into the financial wellness categories identified by the clustering step[cite: 414].
* [cite_start]**Random Forest Classifier**: This model was developed to predict financial wellness categories[cite: 414]. [cite_start]It achieved an accuracy of approximately 82%[cite: 21, 483]. [cite_start]Feature importance analysis revealed that savings rate, debt amount, and investment behavior were the most significant predictors[cite: 22, 477].
* [cite_start]**Logistic Regression Classifier**: This model was used as a baseline, providing interpretable relationships and confirming that debt and savings rate are key factors in financial wellness[cite: 500].

---

### Key Findings and Insights

* [cite_start]**Multi-Factor Wellness**: Financial wellness is not just about income[cite: 471]. [cite_start]The study confirms it is a holistic metric influenced by a person's management of their savings, total loans, and monthly spending[cite: 472].
* [cite_start]**Debt and Savings Are Critical**: Managing debt and maintaining a consistent savings rate are more predictive of financial health than income alone[cite: 476].
* [cite_start]**Predictive Modeling is Viable**: Machine learning models, particularly the Random Forest Classifier, can effectively classify financial wellness with high accuracy (around 82%)[cite: 21, 483].
* [cite_start]**Foundation for Decision Support**: The model can be scaled into a practical, data-driven tool to provide personalized financial recommendations[cite: 486]. [cite_start]For instance, it can suggest budgeting for a "Poor" user or investing for an "Average" user[cite: 489].

---

### Limitations and Future Work

[cite_start]The study's limitations include a small sample size (150-200 records), potential self-reported data bias, and the use of a one-time data snapshot rather than time-series data[cite: 24, 335, 337].

Future research should focus on:
* [cite_start]**Expanding the Dataset**: Collecting a larger dataset to improve the model's generalizability[cite: 25, 336].
* [cite_start]**Incorporating Behavioral Factors**: Including qualitative data such as financial attitudes and risk tolerance to enhance predictive power[cite: 340, 513].
* [cite_start]**Improving Explainability**: Using explainable AI techniques to enhance transparency and increase trust in the model's predictions[cite: 25, 341].
