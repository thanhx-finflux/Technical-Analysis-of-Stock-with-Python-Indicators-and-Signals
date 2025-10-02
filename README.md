# Technical-Analysis-of-Stock-with-Python-Indicators-and-Signals
Python-based technical analysis for stocks (AMZN, GOOG, NFLX, META, GLD) using historical data from yfinance. It calculates key indicators such as RSI, MACD, Bollinger Bands, and visualizes trading signals.


## Overview

Technical analysis helps identify trading opportunities by studying price patterns and market trends. This project uses a ta library to compute indicators and plot them for stocks fetched via yfinance.

## Key Indicators:
- RSI
- Bollinger Band
- MACD
- Moving Average
- Stochastic Oscillator

```python

tickers = ['AMZN', 'GOOG', 'NFLX', 'META', 'GLD']
start = dt.datetime(2024, 1, 1)
end = dt.datetime(2025, 10, 1)
data = yf.download(tickers, start=start, end=end, auto_adjust=True)['Close']
```
## Results
- Analyzes momentum, trend, and volatility for each stock.
- Sample signals: Buy when RSI < 30 and MACD crossover positive, sell when RSI > 70 and MACD crossover negative, and ADX over 25.
- Interpretation: GLD shows an overbought condition in bull runs.

# Visulizations

<img width="916" height="518" alt="1" src="https://github.com/user-attachments/assets/7fffffdf-22ac-4823-ad58-5f2e61f831c5" />


<img width="850" height="545" alt="3" src="https://github.com/user-attachments/assets/b0391d40-3a08-4dcc-8637-466a864afffb" />

<img width="1231" height="1275" alt="image" src="https://github.com/user-attachments/assets/8c1985a4-78da-468c-ad9f-bcb58058065c" />

<img width="627" height="545" alt="image" src="https://github.com/user-attachments/assets/614d9f46-b37b-4bb1-bdeb-f1af74b74b56" />

<img width="1160" height="622" alt="image" src="https://github.com/user-attachments/assets/8b0daf7d-9be4-4da7-92c7-4fa3730f7214" />

<img width="1160" height="622" alt="image" src="https://github.com/user-attachments/assets/4b5999cd-cafe-4257-bf8b-9c917ccb8973" />

<img width="1160" height="853" alt="Image" src="https://github.com/user-attachments/assets/98f29963-4844-4f17-97e6-ebbf0597125d" />

<img width="1160" height="853" alt="Image" src="https://github.com/user-attachments/assets/378f55ba-9a50-4c97-90c4-b91a07a8218e" />

<img width="1207" height="699" alt="Image" src="https://github.com/user-attachments/assets/bf5ae75c-ca76-4ba7-a367-f0e7d0eb538e" />

<img width="1216" height="622" alt="Image" src="https://github.com/user-attachments/assets/8e93203d-189a-4c8f-b80c-916d2c597cd8" />

## Contact
Thanh Xuyen, Nguyen
- LinkedIn: [xuyen-thanh-nguyen-0518](https://www.linkedin.com/in/xuyen-thanh-nguyen-0518/)
- Email: thanhxuyen.nguyen@outlook.com
