# Acea-Water-Analytics---Kaggle-Competition
In this competition, Acea Group focused on the water sector to preserve water bodies by forecasting the water level. Each dataset has a different kind of waterbody with its unique behavior and characteristics. Available Datasets are:

Aquifer (Auser, Doganella, Luco, Petrignano)
Water Spring (Amiata, Lupa, Madonna di Canneto)
River (Arno)
Lake (Bilancino) The models' predictive power will be evaluated with both Mean Absolute Error (MAE) and Mean Square Error (MSE).\

We performed EDA for 9 datasets for 4 different water bodies described above.
There was a lot of missing data. Hence, We had to be careful while dealing with missing values to avoid data bias and overfitting the model.
We explored the data and omitted insignificant columns, and imputed the values in the essential columns.

We applied time series forecasting using XG-boost and LSTM RNN models.

We also implemented an augmented Dicky Fullers test to recognize the stationarity of the time series.

To evaluate the performance, we considered Mean Absolute Error for the predicting models.

We compared the performances of each model for all 4 water bodies, and based on the performance metric, we found that,

For Aquifer, Water Spring, and River LSTM RNN was the best predictive model.
For Lake, XGBoost was the best predictive model.
