# Portfolio_Optimization

In this project I take the role as a financial advisors and advice my client on the structuring of his or her retirement portfolio. To structure the client’s portfolio, ETFs for stocks, bonds, alternative assets and US equity factors are useful tools due to their liquidity, low transactions costs and transparency. 


The modern portfolio management methodologies can be used as well to create and elaborate alternative portfolio allocations compared to the classic 60%/40% portfolio of stocks and bonds. 


The baseline 60/40 portfolio of 60% equity and 40% bonds is created from the eight ETFs that are the most liquid ones traded at the NYSE and represent the broadest segment of the respective global equity and US bond markets. For an approximation of the risk-free rate in the USA use the 13 week, or three month, US Treasury Bill (IRX) expressed in percent per annum, published daily by the US Federal Reserve. 


I implemented different portfolio allocations (Maximum Sharpe-ratio, Minimum volatility portfolio, etc.) and compared the performance including annualized returns, Sharpe ratio, and volatility as well as the rolling maximum drawdown with that of benchmark portfolio, which is simply a combination of 60% in the Wilshire 5000 Total Market Index (W5000) and 40% in three- month US Treasury Bills.


I assume monthly portfolio rebalancing. By applying Markowitz portfolio theory, we can observe that the weights evolve. I also performed the analysis during corona crisis period.


At last, I calculated the VaR and Expected Shortfall based on different methods and see if they predict reasonably how sensitive the portfolios are to exogeneous shocks like the Corona crisis with large drawdowns.
