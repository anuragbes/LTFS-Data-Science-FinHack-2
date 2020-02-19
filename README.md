# LTFS-Data-Science-FinHack-2
Conducted by Analytics Vidhya

# Rank
[Public LeaderBoard](https://datahack.analyticsvidhya.com/contest/ltfs-data-science-finhack-2-an-online-hackathon/) : 21 / 6319</br>
[Private LeaderBoard](https://datahack.analyticsvidhya.com/contest/ltfs-data-science-finhack-2-an-online-hackathon/) : 23 / 6319

# Approach

Problem type: Business Forecasting (Time Series)

Solution Approach: Regression
  * Separated Business case 1 and Business case 2 
  * Created Date-time features such as Month, year, etc.
  * Created Lag and Rolling Mean features (Not a significant impact).
  * Created Holiday features and its distance from nearest given date.
  * Evaluated XGBoost and LightGBM for both cases separately.
  * Differentiated 4 different scenarios where MAPE score on Leaderboard were just above 16 and took Harmonic Mean of all the cases which shot up the Leaderboard MAPE Score to 12.XX
  
Specified Evaluation Metric: MAPE (Mean Absolute Percentage Error)
