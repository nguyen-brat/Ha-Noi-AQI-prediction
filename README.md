# Ha-Noi-AQI-prediction
code join in predicting air Quality competition

# **Preprocess data**
1. load data and imputation missing data using XGBoost (best result)
2. denoise data using rolling mean + fast fourier transform or smothing + fast fourier transform is also efficient
 # **Model**
 1. using N-beat model reach better accuracy in valid but lower in testing compare to using LSTM model which have a higher accuracy in testing but lower in valid
