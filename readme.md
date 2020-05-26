Analyze A/B Test Results Summary

by Z. Jiang
April, 2020

This project was competed as a part of the course requirement of Udacity's Data Analysis Nanodegree certification.

Overview
The A/B testing was conducted in this project to evaluate whether an old and new page improved user conversion.

Statistical Analysis 
- Bootstrapping sampling distributions and p-value calculations
- Logistic regression
- Z-core tests
- Multiple linear regression modeling for the assessment of the interactions between independent variables

Coding and Used Libraries
- Jupyter Notebook
- Python, Numpy, Pandas, Matplotlibs, Scipy, StatsModels
- LaTex

Key Findings
- There's no statistical significance of the user conversion rate between the new and old pages
- The user resident country did not impact the conversion rate between the new and old pages

Datasets
The data set contains records of 294,478 the conducted A/B test

Files
- ab_data.csv
- ab_new_data.csv
- countries.csv

Variables of ab_data.csv
- user_id
- timestamp
- group
- landing_page
- converted

Variables of countries.csv
- user_id
- country
