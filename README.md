# Portfolio-Optimization

The notebook focuses on portfolio optimization using Python. Here's a summary of what is done and how:

Data Loading & Preprocessing: Stock price data is loaded from a CSV file and reformatted using pandas, with prices pivoted by date and symbol.
Returns Calculation: Daily returns for each stock are computed to analyze historical performance.
Risk & Return Metrics: The Sharpe Ratio is introduced as a key metric for optimizing portfolios by balancing risk and return.
Optimization Using SciPy: The scipy.optimize library is used to find the optimal portfolio weights that maximize the Sharpe Ratio.
Visualization & Interpretation: Matplotlib is used to plot efficient frontiers and portfolio performance for better decision-making.
