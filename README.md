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

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/itsual/Time-Series.git
   ```
2. Navigate to the directory:
   ```bash
   cd Time-Series-Analysis
   ```
3. Open the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

---

## Sample Dataset

![Dataset Icon](https://img.icons8.com/ios-filled/50/000000/table.png)  
The repository includes the **international-airline-passengers.csv** dataset, a classic example for time series analysis.

| Month      | Passengers |
|------------|------------|
| 1949-01    | 112        |
| 1949-02    | 118        |
| 1949-03    | 132        |
| ...        | ...        |

---

## Visualization Examples

### Seasonal Decomposition
![Seasonal Decomposition Icon](https://img.icons8.com/ios-filled/50/000000/statistics.png)  
Decompose time series data into trend, seasonality, and residual components:

```python
from statsmodels.tsa.seasonal import seasonal_decompose
result = seasonal_decompose(data['Passengers'], model='additive')
result.plot();
```

### Forecasting with ARIMA
![ARIMA Icon](https://img.icons8.com/ios-filled/100/000000/line-chart.png)  
Implement ARIMA for predictive modeling:

```python
from statsmodels.tsa.arima.model import ARIMA
model = ARIMA(data['Passengers'], order=(5,1,0))
model_fit = model.fit()
print(model_fit.summary())
```

---

## Contribution Guidelines

Contributions are welcome! Please create a pull request or raise an issue if you have suggestions for improvement.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

![Thank You Icon](https://img.icons8.com/ios-filled/100/000000/handshake.png)

Happy Forecasting! 🌟
