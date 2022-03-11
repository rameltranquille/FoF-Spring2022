# Topic 3: Time Value of Money

## Compounding and Future Value
**Initial Value** -> Compounding T periods -> **Future Value**
$$
FV = \${1+R}^T
$$


## Discounting and Present Value 
**Present Value** <- Discount T periods <- **Initial Value**

**ExampleA**
*Q* To recieve 1000 dollars in year, how much should I invest today at a rate of 5%?
$$
PV = \frac{1000}{1+0.5} = 952.38
$$

**ExampleB**
*Q* To recieve 1000 dollars in two year, how much should I invest today at a rate of 5%?
$$
PV = \frac{1000}{(1+0.5)^2} = 907.03
$$

## Going Back and Forth
$$
FV = PV * (1 + R)^T
$$
*Q* If you invested 1000 dollars and recieved 1109 dollars after 3 years, what was the interest rate?
*Q* If you invested 1000 dollars at 6% and recieved $2133, for how long did you invest?

### PV, FV, R, and T are tied together
- $ FV = PV * (1 + R)^T $
- $ PV = \frac{FV}{(1+R)^T}$
- $ R = (\frac{FV}{1+R})^{1/T} - 1$
- $ T = \frac{log(FV/PV)}{(log(1+R)}$

**No arbitrade pricing principl** -> $Price = PV$

## Pricing Securities
Simplest security: single payment $F$ (face value) at maturity $T$
- Pricing: $Prive = PV = F/(1+R)^T$
	+ $R$ is the **yield (aka yield to maturity)**
- Lower $R$ <-> Higher price
- Higher $T$ -> Higher price (pull to par)
	+ [Handout H1](file:handouts/H0.pdf)

### Pricing Securities with multiple payments
- Timeline???
- Present value of cash flows $C(0), C(1),..., C(T)$
$$
PV = C(0) + C(1)\frac{1}{1+R}+...+C(T)\frac{1}{(1+R)^2}
$$
Superposition of zero coupon bonds!


## Net Present Value (NPV)
**Def**: The present value of cash flows minus the present value of costs, including the initial (setup) cost
$$
NPV = PV(revenues) - PV(costs)
$$

It is efficient to invest in a project when the NPV is positive.


## Annuities (Handout H2)
[Handouts H2](file:handouts/H2.pdf)

**Def**: Pays a *fixed cash flow C* for T periods
$$
PV = \frac{C}{1+R} + \frac{C}{(1+R)^2} +...+ \frac{C}{(1+R)^T} = C[1 - \frac{1-\frac{1}{(1+R)^T}}{R}]
$$
With C$[1 - \frac{1-\frac{1}{(1+R)^T}}{R}]$ being the PV Factor



### Perpetuities
**Def**: Annuity with infinite $T$
- Pays a fixed cash flow, $C$, every period forever
**Example**: consol bond in UK, or many 100-year bonds aare "almost perpetuities"
**Pricing:** PV = C / R

*Note*: For annuities/perpetuities: Careful about the timing! 
- First csah flow paid one period from now

**Perpetuity Example**: Suppose that you are a donor and want to endow a student fellowship that pays
10,000 every year, forever. The interest rate is 5% per year. How much money should you give the university?


## Types of Bonds



| Name of Bond          | 1 | ..t.. | T   | ... | Price at time 0                                       |
|-----------------------|---|-------|-----|-----|-------------------------------------------------------|
| Discount, Zero-Coupon | 0 | 0     | F   |     | $P = \frac{F}{(1+r)^T}$                               |
| Perpetuity/consol     | C | C     | C   | C.. | $P = \frac{C}{r}$                                     |
| Annuity, mortgage     | C | C     | C   |     | $P = C/r * (1 - \frac{1}{(1+r)^T})$                   |
| Regular Coupon-Paying | C | C     | C+F |     | $P = C/r * (1 - \frac{1}{(1+r)^T})+\frac{F}{(1+r)^T}$ |
|                       |   |       |     |     |                                                       |

**Relationship between interest rates and asset prices**
*Q* For perpetuities???
*Q* For other bonds???
*Q* For stocks???



