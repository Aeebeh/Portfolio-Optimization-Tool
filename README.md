**Portfolio Optimization Tool**

**Overview**
A Python-based portfolio optimization tool that implements Modern Portfolio Theory (MPT) to create efficient portfolios. The tool uses historical market data from Yahoo Finance to calculate optimal asset allocations based on the Sharpe ratio, with Monte Carlo simulations for risk analysis.

**Features**
- Data Collection: Automated fetching of historical price data using yfinance
- Portfolio Optimization: Implementation of MPT using scipy's optimization
- Risk Analysis: Value at Risk (VaR) calculations, Monte Carlo simulations, Portfolio metrics (returns, volatility, Sharpe ratio)
- Interactive Visualization: Efficient frontier plotting, Portfolio value distribution, Monte Carlo simulation paths

**Technologies Used**
- Python 3.8+
- NumPy & Pandas for data manipulation
- yfinance for market data
- scipy for optimization
- plotly for interactive visualizations

**Installation**

**Clone the repository**
- git clone https://github.com/Aeebeh/portfolio-optimization.git

**Navigate to project directory**
- cd portfolio-optimization

**Install required packages**
- pip install -r requirements.txt

**Usage**

**Run the portfolio optimizer**
- python src/portfolio_optimizer.py

**Example input:**
- === Portfolio Optimizer ===

- Enter ticker symbols separated by commas
- Example Tickers: AAPL, MSFT, GOOGL
- Years of historical data (1-10): 10
- Initial investment amount ($): 100000

**Sample Output**
- Optimal portfolio weights
- Expected annual return
- Annual risk
- Sharpe ratio
- Value at Risk metrics
- Monte Carlo simulation results
- Interactive visualizations

**Project Structure**
portfolio-optimization/
- LICENSE
- Portfolio Optimization/
- README.md
- requirements.txt

**Future Enhancements**
- Additional optimization objectives
- Real-time data integration
- Portfolio rebalancing suggestions
- Machine learning-based predictions
- Enhanced risk metrics

**Contributing**
- Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss the proposed change.

**License**
- MIT

**Author**
- Aeebeh

**Acknowledgments**
- Modern Portfolio Theory by Harry Markowitz
- Yahoo Finance API for market data access
