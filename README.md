# Online Driver License Renewal Forecast

![](https://github.com/austinmyc/Driver-License-Renewal/assets/59735570/6743a3d5-d7b8-4af4-97e2-2edcc13651e0)

### Background

- This project focuses on forecasting the volume of driver license renewals processed through the online channel in Queensland, Australia. 
- A total of eight types of models have been used to forecast the series, and the Dynamic Harmonic Regression model and Extreme Gradient Boosting (XGBoost) give the best results, even though they are based on entirely different modeling concepts. 
- The Rmd file and preprocessed dataset can be accessed in the repo.

---

### Data Source
- The target data was acquired at **"Queensland Government Open Data Portal"**: (https://www.data.qld.gov.au/dataset/daily-driver-licence-renewals)
- Weather data was acquired at **"SILO - Australian climate data from 1889 to yesterday"**: (https://www.longpaddock.qld.gov.au/silo/)
- Both are official data released by the Queensland Government, Australia.

---

### Visualization
We used the data from 2020 - 2023:

![Timeplot_of_data](https://github.com/austinmyc/Driver-License-Renewal/assets/59735570/b2c2e6a2-aafd-41a3-bec5-4da89ac9d4a2)

![Seasonal_plot](https://github.com/austinmyc/Driver-License-Renewal/assets/59735570/55ab2acf-f8a3-4e80-9f06-5d9a1f704535)

---

### Models applied
- Benchmark 
- Linear 
- Exponential Smoothing 
- ARIMA
- Dynamic Regression 
- Vector Autoregression
- XGBoost
- Prophet
