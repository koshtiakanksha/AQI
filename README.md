## Time Series Analysis on Air Quality Index

![AQI](https://csu-ceams.com/blog/content/images/size/w2000/2020/07/aqi_mini-1200x675-1.png)

This project aims to explore the application of time series analysis in forecasting Air Quality Index (AQI) in Pune, India. 

**Objectives:**

1. Analyze air quality data from Pune to identify the top pollutants impacting AQI.
2. Investigate regions within Pune with consistently higher AQI levels.
3. Implement time series analysis for Karve Road station to forecast AQI for the next year.
4. Develop daily air quality reports based on the forecasted AQI.

**Methodology:**

* **Data Acquisition:** Pollutant concentration data for Pune regions (Nov 2020 - Aug 2023) and Karve Road station (Aug 2015 - Aug 2023) was obtained from the Central Pollution Control Board.
* **Data Preprocessing:** Missing values were addressed using seasonal mean imputation to maintain temporal patterns.
* **Top Pollutant Identification:** Correlation analysis was conducted to identify the top three pollutants influencing AQI across Pune regions.
* **High AQI Regions:** Analysis determined regions with consistently higher AQI levels.
* **Time Series Analysis (Karve Road):**
    * Stationarity tests (KPSS & ADF) ensured data suitability for time series analysis.
    * ARIMA models were employed to forecast pollutant concentrations (PM2.5, PM10, NO2) for the next year.
    * Model performance was evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
* **Daily Air Quality Reports:** Forecasted pollutant concentrations were used to calculate daily AQI for a year. Reports included:
    * Date
    * AQI value with color code and health risk information
    * Individual pollutant concentrations

**Findings:**

* The analysis identified PM2.5, PM10, and NO2 as the top contributors to AQI across Pune regions.
* Specific regions were pinpointed as having consistently higher AQI levels.
* Time series models achieved good performance with MAE (25-50) and MSE (20k-30k) ranges.
* Forecasted AQI levels remained below 400, indicating no severe air quality issues anticipated for Karve Road.

**Limitations:**

* The study focused on the Karve Road station, potentially limiting generalizability to the entire city.
* The analysis considered only the top three pollutants and may not capture the full picture.
* Forecasting uncertainties exist, and the study offered limited exploration of external factors influencing air quality.

**Conclusion:**

This project successfully applied time series analysis to forecast AQI for the Karve Road station in Pune. The findings provide valuable insights into air quality dynamics and can inform future air quality management strategies. However, limitations highlight the need for broader geographical coverage, incorporating more pollutants, and considering external factors for a more comprehensive understanding.

