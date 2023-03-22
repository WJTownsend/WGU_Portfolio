# D213: Advanced Data Analysis

## Course Summary

WGU states that D213 Advanced Data Analytics prepares students for career-long growth in steadily advancing tools and techniques and provides emerging concepts in data analysis. This course hones the mental and theoretical flexibility that will be required of analysts in the coming decades while grounding their approach firmly in ethical and organizational-need-focused practice. Topics include machine learning, neural networks, randomness, and unconventional data sources.

This course has two Practical Assessments. 

## Course Objectives

WGU outlines the following competencies as a part of this class:
- **Time Series Analysis:** The graduate applies time series models in generating forecasts.
- **Neural Networks:** The graduate builds neural networks in the context of machine-learning modeling.
- **Natural Language Processing:** The graduate extracts insights from text data using effective and appropriate natural processing (NLP) models.

## Course Materials

WGU's course materials consist of [(1)](https://www.datacamp.com/courses/introduction-to-deep-learning-in-python) [(2)](https://www.datacamp.com/courses/introduction-to-tensorflow-in-python) [(3)](https://www.datacamp.com/courses/natural-language-generation-in-python-archived) [(4)](https://www.datacamp.com/courses/time-series-analysis-in-python) courses on DataCamp for Python or [(1)](https://www.datacamp.com/courses/time-series-analysis-in-r) [(2)](https://www.datacamp.com/courses/arima-models-in-r) [(3)](https://www.datacamp.com/courses/introduction-to-tensorflow-in-r-archived) [(4)](https://www.datacamp.com/courses/introduction-to-natural-language-processing-in-r) [(5)](https://www.datacamp.com/courses/text-mining-with-bag-of-words-in-r) [(6)](https://www.datacamp.com/courses/sentiment-analysis-in-r) courses for R. 

## Practical Assessment(s) Overview & Files

This course has two Practical Assessments. 

### Task 1

This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and ARIMA/SARIMA time series modelling techniques. The student must generate a number of time series visualizations, evaluate the stationarity of the series, account for trends and seasonality, and develop a forecast in the course of addressing this research question.   

My research question for this project was *"Can I effectively and correctly forecast WGU Hospital System daily revenues in an accurate fashion, compared to the actual observed daily revenues?"* Using 20 months of daily revenue data, I generated a forecast of the next 4 months of daily revenues to compare to the observed values. The resulting forecast model was largely ineffective, which I believe was primarily due to a very large portion of the training data being not representative of later data in both the training and testing intervals. [My report for this project, including all of my Python code, can be viewed here.](d213task1.ipynb)

This task did not require a video presentation.  

### Task 2

This project requires the student to select one of a number of authorized datasets to develop a research question to be addressed through sentiment analysis, using Natural Language Processing (NLP) and machine learning within a neural network. The student must perform an exploratory data analysis of their selected dataset, tokenize the data, and develop a model using TensorFlow, including justification of both hyperparameters of that model and the neural network layers involved. Finally, the effectiveness of the generated model must be evaluated. 

I chose to use a dataset of reviews on the Steam PC gaming platform from Australian users. For this project, I used a neural network to perform a sentiment analysis on the written reviews of users for games to predict if the user would recommend that game or not by using NLP techniques. The handling of this unstructured data was a laborious project, as I had to deal with non-English words, English and gaming slang terms, and a customized set of stopwords. After the data was tokenized, sets for training, validation, and testing were generated and padded. A TensorFlow model was generated with nearly 14,000,000 parameters, using an Embedding layer followed by a Flatten layer, and then a series of Dense nodes progressing towards a final sigmoid activation function to generate the prediction of a game being recommended or not. The model finished with a relatively high accuracy (over 90%) with a marginal confidence (loss of 0.50). This was suspected to result from both the smaller number of games which were not recommended in the dataset (around 1/9 of total reviews) and a suspicion that the verbiage used to describe those games which are not recommended was more varied than the verbiage for why a game would be recommended. [My report for this project, including all of my Python code, can be viewed here.](d213task2.ipynb)

This task did not require a video presentation.  