<a href="https://github.com/drshahizan/short-course/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/short-course" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/short-course/network/members"><img src="https://img.shields.io/github/forks/drshahizan/short-course" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/short-course/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/short-course" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/short-course"><img src="https://img.shields.io/github/issues/drshahizan/short-course" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/short-course/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/short-course?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Fshort-course&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

# Generative AI for Statistical Analysis

This module demonstrates how **Generative AI tools** such as **ChatGPT** or **Copilot** can assist in performing basic statistical analysis, from understanding data structure to interpreting results. The case study uses a simple dataset on household income and poverty rate across Malaysian states to show how AI can generate insights and visualization automatically.

## 🎯 Learning Objectives

By the end of this module, participants will be able to:

1. Identify data types and variable roles (categorical, numerical, independent, dependent).
2. Compute descriptive statistics (mean, median, minimum, maximum, standard deviation).
3. Analyze correlation between two continuous variables using AI-generated methods.
4. Generate and interpret a scatter plot with a regression line.
5. Write an executive summary and policy insight based on statistical findings.

## 📊 Dataset Example

| State    | Median_Income_2024 (RM) | Poverty_Rate (%) |
| -------- | ----------------------- | ---------------- |
| Selangor | 9200                    | 2.5              |
| Johor    | 7600                    | 3.8              |
| Kedah    | 5400                    | 7.2              |
| Kelantan | 4300                    | 11.4             |
| Sabah    | 4800                    | 10.6             |
| Sarawak  | 5600                    | 8.3              |

This simplified data is used to illustrate AI-powered statistical analysis.

## 💡 AI Prompt Exercises

Participants will use the following prompts step-by-step to explore how AI can analyze data automatically. Each prompt is followed by the expected result or interpretation.

### 🧩 Prompt 1: Understanding the Data

**Prompt:**

> Analyze the dataset. Identify each column’s data type (categorical or numerical) and describe what kind of statistical variable each one represents (e.g., dependent, independent, or descriptive variable).

### 📈 Prompt 2: Descriptive Statistics

**Prompt:**

> Using this dataset, calculate the mean, median, minimum, maximum, and standard deviation for both `Median_Income_2024` and `Poverty_Rate`.

### 🔗 Prompt 3: Correlation Analysis

**Prompt:**

> Compute the Pearson correlation coefficient between `Median_Income_2024` and `Poverty_Rate`. Explain in one short paragraph what this result means.

### 📉 Prompt 4: Visualization

**Prompt:**

> Create a scatter plot that shows the relationship between `Median_Income_2024` and `Poverty_Rate`, add a regression line, and label each state.

### 🗒️ Prompt 5: Executive Summary

**Prompt:**

> Write a 3–4 sentence summary explaining the relationship between income and poverty across Malaysian states.

### ✅ Example Results Summary

Descriptive statistics results show that states with higher median income have lower poverty rates.
The **Pearson correlation coefficient is approximately -0.97**, indicating a strong negative relationship between income and poverty.
The scatter plot visually confirms this trend, and the AI-generated executive summary provides a concise interpretation suitable for policy discussions.

### 🗣️ Executive Summary 

The analysis of median household income and poverty rate across six Malaysian states in 2024 shows a strong negative correlation (r = –0.97).
States with higher income experience significantly lower poverty levels, while lower-income states face higher poverty rates.
This trend indicates that income growth remains a crucial factor in reducing poverty and promoting social development.


## 🧮 Core Equations Used

Although Generative AI performs the calculations automatically, it uses the same fundamental statistical formulas. Understanding these equations helps participants validate AI outputs and maintain analytical integrity.

### **Mean (Average)**

$$
\bar{X} = \frac{\sum_{i=1}^{n} X_i}{n}
$$

### **Standard Deviation**

$$
s = \sqrt{\frac{\sum_{i=1}^{n} (X_i - \bar{X})^2}{n - 1}}
$$

### **Pearson Correlation Coefficient**

$$
r = \frac{\sum_{i=1}^{n} (X_i - \bar{X})(Y_i - \bar{Y})}
{\sqrt{\sum_{i=1}^{n} (X_i - \bar{X})^2 \cdot \sum_{i=1}^{n} (Y_i - \bar{Y})^2}}
$$

### **Simple Linear Regression Equation**

$$
Y = a + bX
$$

where

$$
b = r \times \frac{\sigma_Y}{\sigma_X}
$$


## 🧰 Google Colab Practice Section

Below are the **full prompts and Python codes** for participants to execute step-by-step in **Google Colab**.

### Prompt 1 – Understanding the Data

**Goal:** Identify each column’s data type and statistical variable role.

```python
import pandas as pd
data = {
    "State": ["Selangor", "Johor", "Kedah", "Kelantan", "Sabah", "Sarawak"],
    "Median_Income_2024": [9200, 7600, 5400, 4300, 4800, 5600],
    "Poverty_Rate": [2.5, 3.8, 7.2, 11.4, 10.6, 8.3]
}
df = pd.DataFrame(data)
df.info()
df.head()
```

### Prompt 2 – Descriptive Statistics

**Goal:** Calculate mean, median, minimum, maximum, and standard deviation.

```python
print("Descriptive Statistics:")
print(df[["Median_Income_2024", "Poverty_Rate"]].describe())
```

### Prompt 3 – Correlation Analysis

**Goal:** Measure relationship between income and poverty.

```python
corr = df["Median_Income_2024"].corr(df["Poverty_Rate"])
print("Pearson Correlation (r):", round(corr, 2))
```

### Prompt 4 – Visualization

**Goal:** Create scatter plot and regression line.

```python
import matplotlib.pyplot as plt
import numpy as np

plt.figure(figsize=(8,6))
plt.scatter(df["Median_Income_2024"], df["Poverty_Rate"], color='blue')

m, b = np.polyfit(df["Median_Income_2024"], df["Poverty_Rate"], 1)
plt.plot(df["Median_Income_2024"], m*df["Median_Income_2024"] + b,
         color='red', label=f"Regression line (r = {round(corr,2)})")

for i, state in enumerate(df["State"]):
    plt.text(df["Median_Income_2024"][i]+50, df["Poverty_Rate"][i], state, fontsize=9)

plt.title("Income vs Poverty Rate (Malaysia, 2024)")
plt.xlabel("Median Household Income (RM)")
plt.ylabel("Poverty Rate (%)")
plt.legend()
plt.grid(True)
plt.show()
```

### Prompt 5 – Executive Summary

```python
print("""
The analysis shows a strong negative correlation (r ≈ -0.97)
between median household income and poverty rate.
Higher-income states like Selangor and Johor have lower poverty levels,
while lower-income states such as Kelantan and Sabah show higher poverty rates.
""")
```

### Prompt 6 – Policy Message (Optional)

**Goal:** Translate insights into actionable policy suggestion.

```python
print("""
Policy Implication:
To reduce poverty effectively, state and federal governments
should prioritize income-boosting initiatives such as skills
development and targeted subsidies in low-income regions.
""")
```



### 🙌🏻 Connect with Me
<p align="left">
    <a href="https://github.com/drshahizan" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/-@drshahizan-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/drshahizan" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/-drshahizan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/drshahizan/"></a>
    <a href="mailto:shahizan@utm.my" target="_blank"><img alt="Email" src="https://img.shields.io/badge/-shahizan@utm.my-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:shahizan@utm.my.com"></a>
    <a href="https://www.researchgate.net/profile/Mohd-Othman-28" target="_blank"><img alt="ResearchGate" src="https://img.shields.io/badge/-ResearchGate-00CCBB?style=flat-square&logo=ResearchGate&logoColor=white"></a>
    <a href="https://orcid.org/0000-0003-4261-1873" target="_blank"><img alt="ORCID" src="https://img.shields.io/badge/-ORCID-A6CE39?style=flat-square&logo=ORCID&logoColor=white"></a> 
 <a href="https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan" target="_blank"><img alt="A" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic"></a>
 
![](https://hit.yhype.me/github/profile?user_id=81284918)
</p>

