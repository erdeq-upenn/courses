Financial Markets
===
by Robert Shiller

## Lesson 1

1. Finance is to make things happen rather than just make money
2. There are many financial managers and works 500 k in the US.
3. Finance is a technology for good or evil
4. Andre Carnegie
>People who succeed in affairs are people with a natural, practical talent.

## Lesson 2

### VaR and Stress test
1. VaR meaning : variance or value at risk
>In finance, some people use VAR for 'value at risk' and this term is relatively new. It didn't appear until after the stock market crash of 1987. And so, it's a measure used by some finance people to quantify risk of of an investment or of a portfolio and it's quoted in units of dollars for a given probability and time horizon. 1% one year VaR at 10 M.

2. Stress test:
It's a method of assessing risks to firms or portfolios.
>Office of Federal Housing Enterprise Oversight actually was doing stress tests on Fannie Mae and Freddie Mac before the 2008 crisis.   
>The Dodd-Frank Act in the United States of 2010 requires the Federal Reserve to do annual stress tests for non-bank financial institutions it supervises.    
>The Dodd-Frank Wall Street Reform and Consumer Protection Act was passed into Federal law on July 21, 2010 as a response to the financial crisis of 2007 to 2008. This Act constitutes the most significant changes to U.S. financial regulation since the regulatory reform that followed the Great Depression.

3. The stress test is a test usually ordered by government to see how some firm will stand up to a financial crisis.
>what would happen if there were a severe recession, or what would happen if the dollar depreciated or appreciated, or what would happen if there's a short term liquidity crisis with suddenly ability to borrow money in the short term dries up.    
>The Dodd-Frank Act gave regulators, the Office of Financial Research subpoena power, so they can go in there and demand information from firms.


### S&P 500
1. It's an average of 500 stocks
> It's an average of 500 stocks. So if they were all independent of each other, the **Law of Large Numbers** would make the stock market as a whole almost constant.   
2. Noise of returns   
variance of Apple vs. SP 500
covariance with a regression line

3. **Fundamental concept $\beta$**   
The CAPM implies the that the expected return on the ith asset is determined on its beta
$\beta_i$ is the regression slop Coefficient when the return on its ith asset is regressed on the return of the markets

4. least square method for regression    
$y = mx+B$ in finance y called return of a stock, x rerutn of the market, slope m as $\beta$, B is called $alpha$.    $\beta$ is the measurement of systematic risk. 
5. Slope beta tells how much a particular stock co-moves with the market and thus as a measure of the stock systematic risk.

### Joe McNay Story

### Distribution and outliners

1. Normal distribution (bell curve)  $\sim \mathcal{N}$(mean,std)
2. Financial not follow $\sim \mathcal{N}$
3. In finance the Cauchy distribution is more charcteristic of financial returns. Most of time the distribution is lie normal distribution except the **fat tail**. instead of just trailing off to zero, continues out about zero

4. **Central Limit Theorem** average of a large number of iid shocks or random variables is approximately normally distributed but that central limit theorem assume that the underlying stock do not have fat tails.


5. The outliner of normal distribution says a probability of a drop greater than 20% is 3E-71
6. covariance 定义     
$cov(X,Y) = E [(X-E(X))(Y-E(Y))]$
where $E(X)$ is the expected value of X.
Using linear properties of expectation, we have:
$Cov(X,Y) = E(XY)-E(X)E(Y)$
$Cov(X,Y) =\sum_{i=1}^np_i(x_i-E(X))(y_i-E(Y))$


7. **Risk is determined by covariance.**
8. $\beta_i=\frac{Cov(r,r_{market})}{var(r_{market})}$
CAMP said that the market demands higher returns form higher beta stock. [risk averse]
