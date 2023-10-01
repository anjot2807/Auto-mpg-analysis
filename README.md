# Auto-mpg-analysis


This repository contains an analysis of the Auto-MPG dataset, which explores the relationship between various attributes of automobiles and their fuel efficiency (miles per gallon, MPG). The analysis includes the use of manual feature selection methods, specifically forward and backward elimination, to identify the most relevant variables for building a predictive model.

## Dataset Description

The Auto-MPG dataset contains information about various car attributes, including displacement, horsepower, acceleration, and more. The main objective of this analysis is to understand how these attributes influence the fuel efficiency of automobiles.

## Analysis Process

### Forward Feature Selection

In the analysis, I employed forward feature selection to systematically evaluate the impact of different independent variables on the target variable (MPG). This method involves iteratively adding variables to the model and selecting the ones that contribute the most to model performance. 

After conducting forward feature selection, the following variables were identified as the most influential for the model: 'displacement,' 'horsepower,' and 'acceleration.' These variables collectively provide the most optimal predictive power for estimating MPG.

### Backward Feature Selection

Additionally, I applied backward feature selection, which is the reverse of forward selection. In this approach, we start with all available variables and iteratively remove the least significant ones. After performing backward feature selection, it was determined that the best independent variables for the model are 'displacement' and 'horsepower.' These variables were found to be the most relevant for predicting MPG.

## Conclusion

The manual feature selection methods, forward and backward elimination, provided valuable insights into the most significant variables for predicting fuel efficiency (MPG) in the Auto-MPG dataset. By focusing on 'displacement,' 'horsepower,' and 'acceleration,' we have identified the most influential factors that contribute to the model's accuracy.

Feel free to explore the analysis code and results in this repository to gain a deeper understanding of the relationship between automobile attributes and fuel efficiency.
