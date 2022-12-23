Author: Joshua Wozny <br>
joshua.wozny@snhu.edu <br>
CS-303
<hr>

# Project Two: Logistic Regression and Random Forests

> For Project Two, you have been asked to create different models analyzing a Heart Disease data set. Before beginning work on the project, be sure to read through the Project Two Guidelines and Rubric to understand what you need to do and how you will be graded on this assignment. Be sure to carefully review the Project Two Summary Report template, which contains all of the questions that you will need to answer about the regression analyses you are performing. <br>

> For this project, you will be writing all the scripts yourself. You may reference the textbook and your previous work on the problem sets to help you write the scripts.

## Scenario
You are a data analyst researching risk factors for heart disease at a university hospital. You have access to a large set of historical data that you can use to analyze patterns between different health indicators (e.g. fasting blood sugar, maximum heart rate, etc.) and the presence of heart disease. You have been asked to create different logistic regression models that predict whether or not a person is at risk for heart disease. A model like this could eventually be used to evaluate medical records and look for risks that might not be obvious to human doctors. You have also been asked to create a classification random forest model to predict the risk of heart disease and a regression random forest model to predict the maximum heart rate achieved.

There are several variables in this data set, but you will be working with the following important variables:
<table>
<tr>
<th>Variable</th>
<th>Description</th>
</tr>
<tr><td>age</td>
<td>The person's age in years</td></tr>
<tr><td>sex</td>
<td>The person's sex (1 = male, 0 = female)</td></tr>
<tr><td>cp</td>
<td>The type of chest pain experienced (0=no pain, 1=typical angina, 2=atypical angina, 3=non-anginal pain)</td></tr>
<tr><td>trestbps</td>
<td>The person's resting blood pressure</td></tr>
<tr><td>chol</td>
<td>The person's cholesterol measurement in mg/dl</td></tr>
<tr><td>fbs</td>
<td>The person's fasting blood sugar is greater than 120 mg/dl (1 = true, 0 = false)</td></tr>
<tr><td>restecg</td>
<td>Resting electrocardiographic measurement (0=normal, 1=having ST-T wave abnormality, 2=showing probable or definite left ventricular hypertrophy by Estes' criteria)</td></tr>
<tr><td>thalach</td>
<td>The person's maximum heart rate achieved</td></tr>
<tr><td>exang</td>
<td>Exercise-induced angina (1=yes, 0=no)</td></tr>
<tr><td>oldpeak</td>
<td>ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot)</td></tr>
<tr><td>slope</td>
<td>The slope of the peak exercise ST segment (1=upsloping, 2=flat, 3=downsloping)</td></tr>
<tr><td>ca</td>
<td>The number of major vessels (0-3)</td></tr>
<tr><td>target</td>
<td>Heart disease (0=no, 1=yes)</td></tr>
</table>
