## The unseen causes of depression

### Members of the group: 
- Ivanna: data cleaning, visualization, concept and business eye. 
- Taho: data cleaning, machine learning, concept and humanitarian prespective. 
- Valentina: data cleaning, machine learning, concept and development view. 

### Goal of the project: 

In this data exploration we want to answer the question, what influences depression rates in countries? 

We have found a depression rate database by country and we will do a cross variable data analysis in order to see the relation between depression rates and factors such as the gender gap of the country, average of sunny days, income inequality, democracy index, among others. 

We understand depression to be a complex health and social issue with multifactoreal causes. In this study we want to explore non traditional indicators, in order to understand the issue in a more systemic manner. 

### Importance:

According to data gathered from 2005 to date by the World Health Organization, depression is now the leading cause of disability worldwide. Just from 2015 to date, it has shown a steady and continuous increase of 18%. To understand not only the individual factors, but also the structures that might influence this, can bring a better understanding of it thus the possibility to tackle the problem better. 

#### What we will do →  Create a model where our target variable will be the depression rate by country and our independent variables will be democracy index, gender gap, air quality, literacy rate, demographic, crime rate, household sixe, social mobility, average of sunny days and public services. 


### Description of the dataset: 
(source, number of rows, number of features). 
#### Our Y:
Depression rates: 
https://www.who.int/data/gho/data/indicators/indicator-details/GHO/estimated-population-based-prevalence-of-depression

#### Our X: 
Democracy index: 
https://worldpopulationreview.com/country-rankings/democracy-countries
Gender gap
	https://worldpopulationreview.com/country-rankings/gender-equality-by-country

Air quality: https://www.iqair.com/world-most-polluted-countries 

Literacy rate: https://data.worldbank.org/indicator/SE.ADT.LITR.ZS
https://www.kaggle.com/datasets/komalkhetlani/youth-and-adult-literacy-rate-around-the-globe 
5. Demographic
https://www.census.gov/data-tools/demo/idb/#/table?COUNTRY_YEAR=2023&COUNTRY_YR_ANIM=2023 
https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset

6. Violent crime rate
https://worldpopulationreview.com/country-rankings/violent-crime-rates-by-country
https://wisevoter.com/country-rankings/crime-rate-by-country/
7. Household size
https://ceoworld.biz/2020/02/19/these-are-the-countries-with-the-largest-household-size/
8. Social mobility 
https://worldpopulationreview.com/country-rankings/social-mobility-by-country
9. Public service index
https://www.theglobaleconomy.com/rankings/public_services_index/


### Work plan: 


Day 1: 

Move all datasets into one  (join all the tables in SQL)
Data cleansing using Python 
Categorize 

Day 2: 

Scale using different scaling method in python 
Have final dataframe 
Plot all independent variables and see correlation. Here we will use Tableau for visualization(world map and look in to different relations)
Choose our final independent variables 

Day 3: (Machine Learning)

Run the regression 
Interpret the coefficients associated to prove insights into how those indicators are related to the likelihood of depression. 
Improve and rerun model based on the first run 

Day 4: 

Interpret the model: visualize the relationship with each indicator to explore the association, interpret coefficient, R. 
Create final visualizations
Make presentations


Day 5: 

Be happy while talking about depression. 

