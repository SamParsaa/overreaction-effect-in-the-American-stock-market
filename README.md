# overreaction-effect-in-the-American-stock-market
Examining the overreaction effect in the American stock market with a focus on the US Oil and Gas and IT market. 

 
#Abstract:  
Experimental psychologists believe that individuals do not behave rationally when confronted with dramatic information and violate Bayes' rule (Kahneman & Tversky, 1977). They use the term "overreaction" to describe this error and believe that people can overreact to events (Mullainathan & Thaler, 2000; Gennaioli & Shleifer, 2018). 
This research examines the overreaction effect in two significant markets, namely the IT market and the oil and gas market, and studies these markets separately. 
Based on the empirical findings from my Master’s research, which revealed unique overreaction behaviors in the IT market compared to the Oil and Gas market, this proposal introduces a gametheoretic model to examine the strategic interactions among investors (Chauhan, 2025). While my previous findings attributed these differences to "intrinsic characteristics", this PhD research will model these characteristics as specific payoffs and signals in a strategic game. 
Introduction 
Cognitive bias plays a great role in investor decision-making in financial markets. Value-based investment theory maintains that people attach more importance to immediate returns compared to long-term profitability, leading them to make non-optimal choices (Barberis et al., 1998).  
Current theories usually evaluate these non-optimal choices in isolation; this study suggests that these choices are strategic responses to the observed behaviors of other market players and investigates how cognitive biases effect investor behavior and fuel market fluctuations. It specifically looks into whether investors should examine their own behavior more closely to prevent cognitive errors and whether the overreaction hypothesis still has a significant impact on stock valuation.  
  
#Research Questions 
This study examines the connection between stock prices, returns, and investor decision-making. It seeks to evaluate how price and return swings affect investor behavior over the short and long terms.  
 
The following are the main research questions: 
 
•	Is there a correlation between historical return patterns and future stock returns, and if so, which way? 
 
•	Does investor overreaction have a major impact on the U.S. stock market? 
 
•	Does the January effect in stock returns stem from overreaction? 
  
 
 
#Literature Review 
De Bondt and Thaler (1985) showed that investors often overreact to market news. Using CRSP monthly return data, they found that stocks with poor past performance ("losers") tend to outperform strong ones ("winners"), especially in January. This effect can last up to five years. They later confirmed these results and ruled out other causes like firm size or risk. 
Their work also showed that small-cap stocks with past losses often perform better in January, possibly due to tax-related trading. More recent studies support this idea. Bordalo et al. (2022) linked overreaction to overly optimistic earnings forecasts. Alvarez and Carvalho (2020) found long-term reversals in global indices. Bahcecioglu et al. (2023) studied overnight price jumps and showed how shocks affect returns. Piccoli and Chowdhury (2017) found that low-beta loser stocks overreact more after negative events. 
Together, these studies show that overreaction is a real and lasting part of market behavior, affecting both short-term volatility and long-term returns. 

#Data and Time Horizon 
Daily stock return data will be collected and aggregated into monthly, quarterly, semi-annual, and annual intervals to test the efficacy of the overreaction hypothesis across different time frames. The time window with the strongest statistical alignment will be selected for final analysis. 
 
#Preliminary Findings 
In each period, ten prominent stocks from these markets were examined. Short-term periods were defined as two-year formation periods and one-year test periods, while long-term periods included five-year formation periods and three-year test periods. The purpose of this division was to examine the behavioral differences of investors in different time periods. 
The results showed that the overreaction effect is observable in some periods and markets. In the IT market, loser stocks in the short-term with daily data often turn into winner stocks in the next period. This finding indicates the presence of excessive investor reaction to short-term fluctuations, which can be attributed to their irrational and emotional behavior. On the other hand, in the oil and gas market, no significant overreaction effect was observed, and price behavior was more stable and predictable. This difference could be related to the intrinsic characteristics of each market and the type of investors in them. 
The PhD Justification: This divergence suggests that different markets have different "strategic games" at play, which proposed game-theoretic model will solve. 
 
#Theoretical Framework 
The research is based on Bayes' rule and its adaptation in behavioral finance. Every new event modifies our beliefs and affects how we make decisions, according to Bayes' theorem. In the financial markets, recent events frequently influence investor behavior more than historical data, which could result in overreaction, especially when stock prices drop and investors are lured to apparent deals. 
 
#Market Efficiency Assumption 
The analysis assumes a semi-strong form efficient market, where all publicly available information is reflected in current prices. The study begins at a time with a common event affecting all stocks in the portfolio. It then tests whether the residual portfolio return, based on a single-period CAPM model, significantly deviates from zero. Statistically significant deviations would suggest market inefficiency. 
The study focuses on stocks that have experienced significant capital gains or losses over a fiveyear period. Instead of relying on firm-specific variables such as earnings, portfolios are constructed based on past excess returns, classifying stocks into “winner” and “loser” groups. This approach allows for a more direct assessment of market efficiency. 
 
#The theoretical foundation is expressed through the following expectation: 
 
E(𝑅𝑗,𝑡 − 𝐸𝑚(𝑅𝑗,𝑡|𝐹𝑡𝑚−1)|𝐹𝑡 −1) = E(𝑢𝑗,𝑡|𝐹𝑡 −1) = 0 
 
#Portfolio Construction 
Rather than relying on firm-specific variables such as earnings, the study constructs "winner" and "loser" portfolios based on past excess returns over a five-year horizon. The cumulative abnormal return (CAR) for each stock is calculated as: 
 𝑁
𝐶𝑈𝑗 = ∑ 𝑢𝑗,𝑡 
𝑡=1
 
Stocks in the top 10% of 𝐶𝑈 are classified as winners, while those in the bottom 10% are losers. 
The average cumulative abnormal return (ACAR) for each group is then computed: 
𝑁 
𝐴𝐶𝐴𝑅  = ∑ 𝑢¯,𝑡 /𝑁 
𝑛=1
 
#Hypothesis Testing 
If overreaction exists, we expect: 
𝐴𝐶𝐴𝑅𝑤,𝑡 < 0       و      𝐴𝐶𝐴𝑅𝑙,𝑡 > 0 
Thus: 
𝐴𝐶𝐴𝑅𝑙,𝑡 − 𝐴𝐶𝐴𝑅𝑤,𝑡 > 0 
If a t-test is applied to assess the statistical significance of this difference. The pooled variance is calculated as: 
	𝑁	𝑁
𝑆𝑡2 = [∑ (𝐶𝐴𝑅𝑤,𝑛,𝑡 − 𝐴𝐶𝐴𝑅𝑤,𝑡)2 + ∑ (𝐶𝐴𝑅𝐿,𝑛,𝑡 − 𝐴𝐶𝐴𝑅𝐿,𝑡)2]/2(𝑁 − 1) 
	𝑛=1	𝑛=1
The t-statistic is then derived as: 
[𝐴𝐶𝐴𝑅𝐿,𝑡  −  𝐴𝐶𝐴𝑅𝑤,𝐽 ]
	𝑇𝑡    	 
 
 
#Interpretation 
If the t-statistic is significantly different from zero, it provides evidence against the semi-strong form of market efficiency and supports the overreaction hypothesis. The study also examines whether this behavioral anomaly contributes to the January Effect, by analyzing seasonal patterns in the performance of winner and loser portfolios. 
 
#Model Validation 
To ensure the reliability of the machine learning model used in this study, K-Fold CrossValidation is employed. This technique divides the dataset into k equal subsets and iteratively trains the model k times, each time using a different subset as the validation set and the remaining subsets for training. The results are then averaged to produce a comprehensive performance estimate. 
This method helps reduce overfitting, maximizes data utilization, and provides a more robust evaluation of model accuracy. The primary performance metric is Mean Squared Error (MSE), with lower values indicating higher predictive accuracy and better model generalization. In this study, the MSE values were consistently low across all folds, suggesting that the model fits the data well and avoids both overfitting and underfitting, offering confidence in its predictive reliability.

#Results
The results showed that the overreaction effect is observable in some periods and markets. In the IT market, loser stocks in the short-term with daily data often turn into winner stocks in the next period. This finding indicates the presence of excessive investor reaction to short-term fluctuations, which can be attributed to their irrational and emotional behavior. On the other hand, in the oil and gas market, no significant overreaction effect was observed, and price behavior was more stable and predictable. This difference could be related to the intrinsic characteristics of each market and the type of investors in them.
Overall, this research shows that the overreaction effect may appear differently in various markets. In short-term markets, loser stocks may turn into winner stocks, but this pattern is not clearly observed in long-term periods. These differences suggest that investor behavior varies depending on the market type and time period, and is related to the specific characteristics of each market.
