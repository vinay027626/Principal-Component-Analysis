# Principal-Component-Analysis

# PCA with Housing Dataset

## Context

<p>Consider the situation where you are working for Zillow as a data scientist.
Housing pricing predictions is the goal.</p>
<p>We know 80 things about each house to use as inputs to be able to predict the price of a house.</p>
<p>Your goal is to islotate the important features from the dataset and build a model which
can be used to predict the price of the houses.</p>
<p>Since there are too many features, Principal Component Analysis can be applied to
reduce the number of features used for the actual prediction model, without any loss of
information</p>

## Dataset to Work With<br>
https://www.kaggle.com/c/home-data-for-ml-course/data?select=train.csv<br>
Download the train.cv file and load it using pandas
<br>
<br>
<br>
## Brief Description of Dataset
With 79 explanatory variables describing (almost) every aspect of residential homes in
Ames, lowa, this competition challenges you to predict the final price of each home.
Detailed Description of Dataset<br>
https://www.kaggle.com/c/home-data-for-ml-course/data?select=data_description.txt<br>

# Assignments
<ol>
  <li>
    Data Cleanup and Exploratory Data Analysis (25%)</li>
    <ul>
      <li>
        Explore Basic statistic of each feature.
      </li>
      <li>
        Outlier Detection</li>
<li>
  Pick your own method to remove outliers</li>
<li>
  Explain the rationale</li>
      <li>
        Use your method of choice for imputation</li>
      <li>Explain the rationale</li>
      <li>
        Identify the target variable correctly</li>
      <li>Isolate the features with high correlation with the target variable</li>
  </ul><br>
  <li>
    Feature Preparation and Transformation (25%)
    <ul>
      <li>
        Drop Unnecessary Columns (All categorical variables, essentially)</li>
      <li>
        Apply Scaling to dataset to bring all variables to the same scale</li>
      <li>
        Feature Selection for isolating final set of variables for PCA</li>
    </ul><br>
  </li>
  <li>
    PCA (25%)
  <ul>
    <li>
      Threshold for Variance (90% - industry standard)</li>
    <li>
      Balance the number of features selected</li>
    </ul>
  </li><br>
  <li>
    Linear Regression (25%)
    <ul>
      <li>
        Fit model to cleaned-up dataset</li>
      <li>
        Comparative Study of with and without PCA</li>
    </ul>
  </li>
  </ol>
