# Credit Scoring Analysis & Default Prediction

An end-to-end Data Science project focused on analyzing and mitigating credit default risks for a UK-based financial institution. This project integrates statistical modeling, machine learning, and sentiment analysis to identify high-risk borrowers and understand customer service satisfaction.

---

## 🚀 Project Overview
This project aims to strengthen credit scoring practices by analyzing demographic, financial, and behavioral data. The analysis follows a rigorous 5-phase data science lifecycle:

1. **Data Management:** Merging disparate datasets, cleaning, and handling outliers.

2. **Exploratory Data Analysis (EDA):** Identifying key risk drivers.

3. **Statistical Modeling:** Building a credit scorecard using Logistic Regression.

4. **Machine Learning Comparison:** Evaluating Random Forest, Decision Trees, and Naïve Bayes.

5. **Sentiment Analysis:** Mining customer feedback to improve service quality.

---

## 📊 Key Insights
* **Default Rate:** The overall defaulter rate in the dataset is 13.23%.

* **Risk Drivers:**
* **Financial Stress:** Customers with high debt-to-income ratios (over 16%) show a significantly higher default rate of 22.1%.
* **Stability:** New employees (less than 3 years) have a high default risk of 21.6%, compared to only 3.41% for long-term employees (over 13 years).
* **Customer Sentiment:** Text mining revealed that while 75% of feedback is positive, dissatisfaction is primarily driven by "slow" processing and "lack of proactive support".

  ---

## 🛠️ Tech Stack
* **Language:** R
* **Libraries:** tidyverse (dplyr, ggplot2, tidyr), patchwork, caret, randomForest, tidytext.
* **Methods:** Binary Logistic Regression, Random Forest, Naïve Bayes, Decision Trees, Sentiment Analysis.

---

## 📂 Repository Structure
`data/`: Contains structured CSV datasets (Credit Details, Customer Info, Profiles) and unstructured customer feedback text document.
`Credit_Scoring_Analysis.Rmd`: The core analysis Rmd file. 
`outputs/`: Visual evidence of the outputs
`credit_scoring_project_presentation.ppt`: Summary of this project and insights
`README.md`: (This file) Detailed project overview and summary. 

---

## 🏁 Conclusion
The project successfully identified that financial stability indicators, particularly debt-to-income and employment duration, are the strongest predictors of default. <br> The Random Forest model was selected as the final predictive tool based on its superior performance across test AUC metrics.











