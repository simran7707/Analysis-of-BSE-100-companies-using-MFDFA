# Analysis-of-BSE-100-companies-using-MFDFA


# INTRODUCTION
The study of stock prices is a complex one, but we are using innovative regression models and
multifractal analysis to gain a better understanding. Our approach is dynamic and driven by a
commitment to uncovering the financial intricacies that move markets.

Our journey commences with a meticulous examination of stock market dynamics, utilizing
formidable regression models such as Linear Regression, Decision Tree Regressor, and Random
Forest. Through rigorous evaluation, scrutinizing metrics like R-squared, Root Mean Square
Error (RMSE), and Mean Absolute Error (MAE), a standout emerges—LSTM. With an
impressive R-squared score of 0.9, LSTM not only underscores its predictive prowess but also
solidifies its position as a key player in the nuanced landscape of stock market intricacies.
Expanding our analytical scope, we delve into the emerging frontier of multifractal analysis,
gaining prominence in our quest to understand financial time series and fractal behavior.
Leveraging log returns as a pivotal metric, our focus shifts to discern the inherent multifractal
nature embedded in stock prices. The revelation of multiple Hurst exponents, extracted through
the Multifractal Detrended Fluctuation Algorithm (MFDFA), proves to be instrumental in
unveiling the nuanced self-similarity and fractionality governed by diverse power scaling laws.
Our research stands as a substantial contribution to the ongoing discourse on market behavior,
establishing a symbiotic relationship between advanced regression models and multifractal
analysis. This synergy is paramount in unraveling the intricacies of the financial landscape. The
journey into the intricate randomness of stock price fluctuations is not merely a scientific
exploration; it is guided by an unwavering commitment to uncover the latent patterns shaping
the financial landscape.

Ultimately, our work serves as a valuable exploration, providing profound insights that
contribute to a deeper understanding of the complexities inherent in financial markets. It is not
just about predicting stock prices; it is about decoding the underlying language of the market,
unveiling the hidden rhythms that governs the fluctuations of financial dynamics. This
comprehensive understanding enhances our ability to navigate the intricate randomness of
market movements, offering valuable perspectives for investors, analysts, and researchers alike.
Through this research journey, we illuminate the pathways to a more informed and insightful
engagement with the ever-shifting dynamics of financial markets.

# METHODOLOGY  
  
•	Data Collection: 
Our methodology initiates with the meticulous curation of a robust dataset, a fundamental cornerstone for our comprehensive analysis. We sourced daily closing prices for all sectors' indices on the Bombay Stock Exchange (S&P BSE) from July 1, 2000, to June 30, 2009. Leveraging web scraping techniques, we directly extracted this invaluable financial data from Yahoo Finance. A stringent selection criterion was applied, focusing on the 16 sectors with complete and uninterrupted data throughout the specified timeframe. This approach ensures data integrity, reliability, and a holistic representation of market dynamics. 
 
•	Regression Modeling: 
Our exploration delves into diverse regression models, each offering unique insights into stock price behaviors. Linear Regression, Decision Tree Regressor, and Random Forest are meticulously employed.  


•	R-Squared (Coefficient of Determination): 


  
•	RMSE (Root Mean Squared Error): 


The efficacy of each model is evaluated using key metrics, including R-squared, RMSE, and MAE.  
 
•	MAE (Mean Absolute Error): 

 
The standout performer, LSTM, emerges as a key player with an impressive R-squared score of 0.9, showcasing its superior predictive accuracy. 
 
•	Multifractal Analysis: 
Building on regression models, our methodology extends into multifractal analysis. Log returns serve as a pivotal metric, unraveling the multifractal nature inherent in stock prices. We employ the Multifractal Detrended Fluctuation Algorithm (MFDFA) to identify self-similarity and fractionality across diverse stochastic time series with varying power scaling laws.  
 
 
•	MFDFA (Multifractal Detrended Fluctuation Algorithm): 

![image](https://github.com/Himanshu300703/Analysis-of-BSE-100-companies-stocks-from-2013---2023-using-MFDFA-/assets/91286198/b25b15e2-c6ca-4646-962d-5d89fd2417f5)
 
  
 
 
•	Log Return: 

![image](https://github.com/Himanshu300703/Analysis-of-BSE-100-companies-stocks-from-2013---2023-using-MFDFA-/assets/91286198/a621f046-625c-4d2f-9c76-c2f1a50d8f39)
![image](https://github.com/Himanshu300703/Analysis-of-BSE-100-companies-stocks-from-2013---2023-using-MFDFA-/assets/91286198/4be28767-2616-4ea9-a415-db79c9843b08)
 
  
 
•	Generalized Hurst Exponent: 

![image](https://github.com/Himanshu300703/Analysis-of-BSE-100-companies-stocks-from-2013---2023-using-MFDFA-/assets/91286198/716b2b38-8bb3-4c51-9c45-a425f04924c1)
 
  
Four essential graphs—Fluctuations Function vs. Time, Generalized Hurst Exponent vs. Fluctuations Function, Mass Exponent vs. Fluctuations Function, and Multifractal Spectrum—illuminate intricate patterns and behaviors within the financial time series. 
 
•	Comparative Analysis: 
To enrich our understanding, we draw parallels with existing research endeavors. A comparative analysis with renowned researchers in the field offers insights into the unique contributions and differentiators of our project. 
 
 
Our methodology culminates in a holistic understanding of stock market dynamics, blending regression models and multifractal analysis. By adhering to rigorous data collection, advanced modeling, and in-depth analysis, our research aims to unravel the complexities inherent in stock price fluctuations, contributing valuable insights to the broader financial landscape. 
 
![Mind map (1)](https://github.com/simran7707/Analysis-of-BSE-100-companies-using-MFDFA/assets/92624625/56c4d10f-690b-4ecf-85ca-9a7e9146f328)

  
Fig. Flowchart showcasing methodology implemented 

# Model Training and Evaluation
![Mind map](https://github.com/simran7707/Analysis-of-BSE-100-companies-using-MFDFA/assets/92624625/038d50c3-c1a1-4fde-871d-49bf7321f439)
Fig. Flowchart showing various Machine Learning models used in this project  
