# Analyze A/B Test Results
#### [_Udacity - Data Analyst Nanodegree:_](https://www.udacity.com/course/data-analyst-nanodegree--nd002) _Project 3 - Practical Statistics_
## Table of Contents

1. [Project Overview](#project)
2. [Requirements](#requirements)
3. [Project Movitivation](#motivation)
4. [Summary of Findings](#summary)
5. [Acknowledgements](#acknowledgements)

### 1. Project Overview<a id="project"></a>
A/B tests are very commonly performed by data analysts and data scientists. 
For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. My goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision. Udacity provided a dataset reflecting data collected from an experiment. I had to use statistical techniques to answer questions about the data and report my conclusion in a short summary.

This project has three parts:

- Part I: Probability\
After initial exploration of the data, I used practical statistics to determine whether there was sufficient evidence to say that the new treatment page lead to more conversions.

- Part II: A/B Test\
Next, I ran an hypothesis test using bootstrapped samples to test our assumption regarding conversion rate of two landing pages. To determmine the probabability of accepting the null hypothesis from the bootstrapped similuation, I derived the p-value and z-value.

- Part III: Regression\
I used a logistic regression see if results acheived in the previous A/B test can also be acheived by performing regression. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

### 2. Requirements<a id="requirements"></a>
This project was created in a Jupyter Notebook made available via Anaconda and written in python. 
The following versions of languages and libraries were used in creating this project:
- matplotlib==3.5.1
- numpy==1.22.1
- pandas==1.4.0
- statsmodels==0.13.1

### 3. Project Motivation<a id="motivation"></a>
Here I wanted to become familiar with using the following statistical techniques:
- Bootstrapping sampling distributions and p-value calculations
- Z-core tests
- Logistic regression
- Multiple linear regression modelling to assess for interactions of independent variables

### 4. Summary of Findings<a id="summary"></a>
- The conversion rate for the new page was not better than that of the old page
- The country of the user did not impact the rate of conversion between the new and old page
- In short, based on the data available, I did not have sufficient evidence to suggest that the new page resulted in more conversions than the old page. So the company should **not** implement this new page but rather **keep** the old page.

### 6. Acknowledgements<a id="acknowledgements"></a>
This project was completed as part of the Udacity's [Data Analyst Nanodegree](https://github.com/keenan-cooper/WeRateDogs-Twitter-Data-from-2015-to-2017/files/7847764/nd002-syllabus_2018-June_v9.pdf).\

