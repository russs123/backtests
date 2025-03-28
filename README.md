# Backtesting Trading Strategies

This repository contains Jupyter notebooks for backtesting various trading strategies. The goal is to analyze historical market data, evaluate different strategies, and refine them based on performance metrics.

## Features

- Implementation of multiple trading strategies  
- Performance evaluation using key metrics (Sharpe ratio, drawdown, etc.)  
- Data handling and preprocessing for backtesting  
- Visualization of backtest results  

## Setup and Installation

### Requirements

- Python 3.11 (recommended)
- pip (Python package installer)

### Installation Steps

1. Clone the repository (or download it directly):

   ```
   git clone https://github.com/yourusername/backtests.git
   cd backtests
   ```

2. Create and activate a virtual environment (recommended):

   ```
   # On macOS/Linux
   python -m venv venv
   source venv/bin/activate

   # On Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Running the Backtests

1. Start Jupyter Lab or Notebook:

   ```
   jupyter lab
   # or
   jupyter notebook
   ```

2. Navigate to the `strategies` directory and open any of the strategy notebooks:
   - `strategy_001_ADX.ipynb` - Average Directional Index strategy
   - `strategy_002_Pivot_Points.ipynb` - Pivot Points strategy
   - `strategy_003_Bollinger_Bands_Mean_Reversion.ipynb` - Bollinger Bands Mean Reversion
   - `strategy_004_Previous_Days_High_Low.ipynb` - Previous Day's High/Low strategy
   - `strategy_005_ORB.ipynb` - Opening Range Breakout strategy
   - `strategy_006_MA_Crossover.ipynb` - Moving Average Crossover strategy
   - `strategy_007_SAR.ipynb` - Parabolic SAR strategy

3. Run the cells in the notebook sequentially to execute the backtest.

4. Modify parameters in the notebooks to test different variations of the strategies.

## License

This project is licensed under the MIT License.

## Disclaimer

This repository is for educational and research purposes only. It does not constitute financial advice or recommendations.
