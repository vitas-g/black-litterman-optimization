# Project Overview
This project implements the Black-Litterman Model in Python to optimize a portfolio consisting of 10 major assets (AMZN, MSFT, COST, etc.). 
Unlike traditional Mean-Variance Optimization, this model allows for the integration of subjective investor views with market equilibrium, providing a more robust and stable asset allocation.
## Language: Python
## Repository Structure
├── data/
│   
├── market_data.csv      
│   ├── assets_data.csv      
│   └── mkt_caps.json        
├── black_litterman.ipynb    
└── README.md   

## How to Run
1)Ensure you have the datasets in the data/ folder.

2)Install the required Python libraries:
  ### pip install pandas numpy matplotlib
  
3)Open black_litterman.ipynb and execute the cells to see the optimization process and resulting asset allocations.
# Key Features
1)Equilibrium Returns Calculation: Derives the market-implied risk premium and neutral starting point.

2)Bayesian Inference: Updates the prior market beliefs using the Black-Litterman master equation.

3)Uncertainty Modeling: Incorporates 68% confidence intervals to represent the precision of investor views.

4)Optimal Allocation: Calculates the final weights for a Sharpe-optimized portfolio.
