# Recipes for FoF Problems
> Should store any interesting/useful recipes and equations for FOF
> Should link to recipes and equations for FOF



-------------------------------------
*Q* What is the correlation between the returns of Amazon and Tesla

| Scenario      | $R_A$ | $R_T$ | Probability |
|---------------|-------|-------|-------------|
| Recession     | 0%    | -10%  | 10%         |
| Normal        | 10%   | 10%   | 50%         |
| Economic boom | 20%   | 30%   | 40%         |


1. Compute each expected return: $E[R_A]=13%, E[R_T]=16%$
2. Compute each volatility: $\sigma_A = 6.4%, \sigma_T = 12.8%$
3. Compute covariance and then correlation [multipleAssets-Covariance](220215-1556-multipleassets-covariance)

-------------------------------------
*Q* $\sigma_{US}=15.4%$, $\sigma_{JP}=23.0%$, assuming the correlation between US and JP is $\rho=-1$. 
  What portfolio weight w (on US) gives a zero risk portfolio?

  1. Let $w$ be the weight on US, and $1-w$ the weight on JP
  2. The expected return of the portfolio is 
     $$
     E[R_p] = w * 0.136 + (1-w)*0.150
     $$
  3. Back to $\rho=27%$. The variance of the portfolio return is: 
     $$
     Var[R_p] = w^2 * (0.154)^2 + (1-w)*(0.230)^2+2*w*(1-w)*0.27*0.154*0.230
     $$
- So, what happens when we vary weight $w$
![Result](InvestmentOpportunitySet.png)











