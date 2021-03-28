# Honours-Course Assignment 1
Contents:
Note about plagiarism
Problem Definition
Data Analysis
Question Answers
References
Assignment todo list
Plagiarism
Students may discuss with each other for information sharing regarding solutions, tools, and techniques to approach the assignment. However, they should implement their own code from scratch. Students found violating general code of conduct might be penalized by reducing their scores.

These assignments are for learning and should be the mutual goal of everybody, teachers, and students alike.

Problem Definition
Access an open source dataset “Titanic”. Apply pre-processing techniques on the raw dataset.

Data analysis
Data Acquisition
Data cleaning/transforms
Data Visualization
Feature Engineering
Dimensionality Reduction/Feature Selection
Question Answers
What is Data?
Can be transformed
What should be the data format?
Structured
Tabular
Well-defined
How do we acquire it?
Sensors
People counter
Cookies data
Surveys
Government
Private
Transactional records
What is data cleaning?
Processing to more readable format
Identifying outliers
Usability
Why to do data cleaning?
Formatting
Data-type - validating data
What is feature engineering?
Data aggregation
Derived features
Crossed features
Fourier features
Why to do feature engineering?
What is visualization?
What are the various types of data?
Textual
Categorical
Numerical
What are the techniques to handle different kinds of data?
Textualq
Removing stop-words, punctuation
Stemming
Embedding
pronoun-noun- entity recognition
Categorical
Nominal
Ordinal
Boolean
Numerical
Change scale
Normalize
Standardize
Robust
Change distribution
Power
Quantile
Discretize
Engineer
Polynomial
Data imputation
Fill Nan's or nulls
Textual
Categorical
Numerical
Once data is enriched, what to do next?
What are the different varieties of plots?
Line
Bar
Stacked
Non-stacked
Histogram
Box and whisker
Scatter
Pie chart
Wind-rose
Correlation and partial correlation
Many more - (list what interests you with examples)
What are Feature Selection techniques?
Matrix Factorization
PCA
SVD
References
Data Preparation techniques
List of books for data processing
Data Visualization - python matplotlib
Data preparation
List of Visualization plots
RandomForestClassifier model
Assignment ToDo List
Notes:

Take it as a challenge to go beyond boudaries of the assignment
Apply all that you can.
Lookout for improvisations.
Students will be scored based on efforts taken. (Copying is strictly prohibited and will be treated severely.)
As a study material for further projects and your understanding, elaborately add more points to this file.
You can also make a GitHub project and use this first draft for continuous updates.
Ideally use Python3.7.x, Pandas, Matplotlib, Seaborn, Sklearn, etc. Optionally use R, Matlab, etc.
ToDo List:

Download the dataset.

Apply the relevant data processing techniques

Remember to do the analysis separately for test and train data.
Ideally prepare a pipeline for data processing
Input - single data instance
Output - Transformed instances
Plot various visualizations

Make it generic - Reusable for the last assignment
Think and answer a few data scientific questions (interesting and insightful) using data analysis?

How many of the survived were male, female? Within this, how many were children in each gender category?
What does the SibSp, Parch, Cabin, Embark column signify? Can we attach external datasets to enrich the information?
Is Fare just a number or is correlated with other columns? If yes, which ones?
Students can add more such questions.
Advanced (assignment 2): Fit a model like LogisticRegression and RandomForestRegressor using sklearn.
