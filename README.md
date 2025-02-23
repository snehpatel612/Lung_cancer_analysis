# Lung Cancer Prediction Analysis

## Overview
This project focuses on analyzing the Lung Cancer Prediction Dataset to predict the likelihood of lung cancer in individuals based on demographic, medical, lifestyle, genetic, and environmental factors. The goal is to assist in identifying high-risk individuals, provide early detection insights, and inform personalized treatment strategies for lung cancer.

## Objectives
- **Predict Lung Cancer Diagnosis**: Build a model to predict lung cancer diagnosis.
- **Survival Analysis**: Assess risk factors affecting lung cancer survival rates.
- **Mortality Risk Prediction**: Predict mortality rates for lung cancer patients.
- **Feature Importance Identification**: Identify key factors influencing lung cancer diagnosis and prognosis.
- **Early Detection Strategy**: Develop strategies for early detection of lung cancer.
- **Treatment Recommendations**: Recommend treatments based on patient risk factors and cancer stage.

## Dataset
The dataset contains 220,632 rows and 24 columns, including:
- **ID**: Unique identifier for each individual.
- **Country**: Country of residence.
- **Population_Size**: Size of the population.
- **Age**: Age of the individual.
- **Gender**: Gender of the individual.
- **Smoker**: Smoking status.
- **Years_of_Smoking**: Number of years the individual has smoked.
- **Cigarettes_per_Day**: Number of cigarettes smoked per day.
- **Passive_Smoker**: Exposure to passive smoking.
- **Family_History**: Family history of lung cancer.
- **Lung_Cancer_Diagnosis**: Diagnosis of lung cancer.
- **Cancer_Stage**: Stage of cancer.
- **Survival_Years**: Number of years survived after diagnosis.
- **Adenocarcinoma_Type**: Type of adenocarcinoma.
- **Air_Pollution_Exposure**: Level of air pollution exposure.
- **Occupational_Exposure**: Occupational exposure to carcinogens.
- **Indoor_Pollution**: Indoor pollution exposure.
- **Healthcare_Access**: Access to healthcare.
- **Early_Detection**: Early detection of lung cancer.
- **Treatment_Type**: Type of treatment received.
- **Developed_or_Developing**: Classification of the country as developed or developing.
- **Annual_Lung_Cancer_Deaths**: Annual lung cancer deaths.
- **Lung_Cancer_Prevalence_Rate**: Prevalence rate of lung cancer.
- **Mortality_Rate**: Mortality rate of lung cancer.

## Data Cleaning and Preprocessing
- **Missing Values**: Filled missing values in `Cancer_Stage` with 'Stage 0' and in `Treatment_Type` with 'NaN'.
- **Duplicated Values**: No duplicated values found.

## SQL Queries
### Basic Level
1. Retrieve all records for individuals diagnosed with lung cancer.
2. Count the number of smokers and non-smokers.
3. List all unique cancer stages present in the dataset.
4. Retrieve the average number of cigarettes smoked per day by smokers.
5. Count the number of people exposed to high air pollution.
6. Find the top 5 countries with the highest lung cancer deaths.
7. Count the number of people diagnosed with lung cancer by gender.
8. Retrieve records of individuals older than 60 who are diagnosed with lung cancer.

### Intermediate Level
1. Find the percentage of smokers who developed lung cancer.
2. Calculate the average survival years based on cancer stages.
3. Count the number of lung cancer patients based on passive smoking.
4. Find the country with the highest lung cancer prevalence rate.
5. Identify the smoking years' impact on lung cancer.
6. Determine the mortality rate for patients with and without early detection.
7. Group the lung cancer prevalence rate by developed vs. developing countries.

### Advanced Level
1. Identify the correlation between lung cancer prevalence and air pollution levels.
2. Find the average age of lung cancer patients for each country.
3. Calculate the risk factor of lung cancer by smoker status, passive smoking, and family history.
4. Rank countries based on their mortality rate.
5. Determine if treatment type has a significant impact on survival years.
6. Compare lung cancer prevalence in men vs. women across countries.
7. Find how occupational exposure, smoking, and air pollution collectively impact lung cancer rates.
8. Analyze the impact of early detection on survival years.

## Data Visualization & Dashboard
- **Key Stats**: 8,961 cases, average age 52.66, 69.73% smokers.
- **Observations**: More males are impacted with cancer compared to females.
- **Risks**: 70% of smokers are at high risk of developing lung cancer, and it is most likely to be men.

## Conclusion
Lung cancer remains a critical public health issue, with smoking and environmental factors driving incidence and mortality. Early detection and effective treatment, especially surgical intervention, significantly improve survival rates.

## Business Recommendations
1. **Prioritize Early Detection Initiatives**: Invest in advanced diagnostic technologies to enhance early lung cancer detection.
2. **Expand Smoking Cessation Programs**: Launch awareness campaigns and provide support for smoking cessation.
3. **Leverage Data for Personalized Treatment**: Invest in AI and predictive analytics for personalized treatment plans.
4. **Promote Environmental Health & Access to Treatment**: Collaborate with policymakers to reduce air pollution and enhance access to surgical treatments.

## Tools Used
- **MySQL**: For data querying and analysis.
- **Excel**: For data cleaning and statistical analysis.
- **Power BI**: For data visualization and dashboard creation.

## Author
Sneh Patel

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
