# Global-Data-on-Sustainable-Energy-2000-2020-
Comparing univariate time-series analysis and ML models in CO2 emission prediction of top 3 emitting countries VS rest of the world.
<br>
<br>
<br>
## Dataset Description
### Global Data on Sustainable Energy (2000-2020)
Source: downloaded from Kaggle (https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy)

This dataset contains data related to sustainable energy indicators and other useful factors across 176 countries from 2000 to 2020. 
It comprises of 3649 entries, 21 features in total. Th
<br>
<br>
<br>

## Goal of Analysis
The analysis aims to answer to the below questions.
<br>
>1. Can we build a model that forecasts future CO2 emissions?
>2. Can we improve the model by incorporating features other than time-series data of CO2? How can we identify the important features?
<br>
<br>
<br>

## Challenge of Dataset
1. A substantial amount of missing data, with some features over 50% missing values
2. The dataset includes 21 features, making feature selection complex
3. Time-series Analysis with feature, 'Year'
<br>
<br>
<br>

## Structure of Script
**Section 1:Missing Data** aims to retain as many features as possible. By visualising missing data in an interactive heatmap, the progress of missing data handling can be monitored by updating the graph after each treatment.
**Section 2:Univariate Time-Series** tests different time-series regression models against carbon emission (ARIMA/AR)
**Section 3:ML with RFE** visualises feature importance selected by ElasticNet and RandomForest, which are finalised with Recursive Feature Elimination(RFE).
Conclusion provides the evaluation of selected time-series models and ML models with RFE, and the limitations of this anlaysis
