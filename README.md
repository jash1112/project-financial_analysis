# Project--Financial_Analysis

---

## Description of the Project 

This project talks about 
1. As an Investment Manager our goal is to determine which company we should invest in.
2. Exploring correlations between different financial ratios to understand their relationships and impacts on each other. 
3. Analyzing trends over time using time series analysis, visualizing changes in revenues, profits, or other financial indicators.
4. Lastly, presenting findings and analyses using interactive graphs for clear and comprehensive representation.

The analysis we're going to do is .. 
1. Financial Ratios
2. Risk Analysis
3. Performace comparision between companies

The questions we're going to answer are: 
1. As an Investment Manager we intend to pick the best investment opportunity in either of these selected companies.
2. Based on the risk analysis which company is most unlikely to invest.
3. Is the market price of the share overvalued or undervalued?

## Members of the group

The members in this group are: 
1. Aayush Chhaperwal (Aayush-1995)
2. Jash Bikash (jash1112)
3. John Nguyen (JohnNguyenAnh)
4. Maher Alqarra (Maher808)

## Work breakdown strucutre

- Aayush Chhaperwal - Data transformation and Calculated Risk analysis Ratio.
- Jash Bikash - Data transformation and Calculated Liquidity Ratio.
- John Nguyen - Data transformation and Profitability Ratio.
- Maher Alqarra - Data transformation and Efficiency Ratio.

## Datasets used: 

1. www.investment.com
2. https://www.alphavantage.co/
3. www.finance.yahoo.com

## Code snippets
## Import Data from yfinance
data = yf.download("DOL.TO CTC.TO LNR.TO", start="2014-12-31", end="2022-12-31")
data.head()


# Analysis 

## Dollarama Analysis
•	Dataset provides insights into financial health, liquidity, profitability, and efficiency.
•	Strong relationships between 'Net Income to Stockholders' and stock price indicators sustained over observed periods.
•	The linear model predicts a negative relationship between time and the Operating Cash Flow Ratio.

## Canadian Tire Analysis
•	Dataset offers insights into financial health, liquidity, profitability, and efficiency.
•	Indicates mixed performance in debt coverage but sustained profitability and improving efficiency.
•	Linear model predicts a positive relationship between time and Operating Cash Flow Ratio for 'CTC'.
•	Correlation between 'Net Income to Stockholders' and stock price suggests a moderate positive relationship.

## Linamar Analysis
•	Indicates mixed debt coverage performance but sustained profits and inventory management improvements.
•	The linear model predicts a negative relationship between time and the Operating Cash Flow Ratio.
•	Unusual negative correlation between 'Net Income to Stockholders' and stock price.

## Limitations

•	We only took data from 2014 and 2022 for three companies in the consumer sector. 
•	We faced a challenge to acquire the API key as there were set limits on call per minute by Alphavantage open API. 
