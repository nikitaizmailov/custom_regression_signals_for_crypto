# custom_regression_signals_for_crypto
- A Machine Learning Regression Algorithm to generate trading signals for Crypto. Uses Binance API.
- Uses 30 day window to predict next day price of Bitcoin. i.e. t-29, t-29... t0 = X input features, t1 = y target label.
- Picked and Trained a RNN LSTM Regression model.
- Optimized Loss Function via Hyperparameter tuning and optimizer.
- On a Test set RMSE and MAE around 30%

## Plotting Predicted vs Actual BTC price labels. You can notice that the model picks up the pattern and has good degree of accuracy.
<img width="1094" alt="Screenshot 2022-05-23 at 11 08 13" src="https://user-images.githubusercontent.com/42198709/169773492-daada348-3a25-4ff9-b137-175ed0c3595e.png">
