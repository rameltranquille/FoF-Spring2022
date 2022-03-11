# CAPM: Introduction

- Portfolio Theory takes prices/expected returns as given 
  - Given these expected returns, all investors should allocate wealth between risk-free asset and tangency portfolio
*Q* What is the tangency portfolio? Whatdetermines asset prices/expected returns > CAPM

**CAPM**
- Predicts tangency portfolio 
- predicts relation between risk and expected return
- underlies most of real-world financial decision making

**THE MARKET PORTFOLIO**
- $p_i$ = price of one share of risky asset i
- n_i = number of shares outstanding for risky asset i 
- **Market Portfolio** = portfolio in which each risky asset i has the following weight: 

$$ 
w_{iM} = \frac{p*n}{\Sigma_i p_i * n_i} =  \frac{Market Capitalization of Security i}{Total Market Capitalization}
$$


## CAPM P1
- Adding up all the investments of all investors gives the market portfolio 
  - but, portfolio theory states that all investors hold the tangency portfolio, which is the same for all investors
- Hence, the *tangency portfolio  == market portfolio*

## Capital Market Line
- The market portfolio's capital allocation line is called the Capital Market Line
- The CML gives the risk-return combinations achieved by forming portfolios from the risk-free security and the market portfolio: 
$$ 
E(R_p) = R_f + \frac{E(R_M)-R_f}{\sigma_M} \sigma_p
$$

![frontierAndCML](frontierAndCML.png)

## CAPM P2 
- The required return on any security is proportional to the risk contribution of that security to the overall portfolio 
- CAPM = how to measure "risk contribution" precisely

## Security Market Line
CAPM predicts that expected excess return of a security is linear in its beta: 
$$
E[R_i] = R_f + \beta_i * E[R_M - R_f]
$$

This linear relation = **Security Market Line**

The beta measurees the security's systematic risk, its sensitivity to market movements: 
$$ 
\beta_i = \frac{Cov(R_i, R_M)}{Var(R_M)}
$$

![Security Market Line](picNotes/SecurityMarketLine.png)

## Risk Contribution of Security I
Recall that STD of the market portfolio: 
$$ 
\sigma_M = \sqrt{\sigma\sigma w_i w_j Cov(R_i,R_)}
$$
Risk contribution of security i depends on its covariance with the market portfolio 
$$ 
\frac{\partial\sigma_M}{\partial w_i} = \frac{1}{\sigma_M}\Sigma w_j Cov(R_i,R_j) = \frac{1}{\sigma_M}Cov(R_i, \bigsigma w_jR_j)
$$
Thus
$$
\frac{1}{\sigma_M} \frac{\partial \sigma_M}{\partial w_i} = \frac{Cov(R_i,R_M)}{\sigma^2_M} = \beta_i
$$

### Risk Premium
- Stock i's systematic or market risk is beta
- Investors are compensated for holding systematic risk in the form of higher returns
- The size of the compensation dpeends on the Equilibrium Risk Premium $E(R_M) - R_f$
- The equilibrium risk premium is inceasing in:
    - The variance of the market portfolio
    - the degree of risk aversion of average investor

    
## Systematic and Idiosyncratic Risk
- Beta measures security i's contribution to the total risk of a well-diversified portfolio, namely the market portfolio. 
  Hence, beta measures the systematic risk of the stock.
- Investors are compensated for holding systematic risk thus CAPM

![CAPM Equation & Risk](capmEquation.png)



## Estimating Beta by Linear Regression
- Get data on excess returns: 
$$
R^e_i(t) = R_i(t) - R_f \text{        } R^e_M(t) = R_M(t) - R_f
$$

Where R_f is the risk-free rate from t-1 to time t.
Estimate beta by running the regression 
$$ 
R^e_i(t) = \alpha + \beta R^e_m(t) + error_i(t)
$$


# Applications of the CAPM 
- Portfolio Choice
- Shows what a "fair" security returns
- Benchmark for security analysis 
  -Required return used in capital budgeting


## Application 1: Stock Selectoin 
- A benchmark for stock selection is to find assets that are cheap relative to CAPM 
- A security i's alpha is defined as 
$$
\alpha_i = E[R_i] - R_f - \beta[E[R_M]-R_f] \text{ where } \beta_i = \frac{cov[R_i, R_M]}{\sigma^2_M}
$$
- Some fund managers try to bu ypositive alpga stocks and short/sell negative alpha stocks
- CAPM predicts taht all alphas are zero

# Active and Passive Strategies
- An *active strategy* tries to beat the market by stock picking, by timing, or by other methods.
- But the CAPM implies that 
  - security analysis is not necessary
  - every investor should just buy a mix of the risk-free security and the market portfolio, a *passive strategy*
- Grossman-Stiglitz paradox: How can market be efficient if everyone uses a passive strategy?


## Application 2: Capital Budgeting and NPV
- Should firm undertake long-term risky project?
- Calculate Net Present Value, using CAPM to calculate required rate of return 
- Managers object: increase value of firm. Only understake projects with NPV>0
- Compare with decision based on Internal Rate of Return on project

# CAPM Summary 
- Prediction 1: Everyone should hold a mix of the market portfolio and the risk-free asset (meaning everyone should hold a portfolio 
  of stocks on the CML)
- Prediction 2: The expected return on an individual stock is a linear function of its beta (meaning stocks should be on the SML)
- Beta is given by 
  $$
  \beta_i = \frac{Cov(R_i,R_m)}{\sigma^2_m}
  $$
- A stock's beta can be estiamted using historical data by linear regression
