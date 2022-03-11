# Topic 2: Return Measures
* [Reading-Ch5-5.2](220218-1920-reading-ch5-52)
* [Reading-Ch5.4](220218-1922-reading-ch54)

## Holding Period Return (HPR)
The holding period return is the most basic measure of performance
	- The *period* can be 1 minute to 10 years
* At time 0 -> Pay $P_0$ to buy the asset at time 0. Assume zero bid/ask spread for simplicity
 
* At time 1 -> Receive a cash payment (coupon or dividen) $C_1$ 
	    -> Resell the asset for $P_1$

### Compute HPR 

$$ 
R_1 = \frac{C_1 + P_1}{P_0}-1
$$

*Q* Buying a stock and selling it a week later for $36
- $ HPR = 36/35 - 1 = 0.0286 = 2.86% $
*Q* You buy a bond with a 5 dollar semiannual coupon for 101 dollar. You sell it 6 months later for 99 dollars after recieving one coupon
- $ HPR = \frac{5+99}{101} - 1 = 0.0297 = 2.97% $

### Capital Gains and Dviidend Yields
$$
HPR = Capital Gain + Dividend Yield
$$

$$
Capital Gain = \frac{P_1}{P_0} - 1
$$
- Positive if the price goes up; negative if the price goes down

$$
Dividend Yield = \frac{C_1}{P_0} 
$$
- Usually positive unless you are paying to keep position open

### Annualized HPR
**Annualized/Annual Holding Period Return** $ann.HPR$ is
$$
ann.HPR = (\frac{V(T)}{V(0)})^2 - 1
$$
- $V(0)$ - time you buy an investment
- Reinvesting all intermediate cash-flows until date $T$
- $V(T)$ - At time $T$ you sell the investment *and the proceeds from the re-invested cash-flows for a total price of $V(T)

### Multiple Period Returns
If you make a sequence of returns and you do not reinvest your returns, then your total return is approximately the simple average return:

$$
R_0 + R_1 + R_2,..., + R_T
$$

$$
\frac{R_0 + R_1 + R_2,..., + R_T}{T}
$$

#### Arithmetic vs Geometric Average
- Geometric is when you reinvest the proceeds at the same rate as that of your initial investment such that
$$ 
((1+R_1)(1+R_2)...(1+R_T))^{1/T} - 1
$$


## APR vs EAR
- Borrowing rates are quoted as **Annual Percentage Rate (APR)** 
  	+ if you pay N times per year (ie 4) then APR/N is your period (quarterly rate)
- APR may not represent the true cost of borrowing, thus we use the **Effective Annual Rate (EAR)** which is
$$
1 + EAR = (1 + \frac{APR}{N})^N
$$

*Q* Which loan is cheapest?
1. 10%, compounded semi-annually
2. 10%, compounded quarterly
3. 10%, compounded daily


## Real Returns & Inflation
**Inflation** 
- Instead of considering a particular good (apples) we consider a broad basket of goods, including 
  durable goods, energy prices, and so on 
- The inflation rate $\pi$ is the percentage change in the price index
The **real return** is 
$$
1 = R^{\text{real}} = \frac{1 + r^{\$}}{1 + \pi}
$$

Treasury issues bonds indexed to inflation, which guarantees a real return
*Note:* Useful to infer market participants' inflation expectations




