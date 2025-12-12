TBTrends: Tuberculosis Data Analysis and Predictive Modeling

An exploratory data analysis (EDA) and predictive modeling project on global tuberculosis (TB) trends, with a specific focus on South Africa's progress towards the WHO End TB Strategy targets for 2030.

Overview
Tuberculosis remains a significant global health challenge. This project conducts an in-depth analysis of a comprehensive country-level public health dataset (Tuberculosis_Trends.csv) from [Kaggle](https://www.kaggle.com/datasets/khushikyad001/tuberculosis-trends-global-and-regional-insights). The primary objective is to uncover patterns and relationships between TB indicators (cases, mortality, treatment success) and various socio-economic and health infrastructure metrics to identify key drivers of disease prevalence.
The analysis uses historical data from 2000-2024 to assess trends, determine correlations, and build a predictive model to forecast future incidence in South Africa.

Key Insights
Regional Disparities: Persistent disparities exist between high-burden regions (Asia, Africa) and low-burden regions (North America, Europe).
Impact of Health Services: The strongest negative correlation was found between Access_To_Health_Services and TB_Deaths, suggesting that improved access to care is a highly impactful structural intervention.
Key Drivers: The Random Forest model identified Population, TB_Treatment_Success_Rate, and GDP_Per_Capita as key drivers for predicting TB cases.
2030 Targets: Under its current trajectory, South Africa is not projected to meet the ambitious 80% TB incidence reduction target by 2030.
Getting Started

Prerequisites
The analysis was conducted using Python and several key libraries from the scientific Python ecosystem.
pandas (for data manipulation)
numpy (for numerical operations)
seaborn and matplotlib (for visualization)
scipy (for scientific computing)
sklearn (for modeling)
statsmodels (for time-series forecasting)
