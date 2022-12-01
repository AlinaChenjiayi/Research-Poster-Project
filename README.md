# Instacart Market Basket Analysis 
This project is for the Poster Project from QTM 302W course offered Fall 2022. A Instacart Market Basket Analysis is conducted, and recommendations in Business strategies are provided accordingly. 

#### -- Project Status: [Completed]

## Project Intro/Objective
This project conducts a market basket analysis of Instacart which is a leading online grocery platform in North America. According to proportion 71% of all-platform online grocery deliver orders came from Instacart yearly report, we believe that Instacart is a company with huge business potential, and it is worth to investigate key factors that influence its business. 


### Partner
* Christina Ding
* christina.ding@emory.edu


### Methods Used
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* R for visualization
* Python for modeling

## Project Description

Among this project, critical factors contribute to sales are determined with visualization from R. We investigated questions related to customer purchasing behaviors 
 - When usually people place order and reorder
 - What are most frequently ordered and reordered products and departments
 - Whether customers favor the organic products. 

Then, customer segmentation is done by using Principle Component Analysis (PCA) and K-Means clustering. We utilized PCA to reduce data dimension, resulting in 6 most important features related to aisles. Then, we used K-means clustering to classify customers with similar characteristics (budget, amount, products) into 4 major groups. Both PCA and K-Means clustering are implemented through pandas and sklearn package in python.

According to these key findings, we provide several concrete suggestions that might be useful for the Instacart Company. 
  - Create one click function based on customer clusters
  - Marketing towards "Eating Healthy" and "Buying Local"
  - Have more online assistants available and replenish stock based on frequently order timing periods
  - Focus on products from produce and dairy eggs departments' quality.
  - Improve the current "shop the recipes" features with kits that come with appropriate portions of products.

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. 

## Getting Started

1. Raw Data is being kept [Data] within this repo.
    
2. Data processing/transformation scripts are being kept in poster project.rmd file (Both R and Python code are in this file).
    *We use the reticulate package in R so that you can run python code in R markdown*  

3. You can run this project through the bindery
https://mybinder.org/v2/gh/AlinaChenjiayi/Research-Poster-Project/HEAD

## Contact
* Feel free to contact email jche797@emory.edu if you have any questions related to this project
