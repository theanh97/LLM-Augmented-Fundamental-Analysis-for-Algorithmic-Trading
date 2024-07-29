# LLM-Augmented Fundamental Analysis for Algorithmic Trading

## Overview

This project leverages **Large Language Models (LLMs)** to enhance fundamental analysis for algorithmic trading. It combines traditional financial analysis techniques with cutting-edge AI to evaluate and select stocks from the S&P 500.

## Key Features

- **LLM-powered Financial Analysis**: Utilizes the Groq API to evaluate income statements of top S&P 500 stocks.
- **Automated Stock Selection**: Scores and selects stocks based on LLM-generated financial performance metrics.
- **Backtesting Framework**: Validates the trading strategy using historical data.
- **Data Integration**: Uses yfinance to fetch real-time and historical stock data.
- **Performance Visualization**: Generates plots of portfolio returns and key performance metrics.

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- Groq API
- yfinance

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Set up your Groq API key in the script.
2. Run the main script:

```bash
python main.py
```

## Project Structure

- `main.py`: Primary script containing all functions and execution logic.
- `top_20_stocks.csv`: CSV file storing the top 20 S&P 500 stocks by market cap.
- `all_scores.csv`: CSV file containing evaluation scores for each stock.
- `pivoted_stock_scores.csv`: Pivoted view of stock scores for easier analysis.
- `backtest_results.csv`: Results from the backtesting process.
- `portfolio_returns.png`: Visualization of portfolio performance.

## Results

The project generates:
- Stock evaluation scores
- Backtesting results
- Performance metrics (Total Return, Annual Return, Sharpe Ratio)
- Visualizations of portfolio returns

## Future Improvements

- Implement more sophisticated stock selection criteria
- Enhance the LLM prompts for more nuanced financial analysis
- Add more comprehensive risk management features
- Expand to include more data sources and financial metrics
