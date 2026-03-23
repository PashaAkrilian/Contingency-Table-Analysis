# Contingency Table Analysis

This project presents a simple contingency table analysis of the relationship between **gender** and the **type of food most frequently consumed during Eid al-Fitr** among **20 respondents**. The study uses categorical data, organizes the responses into a contingency table, and applies a **chi-square test of independence** to examine whether the two variables are likely to be associated.

## Project Overview

A contingency table is a statistical tool used to summarize the frequency distribution of two categorical variables in rows and columns. In this project, the contingency table is used to describe how food preferences during Eid al-Fitr vary by gender.

## Research Topic

**Contingency Table of Gender and the Type of Food Most Frequently Consumed during Eid al-Fitr among 20 Respondents**

## Variables

### 1. Gender
- Male
- Female

### 2. Food Type Most Frequently Consumed during Eid al-Fitr
- Ketupat-based dishes
- Rendang
- Chicken noodles

## Contingency Table

| Food Type | Male | Female | Total |
|-----------|-----:|-------:|------:|
| Ketupat-based dishes | 3 | 5 | 8 |
| Rendang | 4 | 3 | 7 |
| Chicken noodles | 2 | 3 | 5 |
| **Total** | **9** | **11** | **20** |

## Objective

The main objectives of this project are:
- to present categorical data in a structured contingency table,
- to identify distribution patterns across categories,
- to compare food preferences between male and female respondents, and
- to determine whether the two variables are statistically related.

## Statistical Test

A **chi-square test of independence** was conducted using Python.

### Result Summary
- Chi-square statistic: **0.6494**
- p-value: **0.7228**
- Degrees of freedom: **2**
- Cramer's V: **0.1802**

## Interpretation

The p-value is greater than 0.05, which indicates that there is **no statistically significant relationship** between gender and the type of food most frequently consumed during Eid al-Fitr in this sample. In addition, the Cramer's V value suggests that the strength of association between the two variables is **weak**.

## Conclusion

Based on the contingency table and chi-square test results, gender does not appear to have a significant association with Eid al-Fitr food preference among the 20 respondents included in this study. However, because the sample size is relatively small, the findings should be interpreted with caution.

## Tools Used

- Python
- NumPy
- SciPy
- Markdown

## Repository Purpose

This repository was created for a statistics assignment on contingency tables. It contains a simple example of categorical data analysis, contingency table construction, and interpretation of chi-square test results.
