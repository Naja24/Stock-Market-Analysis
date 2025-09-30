# TFT Stock Price Prediction Model Performance Report

## Model Architecture
- LSTM Hidden Units: 256
- Attention Heads: 8 (size: 64)
- Dropout Rate: 0.2
- Recurrent Dropout: 0.1
- Context Length: 24 days

## Training Information
- Total Epochs: 37
- Best Epoch: 22
- Best Validation Loss: 0.000571
- Final Learning Rate: 0.0003

## Performance Metrics

### Training Set
- MAE: 7.2290
- MSE: 72.6540
- RMSE: 8.5237
- MAPE: 5.7583
- R-squared: 0.9662

### Validation Set
- MAE: 6.1851
- MSE: 55.7533
- RMSE: 7.4668
- MAPE: 2.8817
- R-squared: 0.2731

### Test Set
- MAE: 8.9650

- MSE: 99.3294

- RMSE: 9.9664

- MAPE: 4.0622

- R-squared: -36.0633

## Feature Importance
Based on correlation with the target variable (Adj_Close):


## Future Predictions
- Prediction Horizon: 30 trading days
- Starting Date: 2025-04-23
- Ending Date: 2025-06-03
- Predicted Price Change: 3.00 (1.40%)

## Recommendations and Next Steps
- Consider adding more external factors like market indices, commodity prices, or economic indicators
- Experiment with different context lengths to capture various market cycles
- Implement a weighted ensemble with other models (ARIMA, Prophet, etc.) to improve robustness
- Add risk management metrics like Value at Risk (VaR) to the predictions
- Update the model regularly as new data becomes available
