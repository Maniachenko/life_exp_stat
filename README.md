# Life Expectancy Analysis

## Overview
This project aims to analyze life expectancy data from 193 countries spanning from 2000 to 2015. By examining various factors such as immunization rates, mortality, economic conditions, and social determinants, the study seeks to identify key contributors to life expectancy variations. The insights derived from this analysis can aid policymakers and public health officials in prioritizing interventions to improve population health outcomes.

## Data Sources
The data was sourced from the Global Health Observatory (GHO) data repository (World Health Organization) and the United Nations. The dataset includes 22 columns representing various health, economic, and social indicators, and covers 2938 observations.

## Key Features
- **Country**: Name of the country
- **Year**: Year of observation
- **Status**: Development status (Developed/Developing)
- **Life Expectancy**: Average life expectancy in years
- **Adult Mortality**: Adult mortality rates
- **Infant Deaths**: Number of infant deaths
- **Alcohol**: Alcohol consumption per capita
- **Hepatitis B**: Immunization coverage for Hepatitis B
- **Measles**: Measles cases
- **BMI**: Body Mass Index
- **Under-five Deaths**: Mortality under five years of age
- **Polio**: Immunization coverage for Polio
- **Total Expenditure**: Government expenditure on health as a percentage of GDP
- **Diphtheria**: Immunization coverage for Diphtheria
- **HIV/AIDS**: HIV/AIDS prevalence
- **GDP**: Gross Domestic Product per capita
- **Population**: Population size
- **Thinness**: Prevalence of thinness in various age groups
- **Income Composition of Resources**: Human Development Index in terms of income composition
- **Schooling**: Average number of years of schooling

## Methodology
1. **Data Cleaning and Preprocessing**:
   - Handled missing data through statistical methods such as mean and median imputation.
   - Conducted chi-square tests to determine the randomness of missing data concerning the 'Year' variable.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized data distributions and relationships between key variables.
   - Identified highly correlated features with life expectancy.

3. **Statistical Analysis**:
   - Applied multiple linear regression and mixed effects models to identify significant predictors of life expectancy.
   - Performed significance tests, including the Mann-Whitney U test, to compare life expectancy between developed and developing countries.

4. **Results**:
   - Identified key factors such as schooling, adult mortality, healthcare expenditure, and alcohol consumption that significantly affect life expectancy.
   - Highlighted the disparity in life expectancy between developed and developing countries.

## Conclusions
The analysis underscores the importance of education, healthcare investment, and social determinants in improving life expectancy. It provides valuable insights for policymakers to focus on enhancing educational and healthcare infrastructure to boost overall population health.
