
# Understanding Influenza Outbreaks Using Historical Data and Socioeconomic Factors

*<h3>Report: <a href="/DS_Influenza_Report.pdf">Influenza Outbreaks Report</a></h3>*

<h3>Dataset details</h3>

Primary Dataset: 

* https://healthdata.gov/dataset/influenza-laboratory-confirmed-cases-county-beginning-2009-10-season

Secondary Data:

* Temperature and precipitation: https://www.ncdc.noaa.gov/cdo-web/search
* Temperature and precipitation alternative: http://climod2.nrcc.cornell.edu/
* Temperature historical averages for specific cities = http://www.nrcc.cornell.edu/wxstation/comparative/comparative.html
* Demographics, density, poverty and unemployment: https://www.ers.usda.gov/data-products/atlas-of-rural-and-small-town-america/download-the-data/ 
* Vaccination: https://www.cdc.gov/nchs/nis/data_files.htm
* Inter-County Migration: https://www.census.gov/data/tables/2017/demo/geographic-mobility/county-to-county-migration-2013-2017.html
* County GDP: https://www.bea.gov/data/gdp/gdp-county 
* Google Trends: https://trends.google.com/trends/explore?geo=US-NY&q=flu

<h3>Libraries Used</h3>

* Numpy
* Pandas
* MatplotLib
* Scikit-Learn (sklearn)
* Keras*

<h3>Feature Engineering</h3>

* InfluenzaOutbreak_DataPreparation.ipynb
* IO_weatherPrep.ipynb
* TargetGenerator.ipynb
* Fill_weather_nan.ipynb
* IO_weatherPrep.ipynb

<h3>Data Analysis</h3>

* IO_Analysis.ipynb

<h3>Prediction models</h3>

* IO_pred_model.ipynb
* IO_pred_model_without_historicData.ipynb*
* base_model_performance.ipynb
* Neural_net.ipynb*	

\* Not used in Report

<h3> Performance comparision of prediction models </h3>
  <img src="/Plots/Model_Performance.png" height="246px" width="250px"">

*<h4>For more details: <a href="/DS_Influenza_Report.pdf">Influenza Outbreaks Report</a></h4>*
