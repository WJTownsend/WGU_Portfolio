# D209: Data Mining I

## Course Summary

WGU states that D209 Data Mining I expands predictive modeling into nonlinear dimensions, enhancing the capabilities and effectiveness of the data analytics lifecycle. In this course, learners implement supervised models—specifically classification and prediction data mining models—to unearth relationships among variables that are not apparent with more surface-level techniques. The course provides frameworks for assessing models’ sensitivity and specificity.

This course has two Practical Assessments. 

## Course Objectives

WGU outlines the following competencies as a part of this class:
- **Classification Data Mining Models:** The graduate applies observations to appropriate classes and categories using classification models.
- **Predictive Data Mining MOdels:** The graduate implements prediction data mining models to find hard-to-spot relationships among variables.
- **Data Mining Model Performance:** The graduate evaluates data mining model performance for precision, accuracy, and model comparison.

## Course Materials

WGU's course materials consist of [(1)](https://www.datacamp.com/courses/machine-learning-with-scikit-learn) [(2)](https://www.datacamp.com/courses/machine-learning-with-tree-based-models-in-python) [(3)](https://www.datacamp.com/courses/model-validation-in-python) courses on DataCamp for Python or [(1)](https://www.datacamp.com/courses/supervised-learning-in-r-classification) [(2)](https://www.datacamp.com/courses/supervised-learning-in-r-regression) [(3)](https://www.datacamp.com/courses/machine-learning-with-caret-in-r) [(4)](https://www.datacamp.com/courses/machine-learning-with-tree-based-models-in-r) courses for R. 

## Practical Assessment(s) Overview & Files

This course has two Practical Assessments. 

### Task 1

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and *k*-nearest neighbor (KNN) or Naive Bayes classification analysis. Students identify a set of variables to use and split the data into training and test sets before performing their classification analysis to answer this research question. 

My research question for this project was *"Can a KNN (k-nearest neighbors) model be used to identify patients with chronic back pain from the provided data?"*, continuing my line of questioning from prior analyses with different methods. I generated a KNN model with a test accuracy of 0.58 and an AUC score of just 0.52. Given this outcome, I had to conlude that a KNN model could not effectively identify patients with chronic back pain, based on the provided data. [My report for this project, including all of my Python code, can be viewed here.](d209task1.ipynb)

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. [That video can be seen here](https://drive.google.com/file/d/1kupWMxyiWuqhsIdhV2qZPVp5PGc7VplI/view?usp=share_link). 

### Task 2

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and decision trees, random forests, or advanced regression (lasso or ridge) analysis. Students identify a set of variables to use and split the data into training and test sets before performing their classification analysis to answer this research question. 

My research question for this project was *"Can a decision tree model using a boost method be used to identify patients with chronic back pain from the provided data?"*. This was continuing the same basic research question that I'd used for the prior several projects, including D209 Task 1. I generated a decision tree model that used Adaptive Boosting to finally generate a successful model at identifying patients with chronic back pain. The decision tree model had a test accuracy of 0.74 and an AUC score of 0.80, both of which represented significant improvements over the prior models that I had attempted to use to answer this question. [My report for this project, including all of my Python code, can be viewed here.](d209task2.ipynb)

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. [That video can be seen here](https://drive.google.com/file/d/1tdQWaZTwdBADMxNQ4bBWAy7TDC1qv8Sd/view?usp=share_link).