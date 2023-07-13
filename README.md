# Markowitz Portfolio and Game Theory Portfolio

## Introduction

The stock market has been around for well over 100 years. With an opportunity to increase one's wealth over a period of time by investing in companies' stocks the desire to maximize and minimize reward and risk, respectively, for each individual stock became a priority. The Markowitz model came about in 1952 to assist with stock portfolio optimization. The Markowitz model can diversify and measure reward given assumed risk and thus inform the investor if an investment is a stable investment or too volatile to dive into. This can help prevent a dramatic loss in investment that could occur without the aid of an optimization model. This model will delve into the range of risk parameters, and evaluate the most valuable stock portfolio for the investor based on the most optimal reward point for various levels of risk. 

We have tested the recommended strategy that the Markowitz framework provided by comparing the behavior of four different portfolios with different investment strategies ranging from conservative to aggressive. Jimmy's portfolio is comprised only of foreign currencies, Emma's uses half foreign currencies and half stocks, Avery's contains ten randomly chosen stocks from the S&P 500, and Ryan's contains the top ten stocks of the Dow Jones. Our goal in choosing these combinations was to find the ideal balance of risk and reward, and to determine whether a portfolio with lots of stability and a lower, more dependable return would perform much better, much worse, or similarly to a portfolio with very risky yet lucrative elements.

## Game Theory Analysis
In addition to the Markowitz portfolio strategy, we analyze the results within the framework of game theory, where there is no notion of risk. This analysis provides insights into the performance of the portfolios under different perspectives.

## Objective
The primary objective of this project is to analyze the effectiveness of different portfolios under the Markowitz portfolio strategy. By comparing the returns and risks associated with each portfolio, we aim to identify the optimal allocation of financial instruments that maximizes returns while considering acceptable levels of risk.

## Methodology
1. Data Preparation: We collect and preprocess historical data for the financial instruments included in the portfolios.
2. Markowitz Portfolio Strategy: We compute the Markowitz strategy for each portfolio using the training data sets. This strategy helps optimize the portfolio allocation based on expected returns and risk.
3. Risk-Return Analysis: We plot the strategies against each other to visualize the risk-return trade-offs for different portfolios.
4. Parameter Selection: We use validation data to evaluate the performance of the portfolios across various risk parameters and identify the best risk parameter.
5. Performance Assessment: We assess the performance of the selected strategy using testing data to validate its effectiveness.

## Results
Our findings indicate that portfolios heavily or solely comprised of financial currencies, which are considered stable assets, do not yield competitive returns for the same level of risk. On the other hand, portfolios consisting primarily of stocks, while increasing the risk, offer higher returns at every level. This suggests that stocks can compensate for their higher volatility with greater potential rewards.

## Value Proposition
This project serves as an investment strategy guide for both novice and experienced investors. By examining the vastly different portfolios comprised of various financial instruments, including a combined portfolio, individuals can gain valuable insights into why certain portfolios yield significantly higher rewards for the same level of risk. The model offers a comprehensive analysis and understanding of different investment strategies, aiding in informed decision-making.

## Future Enhancements
- Include additional financial instruments to expand the scope of the analysis.
- Explore alternative portfolio optimization strategies to compare against the Markowitz approach.
- Incorporate real-time or updated data to make the analysis more current and relevant.
- Consider external factors, such as market conditions or economic indicators, to provide a more comprehensive investment strategy guide.
