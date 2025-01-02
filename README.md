This project involves creating an optimal stock portfolio from the NASDAQ-100 using data from 2022 and 2023. 
The goal is to maximize returns while accounting for diminishing returns by applying integer programming and non-linear optimization techniques. 
The project is implemented using tools like Gurobi, TensorFlow, and NumPy.

Objectives:
1. Build a stock portfolio with maximal returns.
2. Limit the number of stocks to address diminishing returns and promote diversification.
3. Use historical stock data for insights and model constraints.
4. Optimize the portfolio using a mix of integer programming (via Gurobi) and advanced machine learning techniques (via TensorFlow).


Features:
1. Historical stock data analysis (returns, risks, correlations).
2. Customizable constraints for budget, diversification, and cardinality.
3. Scalable and efficient optimization using Gurobi.
4. Non-linear optimization using TensorFlow for advanced diminishing returns modeling.
5. Visualization and backtesting for portfolio evaluation.


Technologies Used:
Python: For data processing, analysis, and optimization.
Gurobi: Integer programming solver for portfolio optimization.
TensorFlow: Non-linear optimization for diminishing returns modeling.
NumPy & Pandas: Data manipulation and analysis.
Matplotlib & Seaborn: Visualization tools


Workflow:
1. Data Collection and Preprocessing: Fetch historical stock prices for NASDAQ-100 stocks (2022-2023). Clean and preprocess data to calculate returns, risks, and other metrics.
2. Data Analysis: Analyze trends in returns and risks. Define key constraints for the optimization problem.
3. Model Formulation: Define the mathematical model for portfolio optimization: Decision variables [Binary (stock selection), Continuous (stock weights)], objective function [maximize portfolio returns],
   constraints [budget, cardinality, diversification, risk control, and diminishing returns]
5. Optimization with Gurobi: Implement the integer programming model using Gurobi. Solve for the optimal stock portfolio.
6. Advanced Optimization with TensorFlow: Use TensorFlow for non-linear optimization to better account for diminishing returns. Integrate machine learning techniques for dynamic risk-return tradeoff adjustments.
7. Evaluation and Visualization: Backtest the portfolio against NASDAQ-100 performance. Visualize portfolio allocation and risk-return tradeoffs.
8. Documentation: Summarize findings, methodology, and results in a final report.
