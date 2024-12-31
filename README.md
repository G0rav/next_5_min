# next_5_min

Scalp Trading AI - Machine learning model to predict stock price movement for next 5 minutes using candlestick chart images.


```This is a fun project; don't use it for real trading. It will also be slow compared to trading bots, which operate in milliseconds.```



## Plan

### Data Preparation 

- Data collection - OHLCV 5 min interval.
- Kaggle, scrap, yahoo finance or any other APIs
- Chart generation pipeline - from OHCLV
- Candlestick Charts
  - Fixed time window (100 candles)
  - 5,10,15 min candles
  - Volume subplot
  - use standard green and red colors
  - Resolution standardization; percentage or log


### EDA & Training Data Pipeline 

- Prepare target variable/variables
- Analyze charts
- Splits, time based or random 
- Data Generator - real time chart generation from csv data


### Model Development
- Model architecture building - single image, multiple images 5,10, 15 min timeframe
- Optimize hyperparameters
- Accuracy Latency trade-off 


### Evaluation Framework

- **Regression Metrics**
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R-squared score
  - Direction accuracy

- **Trading Metrics**
  - Prediction error distribution
  - Risk-adjusted returns
  - Maximum drawdown
  - Win rate analysis
  - Error threshold analysis


### Training 
  - Loss function selection
  - Optimizer configuration
  - Learning rate scheduling
  - Batch size optimization


### Testing & Refinement

- Analyze prediction errors
- Refine model architecture
- Optimize performance


## Success Metrics

### Technical Metrics
- RMSE < market volatility
- Direction accuracy > 60%
- R-squared > 0.6
- Prediction within 0.1% range > 50%

### Performance Requirements
- Inference time < 100ms
- Memory usage < 4GB
- GPU utilization < 80%
- Batch processing capability


## Future Extensions

1. Multi-timeframe analysis
2. Multiple model building; consider news, tabular data

- **Additional Targets**
  - High/Low range prediction
  - Volume change prediction
  - Price movement range

