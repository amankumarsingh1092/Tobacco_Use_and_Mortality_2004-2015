# Tobacco Use and Mortality (2004–2015) 

About the Project
This machine learning project analyzes the relationship between tobacco use and mortality rates using health data from 2004 to 2015. Smoking-related conditions resulted in 1.7 million hospital admissions in England in 2014–2015 alone, highlighting the urgency of predictive health analytics.

## Project Objective
To predict the likelihood of mortality using health data, with a focus on tobacco consumption patterns. This project combines data science techniques with real-world healthcare data to extract actionable insights and build predictive models that could assist in public health decision-making.

## Datasets Used in This Project
- **Admissions Data**: Hospital admissions due to smoking-related conditions across years.
- **Fatalities Data**: Deaths linked to smoking-related diseases, broken down by diagnosis type, gender, and year.
- **Prescriptions Data**: Trends in pharmacotherapies (NRT, Bupropion, Varenicline) used for smoking cessation.
- **Smoking Prevalence Data**: Distribution of smokers by age group, gender, and year.
- **Health Metrics Data**: Various indicators possibly linked to smoking behavior or health outcomes (e.g., cost, frequency, or public health interventions).
  
## Tools & Technologies
- **Languages**: Python
- **Data Processing & Visualization**: pandas, numpy, matplotlib, seaborn  
- **Modeling Evaluation**:Confusion Matrix, Accuracy Score, Classification Report 
- **Machine Learning**: train-test split, Random Forest Classifier  
 - **IDE**: Jupyter Notebook

## Methodology
### 1. Problem Definition
- Predict mortality risk based on tobacco use and associated factors.
### 2. Data Collection
- Combined surveys, mortality records, and socioeconomic data across several years.
### 3. Data Preprocessing
- Cleaning missing values
- Handling outliers
- Feature engineering (e.g., tobacco use duration, demographics, health access)
### 4. Exploratory Data Analysis (EDA)
- Histograms, heatmaps, and correlation matrices to visualize relationships
### 5. Model Building
- Classification Models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - SVM
  - Neural Networks
### 6. Model Evaluation
- Metrics used:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

### 7. Model Interpretation
- SHAP and LIME used to interpret feature influence on model predictions

### 8. Deployment
- REST API using Flask for prediction
- (Optional) Web interface using Streamlit or Dash
### Author
- Aman Kumar Singh
- www.linkedin.com/in/aman-kumar-singh-71a090206
- aksingh1652@gmail.com

# Tobacco Use and Mortality (2004–2015)

## About the Project
This data science project explores how tobacco use has influenced hospital admissions, fatalities, and prescription patterns in England between 2004 and 2015. It involves exploratory data analysis and visualization using real-world health datasets to uncover trends and insights.

## Project Objective
To analyze patterns in hospital admissions, mortality rates, smoking prevalence, and prescriptions related to tobacco use, and visualize key trends over time to support public health evaluation and awareness.



## Tools & Technologies
- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn  
- **Notebook Environment**: Jupyter Notebook  

---

## Methodology
### 1. Data Cleaning & Preparation
- Converted year formats
- Standardized numeric columns
- Melted data for flexible analysis

### 2. Exploratory Data Analysis (EDA)
- **Admissions**: Identified trends in smoking-related hospitalizations over time.
- **Fatalities**: Analyzed total deaths, gender differences, and smoking-related causes.
- **Prescriptions**: Tracked pharmacotherapy usage and associated costs.
- **Smokers**: Examined smoking prevalence by age group and gender.
- **Metrics**: Investigated annual trends in age-standardized rates and number of deaths.

### 3. Visualization
Used the following plots to derive insights:
- Line plots to show trends over time
- Bar charts to compare categories
- Heatmaps to visualize age-year prevalence and mortality
- Pie charts to show proportion of smoking-related impacts

---

## Key Insights
- Smoking-related admissions and deaths showed a decreasing trend in later years.
- Varenicline (Champix) gained popularity while Bupropion prescriptions decreased.
- Costs for NRT remained consistently high even with reduced prescriptions.
- Smoking prevalence declined across most age groups.
- Males generally had higher smoking prevalence and smoking-related deaths.

---

## Author
- **Name**: Aman Kumar Singh  
- **LinkedIn**: [linkedin.com/in/aman-kumar-singh-71a090206](https://www.linkedin.com/in/aman-kumar-singh-71a090206)  
- **Email**: aksingh1652@gmail.com
