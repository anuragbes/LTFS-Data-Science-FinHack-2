# LTFS-Data-Science-FinHack-2-conducted-by-Analytics-Vidhya

LTFS receives a lot of requests for its various finance offerings that include housing loan, two-wheeler loan, real estate financing and micro loans. The number of applications received is something that varies a lot with season. Going through these applications is a manual process and is tedious. Accurately forecasting the number of cases received can help with resource and manpower management resulting into quick response on applications and more efficient processing.

You have been appointed with the task of forecasting daily cases for next 3 months for 2 different business segments aggregated at the country level keeping in consideration the following major Indian festivals (inclusive but not exhaustive list): Diwali, Dussehra, Ganesh Chaturthi, Navratri, Holi etc. (You are free to use any publicly available open source external datasets).

# Rank
[Public LeaderBoard](https://datahack.analyticsvidhya.com/contest/ltfs-data-science-finhack-2-an-online-hackathon/) : 21 / 6319</br>
[Private LeaderBoard](https://datahack.analyticsvidhya.com/contest/ltfs-data-science-finhack-2-an-online-hackathon/) : 23 / 6319

# Approach

#### Problem type: Business Forecasting (Time Series)

#### Solution Approach: Regression
  * Separated Business case 1 and Business case 2 
  * Created Date-time features such as Month, year, etc.
  * Created Lag and Rolling Mean features (Not a significant impact).
  * Created Holiday features and its distance from nearest given date.
  * Evaluated XGBoost and LightGBM for both cases separately.
  * Differentiated 4 different scenarios(different combination of features) where MAPE score on Leaderboard was just above 16 and took Harmonic Mean of all the cases which shot up the Leaderboard MAPE Score to 12.XX
  
#### Specified Evaluation Metric: MAPE (Mean Absolute Percentage Error)
