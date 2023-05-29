# Homelessness
Investigation into homelessness in the US, specifically how community level market factors affect homelessness rates. We will investigate whether there are alternative modeling approaches that outperform the models described in the U.S. Department of Housing and Urban Development (HUD) report.

~

## Data

Data comes from the HUD's Market Indicators of Homelessness Report. They conducted a literature review to select independent variables from multiple sources in the areas of housing, economic, safety net, demographic, and climate they believed are associated with homelessness. The report indicates data was carefully chosen for its completeness and usefullness. <br>
The dependent variables refer to the total number of homeless people per 10,000 population, and the same measure for unsheltered and sheltered per 10,000 population. HUD has estimated the number of people experiencing homelessness—in both sheltered and unsheltered situations—on a single night in the last week of January in approximately 400 Continuums of Care (CoCs). CoCs are local planning bodies responsible for coordinating a full range of homelessness services in a geographic area, which may cover a city, county, group of counties, or an entire state.

<br> (See the data section of this [report](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf))

~

## Data Preparation 

To prepare the raw data for analysis, the following steps were taken:
  - explored the raw data (general shape, columns, etc)
  - selected relevent subsets of the data
  - renamed columns
  - removed missing data
  - derived new, relevant variables as new columns

The file used to prepare the data can be found as: homeless_data_prep.ipyn
The clean data can be found as: homeless_clean.csv

~

## Data Analysis 

To conduct the analysis, the following steps were taken:
  - created test and train splits
  - scaled predictor data
  - created a OLS model
  - used kfold cross validation testing on Ridge, Lasso, and XGBoost models
  - use root mean square error to evaluate effectiveness of a model

The file used to analyze the data can be found as: homeless_data_analysis.ipyn
The presentation to communicate the results can be found as: homelessness_presi.pdf

~

## Author 

Cassidy Denault, Computer Science Major, Data Science Minor in Seattle, WA.

~

## License

Abides by the MIT License
