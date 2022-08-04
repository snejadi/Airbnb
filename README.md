# Identifying the Most Important Variables to Estimate the Target

## Summary
<br>The objective of this project is to highlight listing features related to the Airbnb listing price. This study aims at answering the following questions:
  - What are the important variables for predicting the target variable?
  - Are the predictor variables correlated with one another? How to mitigate this issue?

## The Data
<br> We used the listing data for Seattle, WA for this study. The data comes from [Airbnb](http://insideairbnb.com/get-the-data/). 
<br> Specifically, we use the [listing.csv](https://github.com/snejadi/Airbnb/blob/main/Airbnb_data/Seattle/listings.csv) file in this study. 
- The data consists of 4,686 data points for 74 different features. 28 features were selected and used for this analysis. Here, we discard the empty columns, URLs, names, id numbers, and the text columns that require further analysis.
<br> THe following figure shows the distribution of the price (the target) in the dataset:
![Figure_01](https://github.com/snejadi/Airbnb/blob/b0a1e57efc0808965626072a745a18e97788f018/figures/01_price.png)

## Analysis
<br> The analysis includes the following steps:
<br> First, we identify and mitigate Multicollinearity among the predictors (listing features). 
- To identify multicollinearity we study similar listing features in separate groups and:
  - Look at the correlation between variables (scatter plot or correlation coefficient)
  - Variance Inflation Factor (VIF)
- To mitigate multicollinearity, we remove the variable most related to the other variables. An alternative approach is to use Principal Component Analysis (PCA), which groups variables contributing similar information and reduces the dimensionality.
<br> Next, we perform a null hypothesis test and evaluate if there is a relationship between the variables and the outcome.
<br> The following boxplots show how different listing features relate to the price:
![Figure_02](https://github.com/snejadi/Airbnb/blob/b0a1e57efc0808965626072a745a18e97788f018/figures/12_acc_bedr_roomT_bath.png)
<br> The following figure, summarizes the Airbnb listing features related to the price:
![Figure_03](https://github.com/snejadi/Airbnb/blob/b0a1e57efc0808965626072a745a18e97788f018/figures/00_significant_features.jpg)

## File Description
<br> Jupyter Notebook is used for this study that includes the following steps: data extraction, cleansing, transformation, and analysis. 
- [Seattle.ipynb](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Seattle.ipynb)&emsp;&emsp;Jupyter Notebook containing the extraction, cleansing, transformation, and analysis.
- [listing.csv](https://github.com/snejadi/Airbnb/blob/main/Airbnb_data/Seattle/listings.csv)&emsp;&emsp;Airbnb reference dataset
- [figures](https://github.com/snejadi/Airbnb/tree/main/figures)&emsp;&emsp;The figures exported from Jupyter Notebook analysis file.

## Installations
<br>Python 3 is required to run this project. Jupyter Notebook and the following libraries are required to preform the analysis and export the results: pandas, numpy, scipy, stats, sklearn, matplotlib, seaborn, and squarify.

## Licensing, Acknowledgements
<br> The author wishes to acknowlwdge [Udacity](https://www.udacity.com/) and [Airbnb](https://airbnb.com/).

## Author
<br>[Siavash Nejadi](https://github.com/snejadi/)