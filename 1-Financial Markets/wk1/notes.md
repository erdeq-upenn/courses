Financial Markets
===
by Robert Shiller
# Week 1
## Learning Objectives    
* Discuss the relevance of this course in everyday life and the importance of ethical judgements in finance.
* Understand the main sources of risk a security is subject to, and the main methods used to evaluate risk of an entire portfolio.
* Describe why an investment may be considered high risk, and the sources of the so called 'disaster risk.'
* List the key events in the history of insurance, and how insurance differs between the state and national level in the U.S.
Identify the qualitative differences between the normal and fat tail distributions, and give examples of risk pooling, moral hazard and selection bias.
* Understand the principle of risk diversification.
Explain the Capital Asset Pricing Model (CAPM), and the role of short-selling within the model.
* Recall how to compute optimal risk-return portfolios.
Understand the concept of efficient frontier in portfolio management.    

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
    > The Dodd-Frank Act in the United States of 2010 requires the Federal Reserve to do annual stress tests for non-bank financial institutions it supervises.    
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

## Lesson 3

### Insurance
1.  Contractholder contract /pay insurance company a premium to protect them from certain risks    
risk pooling(assume independence) $\sigma=\sqrt{p(1-p)/n}$
meaning   
 **The stand deviation of something is the sqart root of $p(1-p)$.**
As n goes large, standard deviation approaches zero.    

    Not ideal when facing Moral hazard and selection bias.
    One famous is farmers buy corp  insurance which has been centuries.
2. insurance developed because of specific technical advances like the development of actuarial theory    
    **milestones in insurance history**   
    * 1600s life table for life insurance
    * In 1840, Morris Robinson who is the head of the Mutual Life of New York, a mutual insurance company, got the idea that what insurance company really needs is insurance salesman.
3. Insurance is a local phenomena
4. FDIC insured, **Federal Deposit, Insurance Corporation**    
    Prevent insurance failure    
    Interesting thing is the lifetime PV
    >The China Insurance Regulatory Commission has set up a state-owned non-profit called China Insurance Protection Fund that protects people against the failure of an insurance company.

5. AIG's failure in 2008
6. McCarran-Ferguson Act of 1945 delegated insurance regulation to the states *INCREASE*
7. There was a non-profit called **National Association of Insurance Commissioners, NAIC, which is not government** *DECREASE* complexity

### Health insurance
History
   * the first health insurance, apparently was in 1694.
   * The first U.S. health insurance company was Franklin health insurance company of Massachusetts in 1850
   * Health insurance with the **health maintenance organization Act** of 1973 which required employers with 25 or more employees to offer what's called an **HMO**
   * In 1986, the U.S. Congress passed another law called EMTALA law. **Emergency Medical Treatment and Active Labor Act** which required hospitals and ambulance services to provide care to anyone needing emergency treatment.
   * U.S. Pain Patient Protection and Affordable Care Act of 2010 called Obamacare

### Disasters

1. Earthquake    
Haitian not well insured

2. Terrorism    
So in 2002, the United States Congress passed the TRIA, the Terrorism Risk Insurance Act of 2002 which required nsurers to offer terrorism insurance for three years.

## Lesson 4

### diversification of ownership    
And that you have to manage your risk by diversifying across a number of different assets, not putting all your eggs in one basket.
1. serve quantified risks and returns and I calculate the optimum
    > **Risk-neutral measurement** (also called an equilibrium measure, or equivalent martingale measure) is a probability measure such that each share price is exactly equal to the discounted expectation of the share price under this measure.  

2. Care the mean and variance of the return on your whole portfolio.(**CAPM Harry Markowitz**)
    > you have to take account of each asset that you invest in. How does it contribute to your overall portfolio variance and portfolio expected return?

3. risk can be described by a variance matrix
4. **hedge funds** are investment companies that are **not** approved for the general retail market. So they're not allowed to advertise. They're not well-known, because they're not allowed to promote themselves, except through private conversations, and to invest in them you have to be an accredited investor, not a general investor. So they are allowed to do sophisticated and dangerous things.
    >**Accredited investors** include natural high net worth individuals (HNWI), banks, insurance companies, brokers and trusts. The high net worth club is $1 million in liquid financial assets.

5. Regulation before 2008-2009 crisis, was mostly micro-credential. That means they wanted to make sure that you as an investor weren't being ripped off by this stockbroker who was squirreling away your money. But we've now had new impetus for macro-credential regulation, and it's now regulation about how interconnected are you with other.
6. Nassim Taleb, who had a book called the **Black Swan**, that talked about rare, low-probably events as being sometimes really big.

### CAPM
1. The capital asset pricing model. It's a model of the optimal portfolio. It asserts that all investors will hold the optimal portfolio.
2. The CAMP implies the expected return on the ith asset determined from its beta.
    $\beta$ is the regression slope Coefficient where the return on the ith asset is regressed on the return of market
3. you're too small to diversify. So you need some company to help you diversify your portfolio. So, the idea has been going back many decades, that people need investment funds to manage their portfolio for them and the investment funds can diversify optimally for them. So before the 1940s, we had what were called **investment trusts. Later they became a different form called the mutual fund**.
4. **equity premium puzzle**. Jeremy Siegle at Wharton equity showed 6.6% stock return rather short term government bond is 2.7%. But why not all people invest in stock?
5. gold is a negative $\beta$ asset

### Short sales
1. Owns a negative quantity of stocks    
   Borrow the share and sell them.
   Rational assumption
2. leverage and being wiped out on risk free asset    
    $r=xr_1+(1-x)r_f$    
    $\Delta=|\frac{r-r_f}{r_1-r_f}|$    
    $var(r) = x^2var(r1)$    
    $\sigma = \Delta \sigma(r_1)$
3. two risk asset $r_1$ and $r_2$    
  $r=xr_1+(1-x)r_f$    
  $var(r)=x_1^2var(r_1)+x_2^2var(r_2)+x_1(1-x_1)cov(r_1,r_2)$   
  So a **positive** Cov is not good in lowering the risks

### Efficient portfolio Frontier    
**efficient portfolio frontier** which expresses the standard deviation of the portfolio in terms of r the expected return on the portfolio instead of $x_1$.
* Picture r vs. $\sigma$
* dominated area: University endowments

### Gorden Growth model
Gorden gave a formula for the present value of a growing quantity.
$PV = \frac{x}{r-g}$

#Week 2
##Learning Objectives    
* Understand the concept of limited liability and its connections with psychology, risk diversification and corporate finance.
Describe inflation indexed debt, and monetary innovation designed to tackle hyperinflation.
* Understand the basics of the real estate market, assumptions behind forecasting the stock market, and the basic framework to price a stock.
* Describe the key intuition and definitions behind the Efficient Market Hypothesis, and why it might only be half-truth.
Understand the basics of the real estate market, assumptions behind forecasting the stock market, and the basic framework to price a stock.
* Describe the key intuition and definitions behind the Efficient Market Hypothesis, and why it might only be half-truth.
To describe and provide examples of the wishful thinking bias and of cognitive dissonance.
* List the key features of Antisocial Personality Disorder and Borderline Personality Disorder.

### inventions take time
### Limited liability
1. **limited liability** credit New York State with inventing the full dimension of this idea in 1811.    
The idea is that investors, in order to be encouraged to invest in businesses, should have protection against liability for what the managers of the business do. They should have limited liability.
2. compare to lottery
3. The other thing about limited liability, is that it created the whole idea of holding a diversified portfolio.

### Inflation Indexed Debt
to define that in terms of a consumer price index.
1. eg. Japan rice bonds
2. The first indexed debt was invented here in the United States in 1780, and it occurred because of inflation.
    >As Plato said, necessity is the mother of invention.

### Unidad de Fomento
1. Now money has several functions. It's a store value and a unit of account and a means of transactions.

### Real estate risk management devices.


## Lesson 6
### forecasting
What would Efficient Market Theory say should be the forecast?
That would be the efficient markets hypothesis taking account of the fact that there's a growth. It's not a random walk, but it's a **random walk with growth**.    

The random walk theory: Karl Pearson in 1905
> a random walk is a process that changes in such a way that each change is independent of previous changes and totally unforecastable.

Burton Malkiel, random walk.

1. random walk: $x_t = t_{t-1}+\epsilon_t$

2. AR-I (first order autoregressive model): $x_t=100+\rho(x_{t-1}-100)+\epsilon_t$  
    * like he has a elastic band on him  
    * Mean reverting to (100) start point
3. AR-1 is closer to the start point

### Intuition of Efficiency
* Reuter's pigeons and the telegraph (1840 Samuel Morse)
* Market is Efficient
* Publicly available, relevant information will lead to correct pricing of freely traded securities in properly functioning markets
* Three forms of the market efficienty   
  >Weak form is that information in past prices can't help you to forecast, the semi-strong form of efficient markets is that all publicly information is already incorporated in the market prices, and the strong form is that all information including inside information held by the companies is already incorporated in the stock prices, prices because it leaks out.

### Price as PDV
1. Price of a stock should be the present discounted value of expected dividents.
2. Gorden Model: $P=E/(r-g)$ or P/E =$\frac{1}{r-g}$
3. P/E ratio: if someone is buyting a high P/E ratio stock, it means:  
  the market has decide either that this stock is very **good**, in terms of **risk, that's r**, or that the **growth rate** of the earnings of this company is going to be phenomenal.
4. Different industries & countries

### Doubting Efficiency market
1. half true
2. The stock market has a tendency to fall before a recession.

## Lesson 7
### Behavioral finance
1. Adam Smith *The wealth of nations*   
   > invisible hand, that the free market is the invisible hand that's directing the economy.

### Prospect Theory
Kahnemana and Tversky, in 1979   
  > so, the economic profession tends to used the idea that everyone has a utility function, which depends on the things that they consume and it represents their happiness.

1. One, they replaced the utility function with what they called a value function.
2. two, they replaced the probabilities with subjective probabilities determined by a weighting function in terms of the actual probabilities.  

Prospect Theory weighting function
* People worries about small gains/losses
* people gamble out of losses
