# Important Features for Predicting Airbnb Prices

## Summary
<br>The objective of this project is to highlight listing features that should be used to estimate Airbnb listing prices. We apply the workflow and evaluate data for different cities in Canada. 

## The Data
<br>The data used in this study comes from the [Airbnb Data](http://insideairbnb.com/get-the-data/). The data for different Canadian cities, namely, Victoria, Vancouver, Toronto, Montreal, Quebec City, and New Brunswick are available and evaluated. We use a similar approach to study different datasets.
<br>
<br>The detailed listing data (listings.csv) are included in this [GitHub Folder]() specified using the name of the city.

## File Description
<br>The Jupyter Notebook files that are named according to the city names are the main files for data extraction, cleansing, transformation, and analysis. The analysis results, include the significant listing features for different cities and are exported and stored in <i>'city name'_feat.txt</i> files. The data for comparing the test set versus the predictions are exported and saved in <i>(city name)_pred.csv</i> file.
<br>Later the significant listing features stored in the txt file is loaded in the significant_feature Jupyter Notebook for comparision and the prediction results are loaded in scatter_plot Jupyter Notebook to compare the predicitons for different cities.
<br>../Airbnb_data/cityName/listing.csv&emsp;&emsp;Airbnb reference dataset
<br>../Airbnb_feature_analysis/cityName.ipynb&emsp;&emsp;Jupyter Notebook containing the extraction, cleansing, transformation, and analysis.
<br>../Airbnb_feature_analysis/cityName_feat.txt&emsp;&emsp;List of significant features
<br>../Airbnb_feature_analysis/cityName_pred.csv&emsp;&emsp;Predictions vs. actual data
<br>../Airbnb_feature_analysis/significant_features.ipynb&emsp;&emsp;Significant features (all cities)
<br>../Airbnb_feature_analysis/scatter_plot.ipynb&emsp;&emsp;Scatter plot for predictions vs. actual data (all cities)

## Installations
<br>Python 3 is required to run this project. Jupyter Notebook and the following libraries are required to preform the analysis and export the results: pandas, numpy, scipy, statsmodels, os, sklearn, Matplotlib, and seaborn.

## How to use the files
<br>The user should start with the cityName.ipynb file. The file loads the listing dataset and exports cityName_feat.txt and cityName_pred.csv files. After analysing all cities, [significant_features.ipynb]() and [Scatter_plot.ipynb]() are used for further analysis comparing the cities.
<br>Example:
<br>&emsp;1-&emsp;[Vancouver.ipynb]()
<br>&emsp;2a-&emsp;[Vancouver_feat.txt]()
<br>&emsp;2b-&emsp;[Vancouver_pred.csv]()
<br>&emsp;3-&emsp;Analyse step 1 for all cities
<br>&emsp;4-&emsp;[significant_features.ipynb]()
<br>&emsp;5-&emsp;[scatter_plot.ipynb]()

## Author
<br>Siavash Nejadi

## Licensing



Licencing, Authors, Acknowledgements