# Objective: Predict World Happiness Rankings 

What makes the citizens of one country more happy than the citizens of other countries?  Do variables measuing perceptions of corruption, GDP, maintaining a healthy lifestyle, or social support associate with a country's happiness ranking?  

Let's use the United Nation's World Happiness Rankings country level data to experiment with models that predict happiness rankings well.


---

**Data**: 2019 World Happiness Survey Rankings [1] + ISO 3166 Country Codes [2] *(The International Standard for country codes and codes for their subdivisions)*

**Features**
*   Country or region
*   GDP per capita
*   Social support
*   Healthy life expectancy
*   Freedom to make life choices
*   Generosity
*   Perceptions of corruption
*   World regions (from *ISO 3166 Country Codes*)

**Target**
*   Happiness_level (Very High = Top 20% and Very Low = Bottom 20%)

**Quick note**: Countries are used in this project as a categorical variable. This variable actually is categorical at the observation level. Suffice it to say, in practice it is not ideal to build a model with a categorical variable such as countries in the World Happiness Report because there are too many categories. This is a rationale for merging this dataset with the ISO 3166 dataset because using world regions instead of countries can significantly reduce the number of categories.

Source:
* [1] https://worldhappiness.report/
* [2] https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv
