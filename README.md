# Heart Attack in Indonesia - Dashboard Tableau

## Project Overview

This project aims to analyze the dominant factors of heart attacks in Indonesia using statistical analysis and visualization. The results are presented through a Tableau dashboard to support data-driven decision-making by the Ministry of Health of the Republic of Indonesia.

---

## Identification of Problems

### Background

Heart disease is one of the leading causes of death in Indonesia, affecting various age groups, from the young to the elderly. A comparative analysis of heart attack characteristics between age groups can reveal valuable insights for more effective prevention and treatment strategies.

As an analyst at the **Ministry of Health of the Republic of Indonesia**, this study was conducted to identify the dominant factors influencing the incidence of heart attacks, with the goal of making health-related policies more targeted and impactful.

---

## Problem Statement (Using SMART Framework)

- **Specific**: Analyze and compare risk factors for heart attacks.
- **Measurable**: Reduce the number of heart attacks in Indonesia by 5%.
- **Achievable**: Create health education and campaign programs and regulate policies regarding cigarettes and fast food.
- **Relevant**: Support the vision of **Healthy Indonesia 2025** in reducing the number of non-communicable diseases.
- **Time-bound**: Achieve a 5% reduction in heart attacks in Indonesia within one year.

> **Problem Statement**:
Analyze the dominant factors of heart attacks with the aim of reducing heart attack cases in Indonesia by 5% in a year, in support of the Healthy Indonesia 2025 vision, through national health programs and campaigns.

---

## Key Research Questions

To support the analysis, the following questions are addressed:

1. What are the dominant factors that cause heart attacks?
2. Why do these dominant factors influence heart attacks?
3. Who is more likely to have heart attacks?
4. At what age do heart attacks occur most often?
5. Where do heart attacks commonly occur?

---

## Data & Methodology

- **Tools Used**: 
  - Python (Pandas, SciPy, Matplotlib, Seaborn)
  - Tableau (for dashboard visualization)

- **Statistical Methods**:
  - Chi-Square Test
  - Descriptive Analysis
  - Comparative Analysis by Age Group

```python
# Sample of libraries used in the notebook
import pandas as pd
from scipy import stats
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import chi2_contingency
