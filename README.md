# Important Features for Predicting Airbnb Prices

## Summary
<br>The objective of this project is to highlight listing features that should be used to estimate Airbnb listing prices. We apply the workflow and evaluate data for different cities in Canada. 

## The Data
<br>The data used in this study comes from the [Airbnb Data](http://insideairbnb.com/get-the-data/). The data for different Canadian cities, namely, Victoria, Vancouver, Toronto, Montreal, Quebec City, and New Brunswick are available and evaluated. We use a similar approach to study different datasets.
<br>
<br>The detailed listing data (listings.csv) are included in [Airbnb_data](https://github.com/snejadi/Airbnb/tree/main/Airbnb_data) specified using the name of the city.

## Analysis
<br> Jupyter notebook is used to prefrom the analysis. The ipynb files are included in [Airbnb_analysis](https://github.com/snejadi/Airbnb/tree/main/Airbnb_analysis).

## File Description
<br>The Jupyter Notebook files that are named according to the city names are the main files for data extraction, cleansing, transformation, and analysis. The analysis results, include the significant listing features for different cities and are exported and stored in <i>city name</i>_feat.txt files. The data for comparing the test set versus the predictions are exported and saved in <i>city name</i>_pred.csv file.
<br>Later the significant listing features stored in the txt file is loaded in the significant_feature Jupyter Notebook for comparision and the prediction results are loaded in scatter_plot Jupyter Notebook to compare the predicitons for different cities.
<br>../Airbnb_data/<i>city name</i>/listing.csv&emsp;&emsp;Airbnb reference dataset
<br>../Airbnb_analysis/<i>city name</i>.ipynb&emsp;&emsp;Jupyter Notebook containing the extraction, cleansing, transformation, and analysis.
<br>../Airbnb_analysis/<i>city name</i>_feat.txt&emsp;&emsp;List of significant features
<br>../Airbnb_analysis/<i>city name</i>_pred.csv&emsp;&emsp;Predictions vs. actual data
<br>../Airbnb_analysis/significant_features.ipynb&emsp;&emsp;Significant features (all cities)
<br>../Airbnb_analysis/scatter_plot.ipynb&emsp;&emsp;Scatter plot for predictions vs. actual data (all cities)

## Installations
<br>Python 3 is required to run this project. Jupyter Notebook and the following libraries are required to preform the analysis and export the results: pandas, numpy, scipy, statsmodels, os, sklearn, Matplotlib, and seaborn.

## How to use the files
<br>The user should start with the <i>city name</i>.ipynb file. The file loads the listing dataset and exports <i>city name</i>_feat.txt and <i>city name</i>_pred.csv files. After analysing all cities, [significant_features](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Significant_Features.ipynb) and the [scatter_plot](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Scatter_Plot.ipynb) are used for further analysis and comparing the cities.
<br>Example:
<br>&emsp;1-&emsp;[Vancouver.ipynb](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Vancouver.ipynb)
<br>&emsp;2a-&emsp;[Vancouver_feat.txt](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Vancouver_feat.txt)
<br>&emsp;2b-&emsp;[Vancouver_pred.csv](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Vancouver_pred.csv)
<br>&emsp;3-&emsp;Run the analyse (step 1) for all cities, that exports the txt and csv files
<br>&emsp;4-&emsp;[significant_features.ipynb](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Significant_Features.ipynb)
<br>&emsp;5-&emsp;[scatter_plot.ipynb](https://github.com/snejadi/Airbnb/blob/main/Airbnb_analysis/Scatter_Plot.ipynb)

## Author
<br>Siavash Nejadi