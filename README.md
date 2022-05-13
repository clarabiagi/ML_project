# ML_project

The aim of our project is to predict the precipitation amount in Dublin using neural networks. 
Firstly, we repeated the analysis of [Prabhanshu Attri et al](https://keras.io/examples/timeseries/timeseries_weather_forecasting/) with our data, then we try to make prediction with different neural network architectures.

We combined LSTM, GRU and dense layers and try out different parameters to see how predictions change.
Notebooks are composed as follows:
 - [Data_norm](./notebooks/Data_norm.ipynb) notebook contains a presentation of data and then, as in [Prabhanshu Attri et al](https://keras.io/examples/timeseries/timeseries_weather_forecasting/), we use the normalised version of data. All relevant variables are included in the analysis
 - [Data](./notebooks/Data.ipynb) notebook is identical to the first notebook but withouth presentation of data and with data not normalised. Here we found the best model, and we make prediction
 - The notebook [functions](./notebooks/functions.ipynb) contains libraries and functions needed for the analysis.
