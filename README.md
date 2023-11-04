# Breast Cancer Incidence Analysis

### Project Overview

This project aims to understand factors influencing breast cancer progression, a major public health concern for women. It uses data-driven insights to uncover 40% of breast cancer care disparities and outcomes, with the goal of informing targeted interventions and policy changes.

### Data Sources

This dataset of breast cancer patients was obtained from the 2017 November update of the SEER Program of the NCI, which provides information on population-based cancer statistics. The dataset involved female patients with invasive breast cancer who were diagnosed between 2000 and 2017. The dataset includes information on the patient's age, race, ethnicity, stage of cancer, tumor size, grade, and treatment.

The data is available for sharing under the Creative Commons Attribution 4.0 International License.

### Tools

- Excel - Data Cleaning
- SQL Server - Data Analytics
- Tableau - Creating Story and Dashboards

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks : 
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involves exploring breast cancer patients to answer key questions, such as :

- What is the survival rate per race ? 
- What is the relation between marital status and breast cancer victims ?
- How hormones such as estrogen and progesteron impact relate to breast cancer ?
- What is the demographic distribution of breast cancer victims ?

### Data Analysis

```sql
SELECT * FROM SEER Breast Cancer Data
Where Tumor Size > 50;
```
### Results/Findings

1. Racial/Ethnics groups face disparities in breast cancer detection and treatments access
2. Being negative to both estrogen and progesteron is conducive to better responding to therapy
3. Breast cancer deaths rise with age; fewer between 30-40, more after 67 years old
4. Women between 36 to 60 have an unpredictable breast cancer risk due to the influence of hormonal factors

### Recommendations

Based on the analysis, we recommend the following actions : 
- Addressing disparities in access to early detection and treatments
- Supporting unmarried or widowed women
- Personalized treatment strategies based on receptor status
- Further research on age group 36-60 are needed
- Investment in research and innovation
- Awareness campaigns
