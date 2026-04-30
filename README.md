
# Does Poverty Cause Crime? — Data Analysis Project

## Executive Summary
This project analyzes the relationship between poverty and crime using a dataset of the top 10 highest-crime countries and the 10 poorest countries globally. Through statistical analysis and data visualization, the study challenges the common assumption that poverty is the primary driver of crime.

The findings reveal that **income inequality (Gini coefficient)** is a stronger predictor of crime than poverty alone, suggesting that structural and societal factors play a critical role in crime rates.

---

## Problem Statement
Crime is often attributed to poverty, but this assumption may oversimplify a complex issue.

**Key Questions:**
- Does higher poverty directly lead to higher crime rates?  
- Are the poorest countries also the most dangerous?  
- What socioeconomic factors better explain crime trends?  

---

## Methodology
- **Datasets Used:**
  - Top 10 countries by Crime Index (Numbeo 2024)  
  - Top 10 poorest countries by GDP per capita (World Bank 2024)  

- **Data Processing:**
  - Combined datasets into a unified analysis table  
  - Standardized variables (poverty rate, GDP, inequality, crime index)

- **Statistical Analysis:**
  - Pearson correlation tests:
    - Poverty vs Crime  
    - Inequality (Gini) vs Crime  
    - GDP per Capita vs Crime  

- **Visualization:**
  - Scatter plots with regression lines  
  - Bar charts for crime and GDP comparison  
  - Multi-panel dashboard using `matplotlib`

---

## Key Visualizations

![Poverty vs Crime Analysis](project2_poverty_crime.png)

### Charts Included:
- Poverty Rate vs Crime Index (Scatter + Trend Line)  
- Top 10 Highest Crime Countries  
- Top 10 Poorest Countries (GDP per Capita)  
- Inequality (Gini) vs Crime  
- Homicide Rate Comparison  
- Summary Insight Panel  

---

## Key Findings

### 1. Poverty Has Only a Moderate Relationship with Crime
- Correlation shows **moderate positive relationship**
- Poverty alone does not fully explain crime levels  

### 2. Inequality is the Strongest Predictor
- Gini coefficient shows a **strong positive correlation with crime**
- Countries with higher inequality tend to have higher crime  

### 3. Poor Countries Are Not Always High Crime
- Many of the poorest countries (mainly in Africa) have **lower crime indices**
- Contradicts the assumption that poverty = crime  

### 4. GDP per Capita Shows a Negative Relationship
- Wealthier countries tend to have **lower crime rates overall**
- But wealth alone is not enough without equality  

### 5. Crime is a Structural Issue
- Governance, inequality, and institutional strength matter more than income levels  

---

## Skills Demonstrated

- **Data Analysis:** Pandas, NumPy  
- **Statistical Analysis:** Pearson Correlation  
- **Data Visualization:** Matplotlib, Seaborn  
- **Data Cleaning & Integration**  
- **Exploratory Data Analysis (EDA)**  
- **Business & Policy Insight Generation**  
- **Data Storytelling**  
- **Power BI Data Preparation (CSV export)**  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## Next Steps

- Expand dataset to include **50+ countries** for stronger statistical validity  
- Incorporate additional variables:
  - Education levels  
  - Government effectiveness  
  - Urbanization rates  
- Apply advanced models:
  - Multiple regression  
  - Machine learning classification  
- Build an **interactive Power BI dashboard**  
- Conduct **regional deep-dive analysis** (Latin America, Africa, etc.)  

---

## Author
**Andre Townsend, MBA**  
Data Analytics Portfolio  

---

## Final Insight
Poverty does not automatically lead to crime.  
**Inequality—not poverty—is the more powerful driver.**

Addressing wealth gaps and strengthening institutions may be the most effective long-term crime reduction strategies.
