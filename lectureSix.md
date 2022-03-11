# Portfolio Choice P2: Risk-Return Tradeoff

## Risk-Return Tradeoff


[Indifference Curves](220216-2130-indifference curves)


## Indifference Curves in Finance

### Example of Utility Function

--------------------------
## Adding a Riskless Security
Risk-Free Return = $R_f$ such as T-bills


### Properties of the Risk-Free Asset
The risk-free return has 3 key properties 
- $E[R_f] = R_f$
- $Var[R_F] = \sigma_f^2 = 0$
- $Cov(R_f,R_i) = 0$ for any asset i.
These are the key values to computing volatility of a portfolio


### +1 Risky Asset
Let w be the fraction of wealth invested in the risky asset (the rest is invested in the risk-free asset) then,
**Expected portfolio return:**
$$
E[R_p] = w * E[R_i] + (1-w)R_f = R_f + w * E[R_i - R_f]
$$

- **Risk premium** = $E[R_i - R_f]$
- **Excess Return** = $[R_i - R_f]$
 
**Variance of Portfolio Return**
$$
\sigma_p^2 = w^2 \sigma_i^2
$$
- Standard Deviation is: 
$$
\sigma_p = |w| * \sigma_i
$$




### Investment Opportunity Set with a Risk-Free and a Risky Asset
- Consider various portfolios $p$ (which are long in the risky asset and long or short in the risk-free asset)
- What is the risk-return relationship? -> combine the expected return and volatility formulas
$$
E[R_p] = R_f + \frac{E(R_i - R_f)}{\sigma_i}\sigma_p
$$

$$
Sharpe Ratio of I = \frac{E(R_i - R_f)}{\sigma_i}
$$
$$
E[R_p] = R_f + SR * \sigma_p
$$

### The Capital Allocation Line

**Sharpe Ratio (SR)** = return premium per unit of risk
![Capital Allocation Line](capitalAllocationLine.png)

$R_f = 3\%, E(R_US) = 12\%, \sigma = 20\%$
*Q* How can I get a 15.6% expected return by investing in US stocks and the risk free asset? (above)
*Q* What is the standard deviation of this portfolio? (above)

## Optimal Portfolio Choice

* Within the feasible portfolios -> upper portion of the investment opportunity set, the *efficient frontier*
* Pick the Most desirable -> highest indifference curve



