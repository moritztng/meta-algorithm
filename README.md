# Meta Algorithm
A universal meta algorithm for machine learning projects - executed by myself. 

## Step 0: Define the problem
1. Define input and output
2. Decide if classification or regression 
3. Decide if supervised or unsupervised
4. Define evaluation metric

## Step 1: Collect data
1. Define the population 
2. Choose a kind of study (experiment or survey)
3. If survey: define sampling method 
3. If experiment: define assignment method / kind of manipulation and control for disruptive factor
4. Choose sample size

## Step 2: Analyze data
1. Take a look at the shape
2. Take a quick glance 
3. Analyze the most important statistics of the variables (mean, meadian, variance, missing values)
4. Analyze each variable in depth: statistics, distribution
5. Analyze relationships: scatterplot matrix with correlation coefficient

## Step 4: Select Features

## Step 5: Clean data
1. Analyze columns for missing values and outliers -> drop column / replace with values / do nothing
2. Analyze rows for missing values and outliers -> drop row / replace with values / do nothing

## Step 8: Data augmentation (optional)

## Step 9: Feature engineering (optional)

## Step 10: Dummy encoding 
1. Identify categorical non-ordinal features
2. Create dummy variables for those features
3. Drop original features

## Step 10: Feature scaling (optional)
1. Identify skewed variables
2. Take log of those variables
3. Standardize or normalize features

## Step 11: Compress data with PCA (optional)
1. Choose number of components
2. Fit components
3. Interpret components
4. Compress data

## Step 12: Split data
- Training data: 70%
- Validation data: 15%
- Test data: 15%

## Step 13: Choose model, loss-function, learning-algorithm
1. Choose Model
1. Supervised regression: linear model 
1. Supervised classification: logistic model, svm, decision trees, naive bayes, neural network 
1. Unsupervised clustering: KMeans, Hierachical Clustering, DBScan, Gaussian Mixture Model
2. Choose loss-function
3. Choose learning-algorithm 

## Step 14: Choose hyperparameters:
1. Choose hyperparameters of model 
2. Choose hyperparameters of loss-function 
3. Choose hyperparameters of learning-algorithm  
4. Choose sample size

## Step 15: Fit model 

## Step 16: Evaluate model
1.Choose metric
1.Classification: accuracy, precision, recall, F-Score, loss
1.Regression: (adjusted) correlation coefficient, sum of squared resiudal
1.Clustering: adjusted rand score, silhouette coefficient
2.Evaluate model on training and cross-validation set
3.Check bias/underfitting and variance/overfitting

## Go to: Step 14

## Step 17: Choose hyperparameter with best cross-validation score

## Go to: Step 13

## Step 18: Choose model, loss-function and learning-algorithm with best cross-validation score

## Step 19: Evaluate model on test data

## Step 20: Sanity check model by inferencing on random example (optional)

## Step 21: Interpret model (optional)

## Step 22: Deploy / save model
