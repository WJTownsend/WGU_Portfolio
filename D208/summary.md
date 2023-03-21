# D208: Predictive Modeling

## Course Summary

WGU states that D208 Predictive Modeling builds on initial data preparation, cleaning, and analysis, enabling students to make assertions vital to organizational needs. In this course, students conduct logistic regression and multiple regression to model the phenomena revealed by data. The course covers normality, homoscedasticity, and significance, preparing students to communicate findings and the limitations of those findings accurately to organizational leaders.

This course has two Practical Assessments. 

## Course Objectives

WGU outlines the following competencies as a part of this class:
- **Logistic Regression:** The graduate employs logistic regression algorithms in describing phenomena.
- **Multiple Regression:** The graduate employs multiple regression algorithms with categorical and numerical predictors in describing phenomena.
- **Regression Implications:** The graduate makes assertions based on regression modeling.

## Course Materials

WGU's course materials consist of [(1)](https://www.datacamp.com/courses/introduction-to-regression-with-statsmodels-in-python) [(2)](https://www.datacamp.com/courses/intermediate-regression-with-statsmodels-in-python) [(3)](https://www.datacamp.com/courses/introduction-to-linear-modeling-in-python) [(4)](https://www.datacamp.com/courses/introduction-to-predictive-analytics-in-python) courses on DataCamp for Python or [(1)](https://www.datacamp.com/courses/introduction-to-regression-in-r) [(2)](https://www.datacamp.com/courses/intermediate-regression-in-r) [(3)](https://www.datacamp.com/courses/introduction-to-statistics-in-r) [(4)](https://www.datacamp.com/courses/inference-for-linear-regression-in-r) courses for R. 

## Practical Assessment(s) Overview & Files

This course has two Practical Assessments. 

### Task 1

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and multiple regression to answer this question. Students create an initial multiple regression model, and generate a reduced multiple regression model by selecting variables based on a statistical justification and a model evaluation metric. Students also generate a number of univariate and bivariate visualizations of variables within the dataset. 

My research question for this project was *"What factors most significantly contribute to the length of a hospital stay?"* Given the necessity to use quantitative data for a multiple regression problem, I chose to focus on length of hospital stay as the variable of interest and examine how other variables in the dataset influenced this. While I was able to generate a model that was statistically significant, I determined that the model had no practical significance at all, which I explained in my report. [My report for this project, including all of my Python code, can be viewed here.](d208task1.ipynb)

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. [That video can be seen here](https://drive.google.com/file/d/1gsfc66L3t1ds3HgeB9ly59NnW9qAWu61/view?usp=share_link). 

### Task 2

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and logistic regression to answer this question. Students create an initial logistic regression model, and generate a reduced logistic regression model by selecting variables based on a statistical justification and a model evaluation metric. Students also generate a number of univariate and bivariate visualizations of variables within the dataset. 

My research question for this project was *"Which factors most significantly contribute to patients diagnosed with chronic back pain?"*, continuing my line of questioning from previous analyses. I was able to conclude that the limitations of the dataset prevented the generation of an effective logistic regression model to predict patients with chronic back pain, as the model would only predict patients to never have back pain, based largely on 59% of patients not having back pain and a lack of variables to meaningfully influence the model to predict patients to have back pain. As a result, despite the generated model being narrowly statistically significant, it had no practical significance, which I explained in detail in my report. [My report for this project, including all of my Python code, can be viewed here.](d208task2.ipynb)

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. [That video can be seen here](https://drive.google.com/file/d/1irwiEji4WLST3fN5wpbWPoPBdnFWuXZ4/view?usp=share_link). 