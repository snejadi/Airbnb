# Important Features for Predicting Airbnb Prices

## Summary
The objective of this project is to highlight listing features that should be used to estimate Airbnb listing prices. We apply the workflow and evaluate data for different cities in Canada. 

## The Data
The data used in this study comes from the [Airbnb Data](http://insideairbnb.com/get-the-data/). The data for different Canadian cities, namely, Victoria, Vancouver, Toronto, Montreal, Quebec City, and New Brunswick are available and evaluated. We use a similar approach to study different datasets.

The detailed listing data (listings.csv) are included in this [GitHub Folder]() specified using the name of the city.

## File Description
The Jupyter Notebook files that are named according to the city names are the main files for data extraction, cleansing, transformation, and analysis. The analysis results, include the significant listing features for different cities and are exported and stored in <i>'city name'_feat.txt</i> files. The data for comparing the test set versus the predictions are exported and saved in <i>(city name)_pred.csv</i> file.
Later the significant listing features stored in the txt file is loaded in the significant_feature Jupyter Notebook for comparision and the prediction results are loaded in scatter_plot Jupyter Notebook to compare the predicitons for different cities.
../Airbnb_data/cityName/listing.csv            Airbnb reference dataset
../Airbnb_feature_analysis/cityName.ipynb      Jupyter Notebook containing the extraction, cleansing, transformation, and analysis.
../Airbnb_feature_analysis/cityName_feat.txt    List of significant features
../Airbnb_feature_analysis/cityName_pred.csv    Predictions vs. actual data
../Airbnb_feature_analysis/significant_features.ipynb Significant features (all cities)
../Airbnb_feature_analysis/scatter_plot.ipynb         Scatter plot for predictions vs. actual data (all cities)

## Installations
Python 3 is required to run this project. Jupyter Notebook and the following libraries are required to preform the analysis and export the results: pandas, numPy, scipy, statsmodels, os, sklearn, Matplotlib, and seaborn.

## How to use the files
The user should start with the cityName.ipynb file. The file loads the listing dataset and exports cityName_feat.txt and cityName_pred.csv files. After analysing all cities, [significant_features.ipynb]() and [Scatter_plot.ipynb]() are used for further analysis comparing the cities.
Example:
1-  [Vancouver.ipynb]()
2a- [Vancouver_feat.txt]()
2b- [Vancouver_pred.csv]()
3-  Analyse step 1 for all cities
4-  [significant_features.ipynb]()
5-  [scatter_plot.ipynb]()

## Author
Siavash Nejadi

## Licensing



Licencing, Authors, Acknowledgements