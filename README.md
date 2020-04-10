# Willow Real Estate: A Pilot Program in Ames, IA

#### Matthew Malone https://git.generalassemb.ly/mtm1186

## Problem Statement
The tech start up Willow Real Estate which is a online Real Estate Database company has been tasked by it's Investment Committee to provide a model that will be competetive with Zillow's Zestimate. Zillow's Zestimate is an automated valuation model that takes into account various home and neighborhood features that estimates home sales prices. The typical Zestimate error is $14, 000 according to online data. However, Zillow is an extremely large publically traded company and the investment committee has set a reasonable goal of a $25,000 error based off of Root Mean Squared Error (RMSE). This will be the first step before the Investment Committee provides more money to expand to new markets.


## Executive Summary
The Investment Committee has viewed the midwest as an untapped market for Willow and has decided your first model should be built using housing data provided by the City of Ames, IA assessors office. This data is from 2006-2010 and has been used in computing assessed values for individual residenal properties sold in Ames. The data set is robust and is a comprehensive overview of a homes land and builidng features. It includes everything an appraiser would use when appraising the fair market value of a home. The data set will be sufficient in building a competetive model to rival Zillow's.

# Data Dictionary
https://www.kaggle.com/c/dsi-us-11-project-2-regression-challenge/data

# Table of Contents
#### Loading Data
#### EDA
#### Modeling
#### Baseline Model
#### Linear Regression
#### Ridge
#### Lasso
#### Model Selection
#### Model Evaluation
#### Conclusion
#### Recommendations

# Model Evaluation
The models were limited in their performance because of the number of features they included. The model was underfit and as result perfomed poortly. This was consistent across the Linear Regression, Ridge, and Lasso Models. Due to additional constraints we weren't able to get a model to run properly with all of the features initially created. If this had been done correctly better target scores would most likely been achieved. The metrics used to evaluate all three models were fairly close to one another. Lasso and Ridge would most likely outperformed the Linear Regression model but were limited due to the number of features.

# Conclusion
The target score the Investment Committee set for Willow Real Estate was not achieved. The Investment committee has decided to stop any addtional funding until it can produce better models that are closer to the target score (RMSE) of $25,000. Due to the fact that the models used lacked complexity and had so few features directly contributed to their poor performance. This stems from upstream issues related to EDA that limited what features could be used in the model.

# Recommendations
Additonal investigation and manufacturing of features with linear relationships to the target will help increase model performance. Too few features were created through feature engineering. A deeper dive is required in EDA to identify trends and relationships. The data needs to be scaled appropriately, this was overlooked at times but is important to do. Inclued more features overall, use the "kitchen sink" approach, as we can always reduce the features to fine tune the models.
..
