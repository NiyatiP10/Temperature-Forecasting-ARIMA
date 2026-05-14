# Temperature Forecasting using ARIMA

A Time Series Forecasting project that predicts **Maximum** and **Minimum Temperature** using the **ARIMA (AutoRegressive Integrated Moving Average)** model in Python.

This project demonstrates the complete workflow of:

* Data preprocessing
* Time series analysis
* Temperature forecasting
* Model evaluation
* Visualization of predictions

---

## Features

* Forecasts daily **maximum** and **minimum** temperature
* Uses **ARIMA** model for time series prediction
* Visualizes actual vs predicted values
* Calculates forecasting accuracy using:

  * MAPE
  * MAE
  * RMSE
* Supports future temperature forecasting

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The dataset contains:

* Date
* Maximum Temperature
* Minimum Temperature

Example:

| Date       | Max | Min |
| ---------- | --- | --- |
| 2020-01-01 | 32  | 18  |
| 2020-01-02 | 31  | 17  |

---

## ARIMA Model

The project uses:

ARIMA(p,d,q)

Where:

* **p** → Auto Regression
* **d** → Differencing
* **q** → Moving Average

Current model configuration:

```python
ARIMA(4,1,0)
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/NiyatiP10/Temperature-Forecasting-ARIMA.git
```

Move into the project folder:

```bash
cd Temperature-Forecasting-ARIMA
```

## Required Libraries

```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
```

---

## How to Run

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Temperature_Forecasting_ARIMA.ipynb
```

---


## Workflow

1. Import dataset
2. Clean and preprocess data
3. Split into train and test data
4. Train ARIMA model
5. Forecast temperature
6. Compare predicted vs actual values
7. Calculate error metrics
8. Visualize results

---

## Model Evaluation Metrics

The project uses:

* Mean Absolute Percentage Error (MAPE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

Example:

```python
mae = mean_absolute_error(actual, predicted)
rmse = np.sqrt(mean_squared_error(actual, predicted))
```

---

## Results

The model successfully forecasts:

* Maximum temperature trends
* Minimum temperature trends

Graphs are generated for:

* Training data
* Testing data
* Predicted vs Actual values

---

## Future Improvements

Possible upgrades:

* SARIMA model
* LSTM Deep Learning model
* Streamlit web application
* Weather API integration
* Real-time forecasting dashboard

---


## Learning Outcomes

Through this project, you can learn:

* Time Series Analysis
* ARIMA Forecasting
* Data Visualization
* Statistical Modeling
* Forecast Accuracy Evaluation

---

## Author

GitHub: NiyatiP10

---

## License

This project is open-source and available under the MIT License.
