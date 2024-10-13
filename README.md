# Financial Analyzer

This project contains a FinancialAnalyzer class that performs various technical analysis calculations and visualizations on stock data.
Supported Financial Technical Analysis are:
- Moving Averages (SMA, EMA, DEMA, TEMA)
- MACD, PPO
- Ichimoku Cloud
- DMI, ADX, ADXR
- Disparity
- RSI, Stochastic RSI
- Stochastic Oscilaltor
- Price ROC
- Bollinger Bands and Keltner Channels
- ATR
- OBV
- CMF, Chaikin OSC
- Force Index
- AR/BR
- TRIX, Mass Index
- Parabolic SAR
- Three Line Break Chart

## Features
- Calculates various technical indicators
- Visualizes indicators using matplotlib
- Performs comprehensive analysis of stock data

## Usage
```python
analyzer = FinancialAnalyzer('AAPL')

### For comprehensive analysis (multiple plots)
results = analyzer.comprehensive_analysis('2023-01-01', '2023-12-31')

### For specific analysis
analyzer.get_data('2023-01-01', '2023-12-31')
analyzer.visualize_ichimoku_cloud()
