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

**Learning Objectives5-6-7**
* Understand the concept of limited liability and its connections with psychology, risk diversification and corporate finance.
* Describe inflation indexed debt, and monetary innovation designed to tackle hyperinflation.
* Understand the basics of the real estate market, assumptions behind forecasting the stock market, and the basic framework to price a stock.
* Describe the key intuition and definitions behind the Efficient Market Hypothesis, and why it might only be half-truth.
* Understand the basics of the real estate market, assumptions behind forecasting the stock market, and the basic framework to price a stock.
* Describe the key intuition and definitions behind the Efficient Market Hypothesis, and why it might only be half-truth.
* To describe and provide examples of the wishful thinking bias and of cognitive dissonance.
List the key features of Antisocial Personality Disorder and Borderline Personality Disorder.
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
* so, the economic profession tends to used the idea that everyone has a utility function, which depends on the things that they consume and it represents their happiness.  

1. One, they replaced the utility function with what they called a value function.
2. two, they replaced the probabilities with subjective probabilities determined by a weighting function in terms of the actual probabilities.  

Prospect Theory weighting function
* People worries about small gains/losses
* people gamble out of losses  

3. Financial theorists like to develop beautiful models, but a financial engineer wants a beautiful device that works in various conditions with real people.

### more detail
* people are, maybe that's a little bit rational, but it looks a little screwy what people do actually.  
* And what they did is a number of experiments that show about decisions under uncertainty
* people are maximizers through **utility**
* kick follows you as you move along the curve

### Logical fallacies

* People are overconfident: people **overestimate** the probability of the things that they identify with and want to see happen.
* Wishful thinking bias
  > Nassim Taleb in his book Fooled by Randomness, which is another great book to read

### Brain
1. safe and risky portfolios.
2. **attention anomalies**: There's a social basis for attention and that is that you tend to pay attention to the same things that other people pay attention.
3. anchoring
4. Representative Heuristic
5. culture


# Lesson 8
**Learning Objectives8-9**
* Describe the implications and institutions associated with the short term interest rate, and describe how to compute single and compound interest.
* Identify the difference between coupon and discount bonds, and calculate the present discounted value of discount bonds.
* Determine the origin, the meaning and the valuation of two debt securities: consols and annuities.
* Understand the meaning of forward rates and to describe how to calculate them
Define the meaning and how to calculate the market capitalization of a company.
* Explain the structure of corporations in the U.S. and the implications of owning shares in a company.
* Identify the differences between common and preferred stocks, and the concepts of dilution and dividends.
* Describe how and why companies repurchase their shares.
* Describe the basics of corporate governance.
* Further understand the pricing of stocks and the price-to-earnings ratio.


## 1982 saving account  
passbook (存单) account --> they just doesnt pay
## Federal funds rate
* shortest rate in US, is a overnight   
* Janet Yellen or Ben Bernanke makes it almost zero  
* EONIA, European Overnight Index Average. has negative ineretest rate
* US and EONIA have the same downward path since 2000
* Why are they lending to another bank at a negative rate? **It's costly to store cash**
* **basis points: one hundredth of a percentage point**
* Interest rates tend to be small positive numbers like 3% or 5% because of technical progress, time preferences and advantages to round aboutness."
## compound interest rates
compound n times a year at annualized rate r, balance after t years is
$V = V_0e^{rt} $
## discounted bonds
* Bonds typcially pay coupons.
  > a corporate bond or a government bond it would be on a piece of paper they would give you. This is like for hundreds of years. And around the exterior of the pieces of paper, were little coupons that you would clip every six months typically. And you would clip your coupons every six months and take them to a bank, and the bank would then give you the money.

* a discount bonds carries no coupons: **because you buy it for less than $100. You buy it at a discount**
* Term T, Yield to Maturity(YTM)  $P = \frac{1}{(1+r/n)^{Tn}}$
* present discounted value
* Coupon paying bonds wiht PDV
* $P_t=\frac{c}{r}(1-\frac{1}{(1+r)^T})+\frac{100}{(1+r)^T}$

## consol and Annuity
* a consol is one that pays a quantity
* consol PDV = $x/r$
* growing consol PDV = $x/(r-g)$
* **consol, growing consol,**
* So, there's market risk for our consol and for any debt instrument, long term debt instrument.
* The coupon is fixed at the time the bond is issued but the market price of the bond changes through time so if the British government issued a 3 pound consol for 100 pounds and that consol is selling for £200 today, the yield to maturity is down to 1.5% instead of 3%


##  Forward rates and expectation theory
* Forward rates are interest rates that can be taken in advance using the term structure.
## inflation and interest rate
* $r_{money} ~=r_{real}+i$
* So the nominal interest rate is quoted in currency. Dollars, Pounds, Renminbi, whatever.
* **index bonds**, which are bonds that pay coupons defined in real terms and a principle, or one or the other in real terms.

## leveraging
* If a company or an individual borrows money to buy assets, we say that person or company is leveraging.
* putting more money into the asset than you have.
* China is widely described as a highly leveraged country, it's gotten worse after the financial crisis.
* risk-taking and risk averse

# Lesson 9
## market capitalization by country
According to the Federal Reserve, as of 2014, these assets were worth $98 trillion US.

## Corporation
* corporation. So the word corporation comes from the Latin word corpus, meaning body. And what it is, is an organization that is
* A corporation is an artificial person.
* And traditionally it would be created by a royal charter, prescription, or act of legislature. More recently it's done according to procedures that are widely available.
* Goetzmann book, stock market in ancient Rome
* Modern Corporations lead by It's governed by a board of directors that is elected by the shareholders.
* **shareholder democracy**
* CEO is generally the top, for instance. So the person, the CEO is hired by the board, serves as an employee, and has to report to the board of directors(董事会).
## Shares and dividends
* split shares : to optimum target price of share price
* In the United States, by tradition, the target price per share is something like $30 a share.
* The company has a constitution, called the Corporate Charter, and the Corporate Charter defines how things are done
* A dividend is a distribution of money from the company's earnings to its shareholders
* So when a company pays a dividend, what happens to the share price  **it drops**
* **EX-DIVIDENT** dete
## common and preferred stocks
* Preferred stock has a specified dividend which does not grow through time.
* And like common stock, it doesn't have to be paid.
* the company is supposed to pay out a fixed dividend to the preferred stockholders, but it doesn't have to. But, it cannot pay a common stock dividend until it's paid up on its preferred stock dividends.
## Corporate charter
* equality of shareholders
* voting share and non-voting shares

## corporate raise money
* ways to raise money:
  - issue debt through broker
  - issue shares  (**dilution**)
  - retrain  earnings (saving money)

## Dilution
## Share repurchase
*  Reverse of dilution
*  tax break
* So there's a tax incentive for share repurchase rather than dividends
## price as PDV of expected dividends
* P/E ratio and P/D ratio
* the price of a share is the present discounted value of its expected future dividends.
* How many years to pay back the investment
* high growth companies should tend to have high PE, a low PE would be a low growth company.

## Why do companies pay dividends

#  Lesson 10
**Learning Objectives10-11**
* Understand the history and key concepts of mortgages.
* Describe the differences between DPPs and REITs.
* Explain the relationship between the 10 year treasury bond YTM and the 30 year mortgage rate.
* Describe the housing market before the bubble, and what led to the crash in 2007.
* Define CMOs and CDOs
* Describe microprudential and macroprudential regulation, and the concept of regulation.
* Define tunneling and give examples.
* Describe the differences between state and national regulation in the U.S.; describe the role of the SEC.
* Give examples of front running, indiser trading, and how brokerage failure can impact the stock market.
* Identify the role of regulatory bodies, and forwards and futures

## RESSION
inverted yield curves tend to be followed by recessions
> So we were just saying that government bond yields in Japan reached a negative number at the 10 year horizon. It's done that similarly in Germany and other European countries. So what does that mean?

* bond market is not a leading recession indicator
* The stock is the most famous indicator

## Real estate and history of mortgage lending
* To mortgage something, to mortgage your house means to offer it as collateral for a loan.
* So, the history of mortgage lending goes back at least to the Tang Dynasty in China.

## Commercial real estate vehicles
**real estate partnership**
In order to buy in to a real estate partnership you have to be an **accredited investor**, which is defined by the Securities and Exchange Commission
> as in terms of your wealth and your income.
> Now it used to be you had to have more than $1 million of investable wealth in your name, excluding your house. Or an income of $200,000 a year or more.

* Direct participation or flow through vehicles, they escape corporate profits tax.
* REIT, Real Estate Investment Trust.
* Restrictions in REITs

### Three REIT booms
1960 -> 1986 -> 1992

## Morgates
* in US, mortgages owned by households was recently **$13.2 trillion**.
* 48 M mortaged homes in US
* In 2012, 11 M is underwater after the crisis

* mortage and refinacne
* foreclose; bank terminate house mortgage before paied off
* That lead to the Roosevelt administration. They created the federal housing administration in 1934, that would ensure mortgages.
* he other thing that Roosevelt did in 1934, was to require **15 year loans**. Any FHA loans had to be 15 years until maturity or longer.
* Now it's typically 30 yrs

* 30 year mortgage rate and 10-y Treasury debts
* typical homeowner buy first home **starter home**, then final house
* Typical payoff mortgage in 10 years
* home mortgage is slightly risky and cost more than 10y bond
* PLAM (price level adjusted mortgage)
* ARM (adjustable rate mortgage)
* DRAMs (dual rates)
* A home equity loan is a loan on the value of your house that you might take on later as a way of getting money.


## PMI, CMO, and CDOs
**private mortgage insurance (PMI)**  
* the CMO is a bank issued mortgages
* A CMO is a collateralized mortgage obligation that is a pool of mortgages that is sold to investors like you
* CMOs- an ordinary of securitized mortgage would not have a AAA rating, because the homeowners might default.
* **CMOs are divided into tranches like that AAA is possible, whereas the reminder become toxic waste.**
* CDOs are more general not only mortgages but also auto loans and anything like That
* The AAA tranches shouldn't have been rated AAA, but they weren't as bad as all that either.
* **rating agencies**

## post crisis Regulation

* bad banks  
  people were really angry that the mortgage, the CMO and CDO people had repackaged mortgages and sold them to the general public. And that the banks who sold the mortgages didn't really care whether they were good or not.
* But a liar's loan was a mortgage issued to a person who did not show evidence of having a job or having a good record.
* In 2010, the Dodd-Frank Act (in response to the great recession during 2008-2010; rather the 1936 great depression )
  > Some of the main provisions found in the Dodd-Frank Act include:
    1 Banks are required to come up with plans for a quick shutdown if they approach bankruptcy or run out of money.
    2 Financial institutions must increase the amount of money they hold in reserve to account for potential future slumps.
    3 Every bank with more than $50 billion of assets must take an annual “stress test,” given by the Federal Reserve, which can help determine if the institution could survive a financial crisis.
    4 The Financial Stability Oversight Council (FSOC) identifies risks that affect the financial industry and keeps large banks in check.
    5 The Consumer Financial Protection Bureau (CFPB) protects consumers from the corrupt business practices of banks. This agency works with bank regulators to stop risky lending and other practices that could hurt American consumers. It also oversees credit and debit agencies as well as certain payday and consumer loans.
    6 The Office of Credit Ratings ensures that agencies provide reliable credit ratings to those they evaluate.
    7 A whistle-blowing provision in the law encourages anyone with information about violations to report it to the government for a financial reward.

* requirements of QRM (qualified resident mortgages)

## talk
* reserve requirements (准备金)
* **Excess reserves** are the reserves that banks hold beyond what they're required to hold by regulation.
* Why start to hold more excess reserves? Why  -> interest rate has been set by central banks to zero
* Any business in insurance or banking or finance more generally, has to worry about adverse selection, moral hazard, and they have to worry about their being manipulated or deceived.

## The bubble
* shortage of house after WWII
* Home price didnt fall after korean war
* overoptimistic mortgage lending make ppl to think going up forever
* building cost in fact is falling for hte last half century
* Book Irrational Exuberance Third Edition
* home price peaked in 2006
* **Real estate is the best investment for long-term holders who can buy and sell through the ups and downs of the market.** This is a wishful thinking bias
* 100 years price series of housing prices
* **SAAR** means seasonally adjusted annual rates
* SNPK Schiller series
* 10-yr hosing expectation and 30 yr MOrtgage rate
* ususallydate the first fault signs in 2007, but in 2005 economics showed house prices falling like a brick.
* Time mag cover
* China housing price: 1) invest outside is restricted 2) fear of corruption 3) son's marriage
* There is a slow down in China now

# Lession 11
## regulation overview
1. crises, misbehabior, and Regulation
  Phools subject to manipulations.
  ppl are constrained by the market eg. 9.99
  Zillow of pricing
2. Phishing Equilibrim
  microprudential(regulation to one ppl or company) and macroprudential(regulation to a whole economy)
  Players want a referee (hate but need )
3. regulation doesnt hinder entrepreneur
4. regulation and housing.
  * the Dodd-Frank Act wanted to get banks responsible for ability to pay and responsible for checking out borrowers.
  * mortgages that are not subject to the five percent retention rule. So, basically, mortgages follow the guidelines that were issued in 2014 by regulatory agencies in the United States.
  * your monthly debt payment cannot be more than 43 percent of your monthly income. **a rule of 43 % income**
  * China and the US when they put on short sale restrictions that prevented sellers who doubted the prices from selling.
  * Well, there is a tax subsidy right to homeownership in the United States. Homeownership encouraged. Better citizen.
  * moving is not a good thing if have home ownership
  * Tax makes a form of a deduction, low income ppl dont have the standard deduction.
  * after Dodd-Frank Act liar's load are prohibited
  * Chicago Mercantile Exchange to create futures markets for single family homes that is also a new home related Derivatives




## five levels of financial regulations

1. within-firm regulations
2. Trade group regulations
3. local government regulations
4. National Government regulation
5. international regulation

1> The board of directors is a uniform policy I think practically everywhere in the world.
  > So a board of directors is usually a part-time job, and they're out there involved in different things

Reputation prevents devious tricks.  
**Tunneling** is often used to describe tricks that people in companies use to steal money from the company.  
Common laws > civil laws
common laws are bettering in dealing with tunneling
So Johnson et al argue that tunneling is more frequent in civil law countries.  
* how to perform tunneling? sell assets of the company at a below market price to some crony of yours.
* sign a contract with your friend's company and pay way too much for the service. A contract 1000 pages so not one would read
* relative similar business and tells the friend to do the secret and let him share the buiness with your Company
* dilute shares: issue a lot of shares and then tunnel the money out some other way and the stockholders are hurt without even seeing it.
* company that's good after you bought extra shares and then announce- and then sell your shares before you announce bad news.
* **Duty of care: act as prudent or rational person.**
* avoid selfdealing transactions.
* Eg of France tuneling a ware house showed US and UK common law system is better dealing with tunneling


2> Trade group
* The first stock exchange in the United States was founded in 1792. "fairness, responsibility, and trust." not actually there. NYSE whitewashing it.
* William Duer, a former Assistant Secretary of the Treasury, had defaulted on his debt, causing a brief panic in the New York financial markets. That was the crash of 1792.
3> local regulations
* US state is local government
* We had two banks of the United States. One created in the 1790s called the Bank of the United States.renewed it in 1816 with what was called the Second Bank of the United States. Each lasts 20 years
* national banks regulated by the nation.
* 1934 SEC set up; security law from local to central government. but corporate law still local
* Blue sky laws: were laws regulating tricks and deception in financial markets.

3> national regulation
* China may not has too much regulations.
* SEC Louis Brandeis: "Sunshine is the best disinfectant."
* Edgar on SEC website: dispenses financial statements, and you can get financial statements that were reported by law to the SEC for all public corporation, and even for others to a certain extent.
* So, the idea is that you have to force companies, or financial institutions to put it out in a clear and consistent standardized way.
* A major thing that the SEC did, was to define the distinction between public and private securities.
* Public securities are securities that the SEC has approved for general public investment. And it had to go through an approval process through the SEC. (IPO)
* quarterly filings that appear on the Edgar database.
* IPO is the procedure of going public.
* **Hedge funds** are examples of companies that are private. You have to circumvent the SEC rulings as an investment company, if you want to do certain things like charge high commission, or high salaries for your leaders.
* **there are different kinds of hedge funds.**
  1. 3c1 refers to some line in the SEC regulations, is a kind of investment company that the SEC requires, takes **no more than < 99 investors, and all of the investors have to be accredited investors.** 2 decades ago, 1 M is a lot of money; to protect small investors
  2. 3c7. 500 investors, individual 5 M or institutions with 25 M.
* regulations that can go too far   
* prevent inside trading by the SEC. Regulation FD issued in 2000   
So Regulation FD requires that when a company tells any material fact to an analyst, it must be also immediately told to the general public.
SRO, there's self-regulatory organizations   
* **front running**: buy ahead of a big order
* So in 1973, the Securities and Exchange Commission officially recognized an organization called the **Financial Accounting Standards Board (FASB)** in Norwalk, Connecticut as the authoritative for accounting standards. Generally Accepted Accounting Principles or GAAP. GAAPs are decided by FASB.
* insurance of corporate account. Broker service dates back Goodbody went bankrupted.
* Merrill Lynch took over Goodbody.
* **FDIC, the Federal Deposit Insurance Corporation. The SIPC is Securities and Investor Protection Corporation.**
* FDIC 500,000 per account
* In 2008 crisis, banks conceals their liabilities.
* **rating services**: Moody's and S&P and Fitch and others.
* Bureau of Consumer Financial Protection, CFPB, usually, Consumer Financial Protection Bureau, cfpb.gov.
5> international regulations
* The Bank for International Settlements (**BIS**) was set up in 1930 which was a central bank for central bankers.

# Lesson 12
## Learning Objectives
1. Recall key vocabulary of options, the concepts of options contracts, and the reason options exist.
2. Understand the role of investment banks and underwriting.
3. Explain financial instruments used in commodities markets, and the future of such markets.
4. Identify the role of regulatory bodies, and forwards and futures.
5. Explain financial instruments used in commodities markets, and the future of such markets.
6. Describe the put-call parity relationship

## forwards and future Markets
### derivatives
* Forward contracts
  > A forward contract is a contract between two individuals, you might call them counter-parties, to deliver at a future date called the exercise date or maturity date.

* If I make a forward contract, both sides are locked into the contract, so they have no liquidity.
* **Forward exchange futures**, a forward exchange contract, FX forwards
e.g. forward exchange rate(Y/$)= $\frac{1+r_{Y}}{1+t_{dollar}}$  X spot_exchange_rate
* forward interest parity
* settlement_formula
### Future contract
* Now futures contracts rely on margin calls.
  > When an investor uses margin to buy ourselves securities. They are paid for using a combination of his or her own funds as well as money borrowed from a broker. The investor receives a margin call from a broker if the securities in the portfolio decrease in value past a certain point. After which the investor must either deposit more money into the account, or sell some of the assets.    

### Rice futures
* 1st future markets in Osaka, Dojima in 1670s
* **Chicago Board of Trade (CBOT)**
* It creates a meaningful price and it creates clarity for the future.

### buying selling and settlement
* there's Daily Settlement. Every day until expiration, a margin account is credited or debited with an amount equal to the change in the settle price times the contract amount.
* settle price
* S&P 500 index: There's one, the regular conventional one, which is $250 times the index. And there's the E-mini, which is $50 times the index.
  > A cash settlement is a settlement method used in certain futures and options contracts where, upon expiration or exercise, the seller of the financial instrument does not deliver the actual (physical) underlying asset but instead transfers the associated cash position.  

### Fairvalue of future contracts
* $P_f=P_s(1+r+s)$ s is the storage cost
### Oil futures
* CME bought NYMEX. on crude light sweet oil
* long-term oil futures
* 100 years comparison of oil and stock market
* OPEC (Organization of Petroleum Exporting Countries was established in 1960) limit production of oil and keep the price up
* Typically, oil is controlled by some government, non-democratic government.
* the first oil crisis was due to Arab countries retaliation for US support of Israel in the Yom-Kippur war.
* The second oil crisis, again, was caused by political situation in the Iranian Revolution, which led to war in the Persian Gulf and disrupted oil supplies
* US a Strategic Petroleum Reserve~ 60 supplies

### SPI and FFR futures
* stock price index futures (SPI), selltement is 250 * (index-future)
* The federal funds futures market is another example of a financial futures market but it's a market and the federal funds rate.
* Well the federal funds rate is the policy or tool of the target, of the Federal Reserve System.

## Lesson 13
### Option
* call and put options
* it is not obligation but rights; while forwards are obligation to buy or sell contract  
* the first options that are well documented come from Holland
* ticker: t's a four-letter ticker which is a clue that it's Nasdaq-listed, rather than New York Stock Exchange which normally lists stocks at three letters.
* bid ask spread
* Why option exist? economic efficiency
* a major source of economic inefficiency is cured by options market.
* **A Silver Lining Theory**. A theory that find that the people in their emotions don't look only at the bottom line, they look at different aspects of their portfolio.
* Ubiquity of options
* And some states are called recourse states, and some are called non-recourse states.
* **a recourse state**: if you buy a house and take out a mortgage to borrow, to get the house and then you stop paying. The mortgage lender can go after you, they can garnish your paycheck they can do legal proceedings to make you pay.
* exchange of options are recent: 1973, when the Chicago Board Options Exchange separated itself from the Chicago Board of Trade and started the first options exchange.
* call put parity

# WK6
## Learning Objectives
* Understand the causes and consequences of sovereign default or sovereign debt repudiation. A first look at public finance.
* Understand how and why a government can get involved in the corporate sector.
* Identify how local governments typically make use of the money generated by municipal bond issues.
* Understand why and how governments got involved in insurance which thus became part of public finance.
* Describe what nonprofit organizations are and illustrate some of their purposes and motives.
* Understand the role of investment banks and underwriting.
* Explain why rating agencies exist.
* Name and describe the key feature of the **Glass-Steagall Act.**
* Explain the biggest assets and liabilities in US households.
* Describe the prudent person rule and the role of financial planners and advisors.

### Investment bank and money managers
* So what do investment banks do? They traditionally do no accept deposits, they're not members of the Federal Reserve System. There's no FDIC insuring them, well they don't even have deposits.
* commercial banks take deposits and make loans.
* **IB under write securities**
* To **underwrite a security** means to manage the process of issuing new shares in companies or issuing debt for companies, or as I said, for other organizations.
* bulge-bracket: (are the big firms)
* Goldman Sachs, First Boston, Credit Suisse
### The underwriting process
* **what is underwriting of securities:** But the really important thing that investment banks do is put their reputation behind the issue.They check you out, due diligence.
* commercial bankers which make loans
*  flip of shares
* best efforts. And that's a case where the underwriter says, "I'll try to sell your shares at such a price, and if it's not sold then we'll just try again.
* pre-filing period --> underwriter forms a syndicate. It's an agreement among underwriters. --> cooling off period

  > A syndicate is a agreement between competitive IBs to underwrite a share    

* Then they file a registration statement with the Securities and Exchange period Commission. And then, there's a so-called, cooling off period,  Red herring
* An underwriting **syndicate** is a band of investment banks and broker dealers who come together to sell new offerings of equity or debt securities of a firm to investors when the issue is too large for a single firm to handle.
* It is compensated by the underwriting spread, which is the difference between the price paid to the issuer, and the price received from investors.

### IPO
* So an IPO is an initial public offering
* It's been documented that the price in the aftermarket tends to be higher than the offering price in an IPO.
* So, this all sounds like a manipulation. Well, it is sort of.
* Yet SEC allow this conspire of syndicate
* the average IPO jumped 16 percent on the first day in the aftermarket.
* impresario hypothesis
### GS and John Whitehead
* Goldman Sachs was maybe the most esteemed investment bank in the United States at that time, and very successful.
* Number one, making money always, and no exceptions.
* 1st principle of GS: make money
* absolute loyalty to the firm and to the partnership, and **personal anonymity** {use GS rather than your name}
* John Whitehead then became, long ago, became chairman of Goldman Sachs
* 1. client's money 1st, 2. our assets are people, capital, and reputation, 3 We stress creativity and imagination.

### Rating Agency
* what is RA? **It's an agency that publishes its information instead of keeping it secret for their favored clients**
* Poor's in 1916 merged with Standard Statistics to form Standard and Poor's long after Henry Varnum Poor.
* John L. Moody founded the first true rating agency called Moody's Investor Services in 1909.
* Moody and Standard and Pools.
* AAA, B, C, D s
* Originally, they would not accept money from the people they rated.
### The Glass-Steagall Act was one of the most famous acts of congress in 1933
* Created the FDIC: first insurance of commercial bank deposits in the United States.
* The really **important** thing that's most remembered about the Glass-Steagall act is it said that **you can't be both an investment bank and a commercial bank**
* JP Morgan and Morgan Stanley in US
* Other countries: universal banks
* **Gramm-Leach Act** of 1999 which signed by President Clinton, finally ended Glass Steagall. So they can now do both.  
* But now there are still people who want the Glass Steagall back. One of them is Paul Volcker
* So he wanted to put Glass-Stegall back with the Dodd Frank act and instead managed only to put in something called the Volcker rule. The Volcker rule is that commercial banks cannot invest can not do proprietary trading.

### Professional money managers
* commercial bank is like a money manager, because it's taking your money as a deposit and it's investing it in something, loans or mortgages.
* 101 T$ in 2015; 270k per household
* average household. The median household would be much lower than that
* Federal Reserve in table of B-101 computes totals of assets held.
* So about a quarter of that $100 trillion is real estate, people own homes.
* Municipal bonds are bonds issued by local governments; advantage that they're tax free.
### The Prudent Person
* In 1974, ERISA, the Employment Retirees Income Security Act, defined a prudent man.
* And required that investment managers behave like a prudent man, a prudent person. And that is, quoting the act, with the care, skill, prudence and diligence under the circumstances then prevailing that a prudent man acting in a like capacity and familiar with such matters would use in the conduct of an enterprise of a like character and with like aims.
* A financial advisor is anyone who advises others on the value of securities or the advisability of an investment or who publishes analysis. It excludes bankers, lawyers, reporters, and professors, broker dealers
* A **Broker Dealer** is a company that you would go to to buy and sell securities.
* National Securities Markets Improvement Act of 1996 required that all advisors managing more than 30 million each must register with the SEC.
* Those managing less than 25 million have to register with their state securities regulator.
* financial planner is not regulated

### Mutual Funds
* what is a mutual fund? a classic mutual fund as defined by the SEC under regulation
* MIT: Massachusetts Investment Trust
* 4:00 PM
* 1990s Exchange Traded Fund (ETF): it operates differently than a mutual fund. a kind of investment fund that is more liquid and tends to have lower management or expense ratios
* 1st SP 500 stock index: SPDR 1993
>  Mutual funds are called open-end funds because you can pull your money in and out. You're owning a share in a portfolio, and you can get it out at market value at 4:00 pm of every day.
> A closed-end fund is different from a mutual fund in that you buy a share in the fund on a stock exchange.

### Exchange, Brokers, dealers, and clearinghouse
* Broker: the definition of a broker is someone who acts on behalf of others
* Dealer: A dealer always acts for herself. In other words, as a principal in the transaction for which she makes a markup. [serves as a principle ]
* The difference between the two prices is called the **bid-ask spread**
* A broker-dealer is a, it could be an individual or a company. It's typically a company that potentially involves both brokers and dealers.
* A person can never be both a broker and a dealer on the same transaction. You have to choose one or the other. You can't both make a commission and then markup on the same trade.
* here's some example of bad behavior. **Churning**： Churning is an illegal and unethical practice that violates SEC rules and securities laws.
* One way to avoid this risk is to always maintain full control over your own trading account.

### Exchange
* The first stock exchange may have been in Antwerp or, I would say, Amsterdam, but New York Stock Exchange was the beginning in the United States
* NYSE, which was created in 1792
* In 1971, the Nasdaq market was created. It was a computerized market.
* so National Association of Securities Dealers Automated Quotation System, replacing the pink sheets
* Exchanges provide standards and codes of ethics.
* National Best Bid Best Offer Intermarket Trading System which was created by an act of Congress.

### Limit order Book
* electronic communications network called Island (old)

### HFT
### Payment for order flow
* brokerage account--> someone collecting orders (send your order to a millisecond trader)--> order to exchange (NYSE)
* in the year 2000 the Securities and Exchange Commissions investigated this practice of payment for order flow


### Government debt
* Repudiation of a debt occurs when the government announces, we're never going to pay, forget it, gone.
* odious debt
* debts in Purto Rico, Ukrian, and Greece
* In 2015, Greece actually defaulted on some of its debt. But it's not over yet.
* But I'm just wondering what if a government defaults on its loan. Who should get paid first or how should the government do it?

### Government involvement in corporations
* First of all, the government regulates business, and secondly the government can own shares in business.
* Fukushima was overwhelm by the tidal wave
* exposed who bears the cost now. Well, it turns out it's the Japanese government, because of limited liability, Japanese government cannot go after you
* debt that it can convert to preferred shares--> 88% owned by government
### Municipal Finance
* So the federal government is not gonna make laws about bankruptcy of state governments, but they do make laws about bankruptcies of municipal governments, cities.
* city borrow money for infrastructures and tax future people in the city
* prohibitions against deficit spending, against the state governments for borrowing money and spending it instead of raising taxes.
* The state and local governments have both a current account and a capital account.
* issue revenue bonds: alternative of tax increase
* **A balanced budget** amendment is a constitutional rule requiring that a state cannot spend more than its income.

### Government Social insurance
* government should use insurance principles
* Otto von Bismarck (俾斯麦) was not an economist. He was the head of the German government.
* similar to personal insurance
* unemployment insurance
* public education. Social security, OASDI stands for Old Age Survivors and Disability Insurance. And we have government health insurance, notably Obamacare
* It's insurance the employer must buy for the employees of the company against accidents at the workplace.

# Week 7
## Learning Objectives
* Illustrate the potential impact of future demographics on economics and finance.
* Explain a new and popular alternative to nonprofit organizations and cooperatives: benefit corporations.
* Describe the motives behind cooperatives and their differences with profit and nonprofit organizations.
* Describe what nonprofit organizations are and illustrate some of their purposes.
* Interpret some of the reasons for wealth, poverty, and inequality.
* Give examples of different critiques of finance and financial markets.
* Discover possible pathways for financial careers.

## Lesson 17
### Nonprofits
* traditional economic theory describes people as having a **utility function**, which is arguments include own consumption, and they care only about that.  
* How many are there? In 2013, there were 1.41 million nonprofit companies in the United States.
* So you wonder why would anyone work for nothing?  Older people work for joy
* The average over 13 countries, mostly advanced countries Was 7.4% of the workforce is non-profit.
* non-distribution constraint. They don't give back the dividend, the profits as dividend. They have to re-invest them.
* Tends to be higher in advanced countries.
* civil society:  Henslow supports Darwin
* nonprofits do not distribute profits as dividends. However, they have a history of distributing profits as bonuses to employees.
* Moreover you have to be incentivized to do good work.
* non-profit hospital, instead of IBD ask church
* compulsive hoarding: people who are illustrated in this show who just never throw anything away and fill their whole house up with junk.
* political correctness. Political correctness might not allow any kinds of inequality

### Cooperative (合作社)
* it is not a non profit; voting is different **one person**
* Rochdale Pioneers
* Everyone is a consumer, and every person is a potential member of cooperative. Regardless of race, religion, belief, occupation or nationality.
* For example, a grocery store can operate in either a for-profit form, or as a cooperative.

### Alternative Forms
* benefit corporation, This is a new corporate form, first created in the state of Maryland.
* **So what is a benefit corporation?** It's something half way between for-profit and nonprofit. It has profits, it makes profits, but it has a dual objective. It's for profits and for some social or environmental purpose that is stated in the company's charter.
* NPK--> Nitrogen, phosphorus, potassium
* finance is a technology, it thrives on invention. I think that we're making big steps forward now with a broader concept of finance than we had 20, 30 years ago. We recognize that human beings are part of a society, that human beings are psychological.
### Public vs private
* certain kinds of businesses are better run by private and some by the government.
* education, steel, etc.
* Phishing for Phools

## Lesson 18
### Critics of Modern Finance
* Adair Turner was head of the Financial Services Authority, FSA in the UK that used to be the main regulator.
* One of them is the rise in debt for advanced economies.
* So total debt of domestic credit as a percentage of GDP was a little over 40% in 1950, and now it's up to 160%.
* Rent seeking is a term coined by Anne Krueger, an economist, referring to just **grabbing what I can get rather than creating anything.**
* Apple began borrowing billions of dollars.--->  to avoid taxes
* the world seems to be increasingly run by takers, as she calls it, rather than makers.
### democratization of finance
* how finance has been increasingly democratized over the centuries and stands to gain if it's further democratized.
* democratization again, is that it **should benefit real people**.
* Risk management should reduce inequality.
* **crowdcube/crowdfunding**(众筹) It's a website where people with business ideas that need funding can take their ideas directly to the public and they can raise money online.
* allow crowdfunding to happen in the United States but limit it so that it can't drive anyone to bankruptcy. So what they said a company in the United States can raise money on a crowdfunding site but only one million dollars in a 12 month period.
* Financial literacy
* was popularized by Richard Thaler and Cass Sunstein in their book Nudge. And it was a new philosophy which they called libertarian paternalism toward government intervention in people's lives.
### Finance and War
* German and Iran and South Africa
* So a socialist theory allowed Vladimir Lenin, Lazaro Cardenas, Mao Tse-Tung, Mohammed Mossadegh, Gamal Abdul Nasser, Indira Gandhi and others to justify major confiscations of property and nullifications of financial arrangements.
* And notably after World War II, in Japan, there were the Big Four, Zaibatsu called Mitsubishi, Mitsui, Sumitomo and Yasuda that were blamed for some of the- they were powers behind the government in Japan and they were blamed for some of the things that, by the victors, that some of the things that happened in World War II.
* When the debt was raised by a government that was using it for ill purposes against the will of the people, that's odious debt.
### Finance and population growth
* the basic point was that population naturally increases, and according to a geometric ratio.
* Whereas subsistence for man increases only in an arithmetical ratio.
* Malthus: So this gives us the Dismal Law of Economics: that any improvement in the ability to give subsistence to man, will be met with by population increases.
### importance of financial theory
* There is a theory of the allocation of scarce resources and also of the pooling of information through markets.
* And similarly, adding psychological principles to mathematical finance is important.
* Gillian Tett called the "silo effect". It's unfortunate that we are separated from- we in economics, are separated from professional schools.
### Wealth and poverty
* And they find that the states with a lot of people have lost jobs to globalization or automation, tend to also be states where polarization in politics is the highest.
* So, most people don't buy financial advice because it's expensive, and they feel that they can't afford it.
* What you see is all there is" effect, that kahneman and tversky. People tend to assume that they have the evidence.
### Career in Finance
* So some young people are very idealistic, And might consider eschewing any connection with finance
* The FSB stands for the Financial Stability Board which is an international body that monitors and makes recommendations about the global financial system.
* And I think another really important thing for young people to do is to maintain human capital. That is, keep thinking about what skills you have will be important and needed by others under maybe different conditions. And finally, maintain humanity in a unforgiving business world.
