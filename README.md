# Covid Test Outcomes and Analysis

### Short Description

These workbooks investigate a dataset made available from Carbon.  

https://covidclinicaldata.org

The workbooks contain python code (pandas, SQL, and scikit-learn) to analyze and make predictions based on observed patient symptoms and testing outcomes.

### Long Description

This workshop uses Covid-19 data from Carbon health to introduce the use of SQL and scikit-learn to analyze a dataset. In both cases, we will use predictor variables (symptoms, comorbidities, vitals) to estimate the probability of an outcome variable (positive or negative COVID-19 test). 

As you work through these workbooks pre or post workshop, keep in mind that our focus is on building technical skills in SQL and scikit-learn. Although some symptoms or combinations of symptoms may correlate with test results, our goal is not to build a highly predictive model for COVID-19. Instead, we will be using Covid-19 data to generate insight and motivate futher exploration of this dataset and other datasets through SQL and scikit-learn.

### Prerequisites

This workshop is designed for participants who have intermediate programming experience with Python and SQL. You'll need this background to follow along with the coding exercises and problem sets. 

If you're generaally interested, you may enjoy reading through the material or watching the videos or attending a workshop without these skills. 

## Workbooks

### query-estimates.ipynb

In this workbook, we use SQL, python, and Pandas to investigate the frequency of positive and negative COVID-19 tests based on different comorbidities and symptoms, and vitals. 

### rf-estimates.ipynb

In this workbook, we use scikit-learn to build a machine learning model that will predict the probability of a positive or negative test based on symptoms and other input variables. Although we will not (in this workshop, at least) build an especially predictive model, you will learn techniques to analyze a dataset using scikit-learn, random forest, and other ML algorithms. 

### clean-data.ipynb

This workbook contains code for pre-processing data prior to building a model. Read data from multiple CSV files into a pandas dataframe, remove N/A values (that will break scikit-learn), convert Positive and Negative test results and other data points from strings or booleans into integers. Write out results as CSV file that can be used as input to scikit-learn model.

### rf-sample-data.ipynb

This workbook contains code to build and populate a scikit-learn model using very little data. Although the tiny (4 row) data set will not provide reliable results, it can provide an opportunity to investigate how data and algorithm choice influence output numbers.

### sql-query-page.ipynb

A workbook for ad-hoc SQL queries and/or pandas operations to explore the dataset.  

### data citation

@dataset{2020covidclinicaldata,
  author =       {Carbon Health and Braid Health},
  title =        {Coronavirus Disease 2019 (COVID-19) Clinical Data Repository},
  howpublished = {Accessed from \url{https://covidclinicaldata.org/.}},
  year =         2020,
  version =      {10-20-2020}
}
