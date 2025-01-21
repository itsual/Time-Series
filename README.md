# Time Series Analysis

![Time Series Analysis Banner](https://img.icons8.com/ios-filled/100/000000/graph-report.png)

Welcome to the **Time Series Analysis** repository! This repository provides comprehensive resources for understanding, exploring, and implementing time series forecasting models such as AR, MA, ARMA, ARIMA, SARIMA, and Prophet. It also includes techniques for data preparation and exploratory data analysis (EDA).

---

## Repository Structure

- **Forecasting_Principles_and_Practice.pdf**  
  A detailed guide covering the theoretical and practical aspects of forecasting.  
  _Last Updated: 5 years ago_

- **Time Series Analysis Guide-Python.pdf**  
  A hands-on guide for time series analysis using Python, including code snippets and practical examples.  
  _Last Updated: Recently_

- **Time Series Models.ipynb**  
  A Jupyter notebook showcasing various time series models with step-by-step implementation.  
  _Last Updated: 5 years ago_

- **Time-Series-Analysis.ipynb**  
  A Jupyter notebook focusing on advanced time series analysis techniques.  
  _Last Updated: Recently_

- **international-airline-passengers.csv**  
  A sample dataset for time series analysis. It includes monthly totals of international airline passengers from 1949 to 1960.  
  _Last Updated: 5 years ago_

---

## Overview of Time Series Analysis

Time series analysis involves analyzing data points collected or recorded at specific time intervals. It is a critical component of forecasting and prediction in domains such as finance, weather forecasting, and supply chain management.

### Key Components of Time Series:

1. **Trend**: Long-term movement in the data.
2. **Seasonality**: Patterns that repeat over a fixed period.
3. **Cyclic**: Fluctuations with no fixed frequency.
4. **Noise**: Random variations in the data.

---

## Tools and Techniques

### 1. **Exploratory Data Analysis (EDA)**
   - Visualization of data trends, seasonality, and noise using tools like Matplotlib and Seaborn.
   - Statistical summaries to understand the data's behavior over time.

### 2. **Data Preparation**
   - Handling missing values.
   - Smoothing and detrending data.
   - Transformations (e.g., log, differencing) to stabilize variance.

### 3. **Forecasting Models**

#### AR (Auto-Regressive) Model:
Captures the dependency between an observation and a number of lagged observations.

#### MA (Moving Average) Model:
Models the dependency between an observation and a residual error from a moving average model applied to lagged observations.

#### ARMA (Auto-Regressive Moving Average) Model:
Combines AR and MA models for better accuracy.

#### ARIMA (Auto-Regressive Integrated Moving Average) Model:
Adds differencing to the ARMA model to make the data stationary.

#### SARIMA (Seasonal ARIMA) Model:
Extends ARIMA to include seasonality.

#### Prophet:
Developed by Facebook, this model is robust to missing data, outliers, and seasonal patterns.

---

## Time Series Analysis Notebooks

| Topic                      | Description                                                                                       | Link                                                                                       |
|----------------------------|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Introduction to Time Series| Basic introduction to time series concepts and terminology.                                       | [Introduction to Time Series](https://github.com/marcopeix/time-series-analysis/blob/master/01%20-%20Introduction%20to%20Time%20Series.ipynb) |
| Statistical Models         | Implementation and analysis using ARIMA models for time series forecasting.                       | [ARIMA Models](https://github.com/marcopeix/time-series-analysis/blob/master/02%20-%20ARIMA%20Models.ipynb) |
|                            | Techniques and applications of exponential smoothing methods.                                     | [Exponential Smoothing](https://github.com/marcopeix/time-series-analysis/blob/master/03%20-%20Exponential%20Smoothing.ipynb) |
|                            | Analysis and forecasting with state space models.                                                 | [State Space Models](https://github.com/marcopeix/time-series-analysis/blob/master/04%20-%20State%20Space%20Models.ipynb) |
|                            | Seasonal ARIMA models for time series with seasonal components.                                   | [SARIMA Models](https://github.com/marcopeix/time-series-analysis/blob/master/05%20-%20SARIMA%20Models.ipynb) |
| Deep Learning Models       | Using Long Short-Term Memory (LSTM) networks for time series forecasting.                         | [LSTM for Time Series](https://github.com/marcopeix/time-series-analysis/blob/master/06%20-%20LSTM%20for%20Time%20Series.ipynb) |
|                            | Implementation of the Moirai model for time series forecasting.                                   | [Moirai](https://github.com/marcopeix/time-series-analysis/blob/master/Moirai.ipynb)       |
|                            | Implementation of the N-BEATS (Neural Basis Expansion Analysis Time Series) model.                | [N-BEATS](https://github.com/marcopeix/time-series-analysis/blob/master/NBEATS.ipynb)      |
|                            | Implementation of the N-HiTS model for time series forecasting.                                   | [N-HiTS](https://github.com/marcopeix/time-series-analysis/blob/master/NHiTS.ipynb)        |
|                            | Implementation of the TSMixer model for time series forecasting.                                  | [TSMixer](https://github.com/marcopeix/time-series-analysis/blob/master/TSMixer.ipynb)     |
|                            | Implementation of the TiDE (Time Series Deep Embedding) model.                                    | [TiDE](https://github.com/marcopeix/time-series-analysis/blob/master/TiDE.ipynb)           |
|                            | Implementation of the Time-MOE (Mixture of Experts) model.                                        | [Time-MOE](https://github.com/marcopeix/time-series-analysis/blob/master/Time-MOE.ipynb)   |
|                            | Implementation of the TimeGPT model for time series forecasting.                                  | [TimeGPT](https://github.com/marcopeix/time-series-analysis/blob/master/TimeGPT.ipynb)     |
|                            | Implementation of the TimeLLM (Large Language Model) for time series forecasting.                 | [TimeLLM](https://github.com/marcopeix/time-series-analysis/blob/master/TimeLLM.ipynb)     |
|                            | Implementation of the TimesNet model for time series forecasting.                                 | [TimesNet](https://github.com/marcopeix/time-series-analysis/blob/master/TimesNet.ipynb)   |
| Advanced Techniques        | Blog post covering time series analysis using the BitCN model.                                    | [BitCN Blog](https://github.com/marcopeix/time-series-analysis/blob/master/bitcn_blog.ipynb) |
|                            | Implementation of the Chronos model for time series forecasting.                                  | [Chronos](https://github.com/marcopeix/time-series-analysis/blob/master/chronos.ipynb)     |
|                            | Time series analysis using conformal predictions.                                                 | [Conformal Predictions](https://github.com/marcopeix/time-series-analysis/blob/master/conformal_predictions_ts.ipynb) |
|                            | Introduction to time series classification methods.                                               | [Intro to Time Series Classification](https://github.com/marcopeix/time-series-analysis/blob/master/intro_time_series_classification.ipynb) |
|                            | Blog post covering time series analysis using the iTransformer model.                             | [iTransformer Blog](https://github.com/marcopeix/time-series-analysis/blob/master/itransformer_blog.ipynb) |
|                            | Blog post covering time series analysis using the Kan model.                                      | [Kan Blog](https://github.com/marcopeix/time-series-analysis/blob/master/kan-blog.ipynb)   |
|                            | Implementation of the LagLLama model for time series forecasting.                                 | [LagLLama](https://github.com/marcopeix/time-series-analysis/blob/master/lag_llama.ipynb)  |
|                            | Blog post covering time series analysis using the RMO model.                                      | [RMO Blog](https://github.com/marcopeix/time-series-analysis/blob/master/rmok_blog.ipynb)  |
|                            | Blog post covering time series analysis using the SoftS model.                                    | [SoftS Blog](https://github.com/marcopeix/time-series-analysis/blob/master/softs-blog.ipynb) |
|                            | Implementation of the Theta model for time series forecasting.                                    | [Theta Model](https://github.com/marcopeix/time-series-analysis/blob/master/theta_model.ipynb) |
|                            | Blog post covering time series analysis using the TimeMixer model.                                | [TimeMixer Blog](https://github.com/marcopeix/time-series-analysis/blob/master/timemixer_blog.ipynb) |
|                            |Transfer learning for Time Series Forecasting                                                      | [Transfer Learning](https://github.com/Nixtla/transfer-learning-time-series) |

---

## Contribution Guidelines

Contributions are welcome! Please create a pull request or raise an issue if you have suggestions for improvement.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

![Thank You Icon](https://img.icons8.com/ios-filled/100/000000/handshake.png)

Happy Forecasting! 🌟

---

## Visualization: Decision Tree for Model Selection

![Refined Time Series Decision Tree](https://github.com/itsual/Time-Series/blob/main/Decision%20Tree%20To%20Choose%20Time%20Series%20Techniques.svg)
