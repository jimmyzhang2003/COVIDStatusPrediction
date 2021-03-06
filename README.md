# COVIDStatusPrediction
The global surge in COVID-19 cases has underscored the need for fast, scalable, and reliable testing. Current COVID-19 diagnostic tests are limited by turnaround time, limited availability, or occasional false findings. Here, we developed a machine learning-based framework for predicting COVID-19 positive test status relying only on readily-available baseline data, including patient demographics, comorbidities, and common lab values. Leveraging a cohort of 31,739 adults within an academic health system, we trained and tested multiple types of machine learning models, achieving an area under the curve of 0.75. Feature importance analyses highlighted serum calcium levels, aspartate aminotransferase levels, and oxygen saturation as key predictors. Additionally, we developed a single-tree XGBoost model that provided an operable method for stratifying sub-populations. Overall, this study provides a proof-of-concept that COVID-19 status prediction models can be developed using only baseline data. The resulting prediction can complement existing tests to enhance screening workflows. 


## Prerequisites
- python>=3.7.6
- scikit-learn==0.22.2
- graphviz==0.10.1
- numpy==1.18.5 
- pandas==1.1.3
- scipy==1.4.1
- matplotlib==3.2.2
- seaborn==0.11.0
- eli5==0.10.1 (optional)


# Usage
## analysis
### COVID_Status_Prediction_Analysis_and_Plots.ipynb
Main python notebook for data analysis, machine learning model development + hyperparameter optimization, and figure visualization.

### COVID_Antibody_Analysis.ipynb
Python notebook for COVID-19 antibody test results analysis (not included in main study). Will update when more antibody data becomes available.

## data
Mount Sinai Data Warehouse: 31,739 adult patients with RT-PCR test results up to June 2nd, 2020 

## doc


## figures
Feature importances plot, ROC curves, probability distribution, and simple decision tree.
