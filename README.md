# ECONOMIC-VARIABLE-CORRELATION-AND-PRODUCTIVITY-MODEL


### INTRODUCTION
Understanding the intricate relationships between key economic variables is crucial for policymakers, investors, and economists. These variables often provide insights into the health and dynamics of an economy, enabling more informed decisions. In the context of Nigeria, a nation with a rapidly evolving economic landscape, analyzing the interactions between the money supply (M1), real exchange rate (black market), stock market performance, and inflation rate is particularly relevant.
This report aims to delve into these relationships, providing a comprehensive analysis that spans several decades. By examining historical data from 1960 to 2024, we can identify trends, correlations, and potential causative factors influencing Nigeria's economic performance. The ultimate goal is to construct a productivity model that incorporates these variables, offering a theoretical and practical framework for understanding and predicting economic behavior.

### OBJECTIVE:
Perform a financial analysis to examine the correlations between key economic variables.

### DATA COLLECTION
For this analysis, we have collected data on key economic variables for Nigeria spanning from 1960 to 2024. The data includes:
- M1 Money Supply
- Real Exchange Rate (Black Market)
- Stock Market Performance
- Inflation Rate
The dataset covers a sufficient time span to analyze trends and correlations, giving us insights into how these variables interact over time.


## CORRELATION ANALYSIS

### Visualization
To understand the relationships between the variables, we will plot them line charts and combo charts. Below are the charts for each pair of variables:
- Stock Price Over Time
- Exchange Rate
- Inflation Rate
- Money Supply (M1) vs. Inflation Rate
- Exchange Rate vs. Inflation Rate





![Screenshot (67)](https://github.com/user-attachments/assets/7a9bad71-7b96-45a8-b44f-ee7be7fdf5e3)



![Screenshot (68)](https://github.com/user-attachments/assets/479c151d-924f-45b3-9a85-35db57fdbe8d)


![Screenshot (69)](https://github.com/user-attachments/assets/2d7182df-5983-4dea-87d8-04529b342068)



### Correlation Analysis


![Screenshot (71)](https://github.com/user-attachments/assets/2b7d585d-223b-4789-8b4f-c9453394c6b3)



### Interpretations
A positive correlation coefficient (close to +1) indicates a strong positive relationship.
A negative correlation coefficient (close to -1) indicates a strong negative relationship.
A coefficient near 0 suggests weak or no linear correlation.

### Observations and implications

- Stock Price and Exchange Rate: There is a strong positive correlation (0.868816) between stock prices and the exchange rate. This suggests that as the exchange rate increases (potentially indicating a weaker Naira), stock prices also increase. This could be due to inflationary pressures or increased demand for equities as a hedge against currency depreciation.
  
- Stock Price and Inflation Rate: There is a moderate negative correlation (-0.338120) between stock prices and the inflation rate. This suggests that higher inflation rates tend to be associated with lower stock prices, possibly due to reduced purchasing power and higher costs impacting company earnings.
  
- Exchange Rate and Money Supply M1: There is a strong positive correlation (0.914805) between the exchange rate and the money supply M1. This indicates that an increase in money supply is associated with a higher exchange rate, possibly due to inflationary pressures from increased money supply.

- Inflation Rate and Exchange Rate: There is a strong positive correlation (0.737656) between the inflation rate and the exchange rate. This suggests that higher inflation rates are associated with higher exchange rates, indicating currency depreciation.
  
- Annual Change in Inflation and Inflation Rate: There is a moderate positive correlation (0.418071) between the annual change in inflation and the inflation rate, indicating that changes in inflation are somewhat aligned with the current inflation rate.







### THEORETICAL FRAMEWORK
To build a theoretical framework around the idea that increased money supply leads to currency depreciation, stock market appreciation, and increased inflation, several economic principles and theories were considered. 


1. Money Supply and Currency Depreciation
   
Theory:

- Quantity Theory of Money: According to the Quantity Theory of Money, M*V = P*Y (where M  is the money supply, V is the velocity of money, P is the price level, and Y is the real output). An increase in the money supply M, assuming velocity V and output Y remain constant, will lead to an increase in the price level P. This implies inflation.

- Currency Depreciation: An increase in domestic money supply can lead to currency depreciation if it outpaces foreign money supply increases. More money in circulation often reduces the currency's value relative to others because of higher inflation expectations. 

Mechanism:

- Inflation Expectations: As money supply increases, inflation expectations rise. Investors and traders anticipate higher inflation, leading to a decrease in the currency's value on the foreign exchange market.



2. Money Supply and Stock Market Appreciation

Theory:

- Liquidity Effect: According to the liquidity effect, an increase in money supply lowers interest rates, as more money becomes available for lending. Lower interest rates make borrowing cheaper, which can lead to increased investment in the stock market.
Wealth Effect: Increased money supply can also boost stock prices as investors perceive higher asset values due to increased liquidity, driving up stock prices.

Mechanism:

- Increased Investment: With more money in circulation and lower interest rates, investors may find stocks more attractive compared to other assets. Increased demand for stocks pushes prices up.
- Portfolio Rebalancing: As money supply increases, investors may rebalance their portfolios by increasing their allocation to equities, further driving up stock prices.


3. Money Supply and Inflation

Theory:

- Phillips Curve: The Phillips Curve suggests an inverse relationship between unemployment and inflation, but an increase in money supply can shift the curve upward, leading to higher inflation if the economy is near full employment.

- Expectations-Augmented Phillips Curve: This extended Phillips Curve incorporates the role of inflation expectations. As money supply increases, inflation expectations rise, which can lead to higher actual inflation.

Mechanism:

- Demand-Pull Inflation: With an increased money supply, aggregate demand may rise if the economy is operating near full capacity. This increased demand can push prices up, leading to higher inflation.

Implications

1. Currency Depreciation:
  Short-Term: The immediate effect of increased money supply is likely a depreciation of the currency due to higher inflation expectations.
  Long-Term: Persistent high inflation can erode currency value over time.

2. Stock Market Appreciation:
   Short-Term: Stock markets may react positively to an increase in money supply due to lower interest rates and increased liquidity.
   Long-Term: If inflation rises significantly, it could eventually hurt stock market performance if it leads to higher costs for companies and reduced consumer purchasing power.

3. Increased Inflation:
   Short-Term: Initial inflationary pressures may arise from increased money supply.
   Long-Term: Sustained high money supply can lead to persistent inflation if not countered by monetary policy adjustments.




### Graphical Representation
To visualize these relationships, graphs are used:

![Screenshot (70)](https://github.com/user-attachments/assets/022adc48-7898-42a1-9410-3e0bfa77bc24)


Money Supply vs. Inflation: Show how an increase in money supply can shift the inflation curve upward.

![Screenshot (73)](https://github.com/user-attachments/assets/8c5666f2-e570-4fa7-98a8-ab07a735eca4)

Money Supply vs. Stock Prices: Illustrate the positive correlation between increased money supply and stock prices.

![Screenshot (74)](https://github.com/user-attachments/assets/b8037ce3-c76c-4660-9516-87051de1cfae)


Money Supply vs. Exchange Rates: Demonstrate how increased money supply might lead to currency depreciation.


### Conclusion
The theoretical framework suggests that an increase in money supply will lead to currency depreciation, stock market appreciation, and increased inflation, given a constant level of productivity. This framework aligns with several established economic theories and provides a foundation for analyzing how changes in money supply influence various economic variables.


### PRODUCTIVITY MODEL

A potential productivity model looks like this:

Productivity=Output/Inputs

Since Output and Inputs are often hard to measure directly, you can use proxies based on your variables:
- Output Proxy: Stock Market Performance can be an indirect measure of economic output or economic health.
- Inputs Proxy: Money Supply, Inflation Rate, and Exchange Rate can affect economic inputs.
  
A possible model might be:

Productivity= Stock Market Performance/ (Money Supply) * (1 + Inflation Rate) * (Exchange Rate)

Here’s why:
- Stock Market Performance: Reflects overall economic health and business conditions.
- Money Supply: Higher money supply might indicate more economic activity but can also lead to inflation.
- Inflation Rate: Higher inflation erodes purchasing power, affecting productivity negatively.
- Exchange Rate: A higher exchange rate can indicate a depreciation of the domestic currency, which might impact productivity.


![Screenshot (72)](https://github.com/user-attachments/assets/9017d307-1bd4-4492-a900-804d25496f05)

The time span from 2000 to 2024 was used as there was no Exchange rate data available from 1960 to 1999.

### Analyze Productivity Trends

- Graph Productivity:

  
![Picture1](https://github.com/user-attachments/assets/c7aa2263-4a53-4fab-8c88-cdbc08a52a23)

This graph shows a flat productivity

Assess Trends:
Flat Productivity: Implies that increases in money supply do not significantly impact output.

Interpret Results
Flat Productivity: Suggests stability in economic output relative to inputs. The combined effect of money supply, exchange rate, and inflation might be balanced.


### PRODUCTIVITY BASELINE
Productivity Baseline is a reference level of productivity that can be compared to current productivity to determine if it is increasing or decreasing. The baseline can be defined as a scenario where money supply is constant, and changes in productivity are ideally attributed to changes in other factors, such as exchange rate and inflation.
Formula for Productivity Baseline

The baseline formula should reflect the idea that productivity changes due to changes in exchange rate and inflation while keeping money supply constant. The actual formula for calculating baseline productivity, considering a flat money supply, can be expressed as follows:

Baseline Productivity  = (Base Money Supply) * (1 + Baseline Inflation Rate) * Baseline Exchange Rate/ Stock Market Performance

Where:
- Base Money Supply is the constant money supply value.
- Inflation Rate is the baseline or reference inflation rate.
- Exchange Rate is the baseline or reference exchange rate.

Let’s use the year 2020 as the baseline year for illustration:

- Base Money Supply: 12,728,323.53
- Baseline Inflation Rate: 13.25% or 0.1325 (expressed as a decimal)
- Baseline Exchange Rate: 357.93
- Stock Market Performance: 27,114.84


1. Calculate Adjusted Money Supply:
Adjust for inflation to get the effective money supply value:

Adjusted Money Supply=Base Money Supply × (1+Baseline Inflation Rate)

Adjusted Money Supply= 12,728,323.53 x (1+0.1325) 
                    = 12,728,323.53 × 1.1325 ≈ 14,414,826.39

                                        
2. Calculate Baseline Productivity
Baseline Productivity =14,414,826.39 × 357.93/27,114.84 

Baseline Productivity=5,159,498,812.53/27,114.84
                                      ≈190,283.21


### Summary
The money supply (M1), stock market performance, inflation rate, and exchange rate for the year 2020 was used to calculate the productivity baseline. If the money supply is flat but productivity increases, you would expect an increase in the exchange rate and a decrease in inflation under typical economic conditions.
This approach provides a way to measure how economic conditions (exchange rates and inflation) adjust in relation to productivity while holding money supply constant.
To compare the Actual Productivity with the Baseline Productivity and analyze the trends,it can be done this way;

1. Calculate the Ratio of Actual Productivity to Baseline Productivity
Given:
- Actual Productivity for 2020: 2.006058338
- Baseline Productivity for 2020: 190,283.21
formula;
Ratio = Actual Productivity/Baseline Productivity
           = 2.006058338/190,283.21
           ≈0.00001054

 2. Analyze Trends and Implications
- Increasing Productivity:
If the ratio of actual productivity to baseline productivity is increasing over time, this would suggest improvements in economic efficiency or favorable changes in exchange rate and inflation.
- Decreasing Productivity:
If the ratio is decreasing, it could indicate that productivity is declining relative to the baseline due to adverse changes in exchange rate or inflation.


### Flat Productivity:
If the ratio is relatively constant, it means that changes in exchange rate and inflation are balancing each other out, and productivity remains stable relative to the baseline.
2020 Analysis Based on Given Data:

   - Ratio Calculation:
    Ratio for 2020 = 0.00001054
    
Since this ratio is extremely small, it suggests that the actual productivity is very low compared to the baseline. This could imply:

1. Significant Productivity Gap: The actual productivity for 2020 is much lower than the baseline productivity. This might be due to adverse economic conditions or inefficiencies that are impacting productivity.

2. Economic Efficiency Issues: The low ratio indicates that current economic conditions (money supply, inflation, and exchange rate) are likely not favorable compared to the baseline period.

Implications:
- If Productivity is Increasing: 
Even though the current productivity is low relative to the baseline, if this trend shows improvement over time, it might suggest that the economy is on a path to recovery or improvement in productivity.
- If Productivity is Decreasing:
  A continuing decrease in the ratio would highlight worsening economic conditions or inefficiencies.
- If Productivity is Flat:
  If the ratio remains constant over time, it suggests that the changes in economic variables are balanced, but the overall productivity level remains low compared to the baseline.
Actionable Insight: Review and investigate the factors contributing to the low productivity ratio. Consider assessing the underlying economic variables such as money supply, inflation, and exchange rates to understand their impact on productivity.


### CURRENCY DEVALUATION
To analyze the real currency devaluation of the Nigerian Naira (NGN) using a reference currency with flat M1 growth and stable productivity, considering key economic indicators such as exchange rates, inflation rates, and money supply.

- Determine the Nominal Exchange Rate Change: To calculate the percentage change in the exchange rate.
Given the exchange rates for the local currency (NGN) for two consecutive years:

Initial exchange rate (2023-12-31): 636.2844615 NGN/USD

Final exchange rate (2024-12-31): 1371.818108 NGN/USD

Nominal Exchange Rate Change= (1371.818108−636.2844615/636.2844615) ×100 
                            ≈115.6%

- Calculate the Inflation Differential: Calculate the inflation differential between the local currency and the reference currency.
Given the inflation rates for the local currency (NGN) for two consecutive years:

Inflation rate for Nigeria (2023-12-31 to 2024-12-31): 27.64%

Inflation rate for Nigeria (2022-12-31 to 2023-12-31): 21.87%

Assuming the reference currency (USD) has a flat M1 growth and stable productivity with minimal inflation (let's assume 2% for the reference currency):

Inflation Differential = Inflation Rate of Local Currency − Inflation Rate of Reference Currency 

For 2023-2024:

Inflation Differential = 27.64% − 2% = 25.64%

- Calculate Real Currency Devaluation: Adjust the nominal exchange rate change by the inflation differential.
Real Currency Devaluation = Nominal Exchange Rate Change − Inflation Differential Real Currency Devaluation = 115.6% − 25.64% = 89.96%


### INTERPRETATIONS
The real currency devaluation for the Nigerian Naira (NGN) from 2023 to 2024, after adjusting for the inflation differential with a reference currency assumed to have a flat M1 growth and stable productivity, is approximately 89.96%. This significant devaluation indicates a substantial loss in the purchasing power of the Naira relative to the reference currency (USD), after accounting for inflation.


### IMPLICATIONS
- Economic Impact: A high real devaluation can have several effects, including increased cost of imports, potential improvements in export competitiveness, and higher inflationary pressures domestically.
- Policy Considerations: Policymakers might need to address the underlying causes of the devaluation, such as inflation, exchange rate policies, and economic stability measures to mitigate the adverse effects on the economy.
- Investor Sentiment: Such a large devaluation could impact investor confidence, leading to capital flight or reduced foreign direct investment.



### RECOMMENDATIONS
 
Based on the analysis of the historical data and the correlations identified between the economic variables, the following recommendations are proposed:

1. Monetary Policy Adjustment:
   - Control Money Supply Growth: To avoid excessive inflation and currency depreciation, the Central Bank of Nigeria (CBN) should implement measures to control the growth of the money supply. This can be achieved through targeted monetary policies such as adjusting interest rates and reserve requirements for banks.
   - Enhance Transparency in Exchange Rate Management: By ensuring a more transparent and market-driven exchange rate mechanism, the CBN can reduce the volatility in the black-market exchange rate, thereby stabilizing investor confidence and economic predictability.
     
2. Fiscal Policy and Inflation Control:
   - Monitor and Manage Inflation: The government should adopt fiscal policies that address the root causes of inflation, such as improving agricultural productivity to stabilize food prices and investing in infrastructure to reduce production costs.
   - Strengthen Anti-Inflation Measures: Implementing anti-inflationary policies, including subsidy reforms and enhancing competition in the market, can help in managing inflation effectively.
     
3. Stock Market Development:
   - Encourage Foreign Investment: Policies that attract foreign investment into the stock market can boost liquidity and stability. This includes creating a favorable regulatory environment and ensuring political and economic stability.
   - Support Domestic Investors: Promoting financial literacy and providing incentives for domestic investors can enhance participation in the stock market, driving growth and stability.
     
4. Economic Diversification:
   - Reduce Dependency on Oil: Diversifying the economy away from oil dependence by promoting sectors like agriculture, manufacturing, and technology can create a more resilient economic structure.
   - Promote Export Growth: Encouraging the growth of non-oil exports can strengthen the exchange rate and reduce the impact of global oil price fluctuations on the economy.
     
5. Productivity Enhancement:
   - Invest in Human Capital: Enhancing education and training programs to improve the skill set of the workforce can boost productivity and economic growth.
   - Improve Infrastructure: Investing in infrastructure, such as transportation and energy, can reduce production costs and increase efficiency across various sectors.


### CONCLUSION
This report has provided a detailed analysis of the relationships between Nigeria’s M1 money supply, real exchange rate (black market), stock market performance, and inflation rate over the period from 1960 to 2024. The correlation analysis revealed significant insights into how these variables interact and influence each other.

The theoretical framework proposed suggests that an increased money supply leads to currency depreciation, stock market appreciation, and increased inflation, given a baseline productivity level. By developing a productivity model, we examined whether productivity in Nigeria is flat, decreasing, or increasing over time.
Based on the findings, several recommendations have been made to improve monetary and fiscal policies, develop the stock market, diversify the economy, and enhance productivity. Implementing these recommendations can help stabilize the economy, reduce inflation and currency volatility, and foster sustainable economic growth.

In conclusion, understanding and managing the interplay between these key economic variables is crucial for Nigeria’s economic stability and growth. Policymakers should leverage these insights to craft informed policies that address the underlying challenges and capitalize on opportunities for long-term economic development.






