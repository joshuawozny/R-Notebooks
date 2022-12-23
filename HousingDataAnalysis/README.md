Author: Joshua Wozny <br>
joshua.wozny@snhu.edu <br>
CS-303
<hr>

# Project One: Multiple Regression, Qualitative Variables Interactions, Quadratic Regression

> For Project One, you have been asked to create different regression models analyzing a housing data set. Before beginning work on the project, be sure to read through the Project One Guidelines and Rubric to understand what you need to do and how you will be graded on this assignment. Be sure to carefully review the Project One Summary Report template, which contains all of the questions that you will need to answer about the regression analyses you are performing. <br>

> For this project, you will be writing all the scripts yourself. You may reference the textbook and your previous work on the problem sets to help you write the scripts.</p>

## Scenario
You are a data analyst working for a real estate company. You have access to a large set of historical data that you can use to analyze relationships between different attributes of a house (such as square footage or the number of bathrooms) and the house’s selling price. You have been asked to create different regression models to predict sale prices for houses based on critical variable factors. These regression models will help your company set better prices when listing a home for a client. Setting better prices will ensure that listings can be sold within a reasonable amount of time.

There are several variables in this data set, but you will be working with the following important variables:
<table>
<tr>
<th>Variable</th>
<th>Description</th>
</tr>
<tr><td>price</td>
<td>Sale price of the home</td></tr>
<tr><td>bedrooms</td>
<td>Number of bedrooms</td></tr>
<tr><td>bathrooms</td>
<td>Number of bathrooms</td></tr>
<tr><td>sqft_living</td>
<td>Size of the living area in sqft</td></tr>
<tr><td>sqft_above</td>
<td>Size of the upper level in sqft</td></tr>
<tr><td>sqft_lot</td>
<td>Size of the lot in sqft</td></tr>
<tr><td>age</td>
<td>Age of the home</td></tr>
<tr><td>grade</td>
<td>Measure of craftsmanship and the quality of materials used to build the home</td></tr>
<tr><td>appliance_age</td>
<td>Average age of all appliances in the home</td></tr>
<tr><td>crime</td>
<td>Crime rate per 100,000 people</td></tr>
<tr><td>backyard</td>
<td>Home has a backyard (backyard=1) or not (backyard=0)</td></tr>
<tr><td>view</td>
<td>Home backs out to a lake (view=2), backs out to trees (view=1), or backs out to a road (view=0)</td></tr>
</table>
