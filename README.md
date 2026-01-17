# 📊 2024 Global Data Salary Analysis
**HR Consultancy Project | Salary Trend Prediction & Insights**

## Executive Summary
Our analysis of **57,194 records** spanning 2020–2024 shows that while Data Scientists ($167,297) share similar raw averages, the underlying market mechanics are far more nuanced.

### 🚀 Model Performance
By implementing a **log-linear regression model**, we achieved:
* **Adjusted $R^2$:** 0.3042
* **Mean Absolute Error (MAE):** $46,972
* **Improvement:** This represents a **300% improvement** in predictive accuracy over the baseline competitor ($R^2=0.10$).

### 💡 Key Strategic Drivers
When controlling for all factors, the following variables emerged as the strongest predictors of salary:
* **Machine Learning Premium:** ML roles command a **54.6% premium**.
* **Geographic Influence:** US-based roles provide a **53.7% salary lift** over international roles.
* **Remote Dynamics:** Contrary to expectations, "Remote" roles only see a minor 7.3% reduction, while **"Hybrid" roles face a significant 29.7% penalty**.

### 🎯 Final Recommendation
To further reduce predictive error, future data collection should prioritize:
1. **Candidate Skillsets:** Specific languages and tools.
2. **Metropolitan Locations:** Granular data to account for cost-of-living variances.

## 🛠️ Skills & Tools Used
* **Languages:** R (Tidyverse)
* **Statistical Modeling:** Log-linear Regression, Predictive Accuracy Benchmarking ($R^2$ improvement)
* **Data Manipulation:** Data cleaning, type conversion (`str`), and categorical counting (`distinct`, `count`)
* **Domain Knowledge:** HR Analytics, Salary Benchmarking, and Remote Work Impact Analysis

---
### 📂 Dataset
The analysis is based on a survey of **57,194 records** (2020–2024) provided in `salaries.csv` by a global HR consultancy.

---
*This analysis was conducted using R and the Tidyverse as part of a DataCamp professional competition.*
