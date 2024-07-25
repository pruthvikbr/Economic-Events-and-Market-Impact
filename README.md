
# S&P 500 Presidential Analysis and Stock Price Prediction

This project explores the relationship between presidential terms and the performance of the S&P 500 index. Additionally, it implements machine learning models to predict stock prices and analyze their trends over time. The project leverages historical stock data and applies various statistical and machine learning techniques to gain insights.

### How Presidential Elections Impact the Stock Market

Presidential elections can significantly impact the stock market due to the uncertainty they create and the potential for policy changes that could affect businesses and the economy. Here are a couple of examples illustrating this impact:

#### Example 1: The 2016 Presidential Election
The 2016 presidential election in the United States, where Donald Trump won against Hillary Clinton, is a prime example. Before the election, there was significant market volatility due to the uncertainty surrounding the outcome. Markets generally dislike uncertainty, and the potential for drastically different economic policies under Clinton and Trump led to fluctuating stock prices.

- **Pre-Election**: In the months leading up to the election, the stock market experienced increased volatility. Investors were unsure of the outcome and the subsequent policy direction.
- **Post-Election**: After Trump's victory, the stock market initially dropped sharply but then quickly rebounded, embarking on a sustained rally. This rally, often referred to as the "Trump bump," was driven by investor optimism about Trump's pro-business policies, including tax cuts and deregulation.

#### Example 2: The 2008 Presidential Election
The 2008 election, where Barack Obama won against John McCain, occurred during the financial crisis, adding another layer of complexity to its impact on the stock market.

- **Pre-Election**: Leading up to the election, the market was already under severe stress due to the financial crisis. There was significant volatility as investors were anxious about the potential leadership and policies that would address the economic downturn.
- **Post-Election**: Following Obama's victory, the stock market experienced continued volatility. However, the market began to stabilize as Obama introduced measures aimed at economic recovery, including the stimulus package. Over time, the policies helped restore investor confidence, contributing to a gradual market recovery.



## Project Overview
This project aims to:
1. Analyze the impact of different presidential administrations on the S&P 500 index.
2. Use machine learning models to predict stock prices based on historical data.

## Data Sources
- **S&P 500 Index Data**: Historical data for the S&P 500 index was obtained from Yahoo Finance.
- **Presidential Terms Data**: Details of presidential terms were used to annotate the stock performance during each administration.

## Methodology
1. **Data Collection**: Historical S&P 500 data was collected using the `yfinance` library.
2. **Data Annotation**: The stock data was annotated with presidential terms to study the impact of different administrations.
3. **Statistical Analysis**: Calculated annual returns, average returns, and standard deviations for different presidential terms.
4. **Machine Learning**: Implemented models including Linear Regression and Random Forest Classifier to predict stock prices.

## Findings
- The analysis revealed trends and patterns in stock performance across different presidential administrations.
- Average returns and standard deviations were compared between Democratic and Republican administrations.
- On an average Democrats performed well than the republicans comparing over the long term from 1985

- ![image](https://github.com/user-attachments/assets/3ef33b1e-a8b8-417f-a69c-ea66e8fc5e0f)

- ![image](https://github.com/user-attachments/assets/993b0a69-e726-4d79-b198-e1062d0306f1)
Linear Regression
![image](https://github.com/user-attachments/assets/41e6969f-acaa-4682-bb66-2b89892762ee)
- Polynomial Regression and Linear Regression
![image](https://github.com/user-attachments/assets/138080c9-5a3d-4940-8214-6db93e47363a)



## Machine Learning Models
1. **Linear Regression**: Applied linear regression to predict stock prices based on historical data.
2. **Polynomial Regression**: Used polynomial regression for a more complex fit to the data.
3. **Random Forest Classifier**: Implemented a Random Forest Classifier to predict whether the stock price will increase or decrease.

## Visualization
- Bar charts comparing average returns by president and party.
- Line plots showing the actual vs. predicted stock prices.
- Histogram of prediction probabilities from the Random Forest model.

## Conclusion
This project demonstrates the potential impact of political factors on financial markets and showcases the application of machine learning techniques in stock price prediction. The insights gained can inform investment strategies and provide a historical context for market analysis.


## Future Work
- Extend the analysis to include other financial indices and economic indicators.
- Improve the accuracy of machine learning models with additional features and advanced techniques.

---

This README provides a comprehensive overview of your project, highlighting key aspects without including any code. You can adapt it further based on specific details or preferences.
