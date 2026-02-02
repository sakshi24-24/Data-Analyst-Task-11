# 📊 A/B Testing: Marketing Campaign Analysis
**Data Analyst Internship | Task 11** 🚀

## 🎯 Project Objective
The goal of this project is to analyze an A/B test dataset to determine if a new advertisement campaign ("ad") leads to a higher conversion rate compared to a control group ("psa"). 📈

## 🧪 Methodology
* **Hypothesis Testing:** Conducted a **Chi-Square Test of Independence** since the outcome variable (converted) is categorical (True/False). 📉
* **Significance Level (α):** 0.05. ⚖️
* **Tools Used:** Python (Google Colab), Pandas, Scipy, Seaborn, Matplotlib. 🐍

## 🔍 Results & Findings
* **Control Group (PSA) Conversion Rate:** 1.79% 🔘
* **Treatment Group (Ad) Conversion Rate:** 2.55% 💰
* **P-Value:** 1.99e-13 (Extremely significant) ⭐
* **Confidence Interval:** The 95% CI for the difference does not include zero, confirming the lift is statistically valid. ✅

## 💡 Business Recommendation
Based on the statistical significance, the advertisement campaign is highly effective. I recommend **scaling the ad campaign** as it provides a clear and measurable increase in conversion compared to the PSA group. 🚀🏁

## 📁 Repository Contents
* `task11_abtest.ipynb`: The complete Python analysis notebook. 📓
* `ab_test_summary.csv`: Key statistical metrics (Conversion rates, P-value). 📄
* `final_recommendation.txt`: Formal business decision summary. 📝
* `marketing_AB.csv`: The raw dataset used for analysis. 🗃️
