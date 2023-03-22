# D212: Data Mining II

## Course Summary

WGU states that D212 Data Mining II adds vital tools to the data analytics arsenal that incorporates unsupervised models. This course explains when, how, and why to use these tools to best meet organizational needs. 

This course has three Practical Assessments. 

## Course Objectives

WGU outlines the following competencies as a part of this class:
- **Hierarchical & K-Means Clustering Techniques:** The graduate applies clustering techniques to accurately predict outcomes of interest.
- **Principal Component Analysis:** The graduate implements dimension reduction methods to identify significant variables.
- **Market Basket Analysis:** The graduate predicts patterns in data using association rules and lift analysis.

## Course Materials

WGU's course materials consist of [(1)](https://www.datacamp.com/courses/unsupervised-learning-in-python) [(2)](https://www.datacamp.com/courses/cluster-analysis-in-python) [(3)](https://www.datacamp.com/courses/dimensionality-reduction-in-python) [(4)](https://www.datacamp.com/courses/market-basket-analysis-in-python) courses on DataCamp for Python or [(1)](https://www.datacamp.com/courses/unsupervised-learning-in-r) [(2)](https://www.datacamp.com/courses/cluster-analysis-in-r) [(3)](https://www.datacamp.com/courses/advanced-dimensionality-reduction-in-r) [(4)](https://www.datacamp.com/courses/market-basket-analysis-in-r) courses for R. 

## Practical Assessment(s) Overview & Files

This course has three Practical Assessments. 

### Task 1

This project requires the student to use one either k-means or hierarchical clustering on one of the two provided datasets (medical or churn) to analyze the data. After selecting the variables of interest, the student generates a clustering model to facilitate this analysis. The student then communicates the results of their analysis and evaluates the model.  

For this project, I analyzed on survey data in the medical dataset using a modified version of a Likert scale. While the answers to each of 8 survey questions across 10,000 patients appeared identical in their descriptive statistics, hierarchical clustering revealed two distinct clusters of patients with pronounced differences in their survey responses. [My report for this project, including all of my Python code, can be viewed here.](d212task1.ipynb)

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. [That video can be seen here](https://drive.google.com/file/d/1Peq0hjFb65x4jyvxtBItzeQJ4IT0xYWU/view?usp=share_link). 

### Task 2

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and Principal Component Analysis (PCA) to reduce the dimensionality of the dataset (over 50 features). The student identifies the number of principal components and the variance of each component, before addressing the research question with those principal components. 

My research question for this project was *"Can patient hospital readmission be effectively predicted through a decision tree classifier with adaptive boosting after principal component is used to reduce the dimensionality of the dataset?"* The dataset included 12 quantifiable features which could be incorporated into PCA, and several of these struck me as having no practical significance to the situation. Nonetheless, after performing PCA, my decision tree model was able to predict patients who would be readmitted to the hospital with 88% accuracy and an AUC score of 0.876. It is worth noting that this dataset is artificial, but this was a genuinely surprising result. [My report for this project, including all of my Python code, can be viewed here.](d212task2.ipynb)

This task did not require a video presentation. 

### Task 3

This project requires the student to develop and answer a research question regarding one of two new datasets, using market basket analysis and association rules to analyze customer behaviors. 

My research question for this project was *"What (if any) medications are positively associated with prescriptions & purhcases of Cialis?"* In other words, this was examining what medications are also prescribed and purchased by patients alongside Cialis.  [My report for this project, including all of my Python code, can be viewed here.](d212task3.ipynb) 

This task required a video presentation, demonstrating the successful operation of all code included in my report and covering certain aspects of the report. I found that several association rules existed within the data, but with the scores for support, confidence, and lift that I used to establish a final list of the "top association rules", I found only one rule that involved Cialis. That rule was "If Cialis, then Abilify", meaning that if Cialis was purchased, a purchase of Abilify was more likely. [That video can be seen here](https://drive.google.com/file/d/1-_n-VdGwriJwXF40Ytu9gYONlZryKLzp/view?usp=share_link).

My work on this project earned [an Excellence Award from WGU](d212task3award.pdf). The evaluator for this project who submitted my work for the award made the following observations. *“This submission on market basket analysis was excellent because not only did it satisfy all the rubric requirements to demonstrate competency in the method, but it also then applied the analysis to a practical use-case on the relationship between specific prescriptions to achieve medical insights.”*