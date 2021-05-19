# Forecasting leaf area index with SARIMA model

Using grid search to find the most ideal SARIMA model to predict leaf area index from a single plot in the Amazon rainforest. LAI data is collected from NASA Earth Observations and is available at https://neo.sci.gsfc.nasa.gov/view.php?datasetId=MOD15A2_M_LAI. 

The current model is not a good fit. The model residuals imply correlation, and the data appears to still have trend or seasonal trend after first and seasonal difference. Further preprocessing is necessary to achieve a better result.
