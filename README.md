# Stack Overflow Survey
1. You can look at this code by running `jupyter notebook` within this repository. Please, follow the steps [here](https://jupyter.org/install), if you do not have jupyter installed.
2. Check out the file named: `job_satisfaction_stack_overflow_survey.ipynb`
3. You can take a look at the file named: `job_satisfaction_exploration`, to look at my original work.
4. This code follows the CRISP-DM process as explained below.

## Business Understanding
I started by looking at the survey, and a blog written by someone else. This blog was written to explain how someone may join the field of development. I thought that there must be some more useful insights from this dataset for myself, and other fellow developers.

## Data Understanding
This dataset takes a look at many features of the developer in their everyday life. As there was a column for `JobSatisfaction`, I spent some time looking at other variables, and seeing if there were any correlations. 

## Prepare Data
My first step in working with the dataset is to clean it, and divide the columns that I am looking at between quantitative, and qualitative variables. This can be seen through imputing with a mode/mean where necessary. As well as, imputing by reshaping the data for more sensible categories to work with.

## Data Modeling
This step is utilized in looking at the R2 error of the categorical variables in this dataset. This model creates dummy variables, and then passes them through to R2. Looking at some simple correlations, for the strongest independent predictors.

## Evaluate the results
You can see my thought process in the comments of the code. In looking through the data, sorting it, and visualizing it. I was able to gain insights on the best predictor, and also the predictors that change, as the `YearsProgram` column increased.

## Deploy
Not an ML model. See "Data Modeling" above for more information.