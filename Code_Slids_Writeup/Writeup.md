# Data Scientist Job Change Prediction

## Abstract
A company who provided Data Science training is in need of Data Scientist for their own company. However, they faced difficulties in hiring process. After processing some Candidates, Candidates tend to bail out in end of recruitment process. This situation made HR team to start over again to find the suitable candidate.

As the end of the year, HR department decided to make new enhancement in the process of recruitment from candidates who sign up their training. The ais for this enhancement is Company will easily known which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.


## Design
The dataset contains around 19158 with 14 features, Some of the features were dropped 
and other grouped into more general categories.

## Data
The dataset contains around 19158 with 14 features, 
The data was obtained from kaggle the predictions of data scientist job change were drawn from multiple features such as training hours, gender experiance,last new job.


## Algorithms
Pre-processing
1. Remove extra unnecessary details.
2. Created plots to visualize the relationships between the target and predictors, and between the variables themselves.
3. Decided which features to keep and which to drop.

## Feature Engineering
1. Convert some columns into Numeric Values
2. Convert some categorical variables into dummy variables
3. Split data to train and test and validation.

## Models
1. Several Classificatio models were used such as : Logistic  Regression , Random Forst , KNN , Decision Tree ,XGBoost , SVC , GardientBoosting classifier , AdaBoost classifier ,MLP classifier
2. We picked the model with the highest F1 score : XGBoost.

## Model Evaluation and Selection
1. The dataset observations of 1300 were split into 60/20/20 .
2. The evaluation of our models was based on F1 score.

## Tools
Tools: 
- Python, and Jupyter Notebook , Flask, DeepNote
- Libraries: BeautifulSoup, Selenium , Pandas, Numby, Sklearn, and Matplotlib ,Seaborn.


