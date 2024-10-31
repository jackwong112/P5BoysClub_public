# P5BoysClub_public
Business cycle and asset allocation --The performance of gold, stock, exchange rate and bond against GDP growth rate and inflation rate of Hong Kong in the past 10 years

Introduction

Acting as a sell-side fund management firm, we would like to investigate the 10-year financial data (from 1 January 2014 to 31 December 2023) of 4 asset classes for analysis: gold, Hang Seng Index (stock), USD to HKD (exchange rate) and Hong Kong Government 10-year bond yield (bond) against the Gross Domestic Product (GDP) growth rate (annual %) and inflation rate measured by Consumer Price Index (CPI) (annual %) in Hong Kong and understand the importance of managing a portfolio better in consideration of profit maximization and portfolio diversification.

Business Cycle

Bodie, Kane and Marcus (1999) described a business cycle as below:

The economy recurrently experiences periods of expansion and contraction, although the length and depth of those cycles can be irregular. This recurring pattern of recession and recovery is called the business cycle…A peak is the transition from the end of an expansion to the start of a contraction. A trough occurs at the bottom of a recession just as the economy enters a recovery. (p.511)



A)	Hong Kong GDP growth rate (annual %): 

https://www.censtatd.gov.hk/en/web_table.html?id=310-31001#

B)	Hong Kong inflation rate measured by CPI (annual %):

https://www.censtatd.gov.hk/en/web_table.html?id=510-60001#

 
Observation:


The above graph shows how GDP growth rate and inflation rate moved in the period from 1 January 2014 to 31 December 2023 in Hong Kong. 

We identify a short and complete business cycle from June 2019 to January 2022. 

Both GDP growth rate and inflation rate move together with a time lag. 



From the above graph, a business cycle can be divided into 4 cycle phases as described below:

Phase 1: GDP growth starting from a recession in June 2019, a trough in May 2020
Phase 2: getting an expansion from May 2020 to December 2020
Phase 3: transiting to a superheated economy from December 2020 to a peak in March 2021
Phase 4: falling from the peak to January 2022 during a stagflation

 
Asset Classes

Diversification is a key principle of effective investing. By spreading investments across various asset classes and strategies, we can enhance our portfolio's resilience to market fluctuations, aiming for a more favorable balance between risk and returns over the long term.
The table below shows how the performance of each asset class can differ at various phases of the business cycle.


 
1.	Gold spot price:

https://www.investing.com/currencies/xau-usd-historical-data (XAU_USD Historical Data.csv)
 

Theory:

The GDP indicates the economic health of a region, while gold is a non-confidence vote in the economy. Hence, there should be a negative correlation between GDP growth and the price of gold.

Inflation is when prices rise, so does the price of gold.

Observation:

	GDP 	Inflation 	Expected Gold Price	Actual Gold Price
Phase 1	falling	falling 	increasing/decreasing	increasing 
Phase 2	rising	falling	decreasing	increasing
Phase 3	rising	rising	decreasing/increasing	decreasing
Phase 4	falling	rising	increasing	mild increasing

 

 
2.	Hang Seng Index (HSI): 

https://www.investing.com/indices/hang-sen-40-historical-data (Hang Seng Historical Data.csv)


Theory: 

The stock market rises and falls, so does sentiment in the economy. As sentiment changes, so do people's spending, which ultimately drives GDP growth; however, the stock market can have both negative and positive effects on GDP.

High inflation has historically correlated with lower returns on equities. 

Observation:

	GDP 	Inflation 	Expected HSI	Actual HSI
Phase 1	falling	falling 	decreasing/increasing	decreasing 
Phase 2	rising	falling	increasing	increasing
Phase 3	rising	rising	increasing/decreasing	increasing
Phase 4	falling	rising	decreasing	decreasing

 


 

3.	USD to HKD:

https://www.investing.com/currencies/usd-hkd-historical-data (USD_HKD Historical Data.csv)


Theory: 

There are several ways in which GDP affects currency exchange rates. Firstly, there is a direct effect. If a country is doing badly economically, international investors do not want to put their money here and demand for the currency falls, taking the exchange rate down. However, Hong Kong dollar is pegged with United States dollar and was originally set at a rate of 7.8 per United States dollar, although it has been allowed to trade between 7.75 and 7.85 per United States dollar since 2005.

In general, inflation tends to devalue a currency since inflation can be equated with a decrease in a currency's buying power. As a result, countries experiencing high inflation tend to also see their currencies weaken relative to other currencies.

Observation:

	GDP 	Inflation 	Expected USD/HKD	Actual USD/HKD
Phase 1	falling	falling 	decreasing/increasing	mild decreasing 
Phase 2	rising	falling	increasing	staying stable
Phase 3	rising	rising	increasing/decreasing	staying stable
Phase 4	falling	rising	decreasing	mild increasing



 
4.	Hong Kong Government 10-year bond yield:

https://www.investing.com/rates-bonds/hong-kong-10-year-bond-yield-historical-data (Hong Kong 10-Year Bond Yield Historical Data.csv)


Theory: 

Economic growth is typically bullish for corporations as it leads to increased revenues and profits for companies, making it easier for them to borrow money and service debt, which leads to a reduced risk of default and, in turn, lower yields.

One of the factors that affect a bond's price is inflation. A rise in the inflation rate will tend to cause bond prices to drop. Inflation behaves similarly to bond yields, moving in the opposite direction from bond prices.

Observation:

	GDP 	Inflation 	Expected bond yield	Actual bond yield
Phase 1	falling	falling 	increasing/decreasing	mild decreasing 
Phase 2	rising	falling	decreasing	staying stable
Phase 3	rising	rising	decreasing/increasing	mild increasing
Phase 4	falling	rising	increasing	increasing



 
Correlations by heatmap diagrams


 

From the above diagram, we see that the overall correlations over 10-year period among 
GDP growth rate, Inflation rate by CPI, Gold spot price, Hang Seng Index, USD/HKD and Hong Kong 10-year government bond yield. 

The correlations seem to be relatively small because some strongly positive correlations will be offset by some strongly negative correlations during business cycles over the time.

Now, we look into the correlations during the 4 cycle phases from June 2019 to January 2022.
 
 
 

 
From the heatmap diagrams, we discover that there are more deep colors, either strongly positive or strongly negative.

For example, GDP growth rate becomes strongly positive correlated (+0.85) with inflation rate by CPI in phase 1. The correlation then becomes moderately negative (-0.46) in phase 2. No correlation (0) is in phase 3 and moderately negative (-0.38) is in phase 4.
 
Conclusion





 

In summary, during the observation period of business cycle from June 2019 to January 2022, we find that gold price kept going up almost throughout the 4 phases, especially performed better in phases 1 and 2. We believe that gold price is affected by global economic factors such as war affairs and quantitative easing in USA and other countries. It seems not significantly to be reflected by the sole regional market factor.

HSI performed better in phases 2 and 3, it behaved as expected because of the economy booming. HSI well reflects the economy of Hong Kong and inflation erodes the stock returns. 

Stable USD/HKD and higher bond yield in phase 4 became attractive, also as expected. It implies that holding cash and bonds are not a bad choice in bad economy moment since USD/HKD remains stable almost for all the time and Hong Kong government bonds have a relatively good credit rating. 

Although the asset classes performed little differently from the best performing asset class  as stated in the economic theory, we hope through periodically review and adjustment in the diversification strategy in response to changes in market conditions, individual goals and risk tolerance, the risk associated with specific asset class can help to reduce the likelihood of concentrated losses. 

In terms of coming future, we predict Hong Kong is experiencing a gradually expansion (phase 2) and recommend more weights in gold and HSI investments in the portfolio since Russia-Ukraine war has not yet terminated while Hong Kong business environment improves with government easing policy. 


Afterwords

This project has a good extensibility to refine in the following areas to give a better overall picture:
— adopt a longer time period for data from 30 years to 50 years
— include a benchmark interest rate, for example, 1-month Hong Kong Interbank Offered Rate (HIBOR), the Prime rate or the Base rate of Hong Kong Monetary Authority (Interest rate is a significant factor to measure the health of economy in addition to GDP growth rate and inflation rate)
— include Centa-City Leading Index (CCL) to measure the secondary private residential property prices in Hong Kong (Housing is one of the commodities)
— include some value stocks (e.g. 0002.HK) and growth stocks (e.g. 0700.HK). Normally, as economy grows, growth stocks grow more rapidly while value stocks grow less
— include some alternative investments such as USD to BTC
— compare with other regional markets such as Singapore
— implement machine learning tools for prediction


Disclaimer: Investors should note that investment involves risks (including the possibility of loss of the capital invested), prices of securities / fund units may go up as well as down and past performance information presented is not indicative of future performance. 


References:
Zvi Bodie, Alex Kane, Alan J. Marcus, “Investments”, McGraw-Hill International Editions, 1999.

Table 310-31001 : Gross Domestic Product (GDP), implicit price deflator of GDP and per capita GDP. (2024, August 16). Census and Statistics Department. https://www.censtatd.gov.hk/en/web_table.html?id=310-31001#

Table 510-60001 : Consumer Price Indices (October 2019 – September 2020 = 100). (2024, September 20). Census and Statistics Department. https://www.censtatd.gov.hk/en/web_table.html?id=510-60001#

XAU/USD - Gold Spot US Dollar. (2024, October 14). investing.com.
https://www.investing.com/currencies/xau-usd-historical-data

Hang Seng (HSI) . (2024, October 14). investing.com.
https://www.investing.com/indices/hang-sen-40-historical-data

USD/HKD - US Dollar Hong Kong Dollar. (2024, October 14). investing.com.
https://www.investing.com/currencies/usd-hkd-historical-data

Hong Kong 10-Year Bond Yield. (2024, October 14). investing.com.
https://www.investing.com/rates-bonds/hong-kong-10-year-bond-yield-historical-data

