# Time series analytics - Sales forecasting

Use case: To forecast sales for a particular product category of Walmart.

## Description

This project is to forecast sales for Walmart superstore using time series analytics by going through industry best practice to deal with time series problems. The process includes:

- Check stationarity
- Transform data
- Decompose data into components
- Detect anomalies
- Test white noise
- Identify orders for model components
- Build models and measure their performance.

## Getting Started

### Dependencies

* Please check **requirement.txt** file.

### Data

The author attached the data file in the repository. It was retrieved from Kaggle at: https://www.kaggle.com/datasets/juhi1994/superstore

### Performance
![download](https://user-images.githubusercontent.com/91911269/233193537-c8af8922-d348-4794-93de-1a11a7cc1848.png)

**Final thoughts:**

- The SARIMAX model has demonstrated a significant improvement in accuracy compared to the ARIMA model, as evidenced by the plot.
- Look at the plot, the Green line closely follows the trend of the Blue line, in contrast to the poor performance of the Orange line.
- However, the SARIMAX model did not perform as well as expected due to the presence of outliers in the prediction testing period and the limited training data available (4 years).
- It is important to note that in real-world industry problems, outliers can be identified and addressed, and a longer time series of data can be used for training.

Overall, this work provides insights into the effective use of SARIMAX for sales prediction and I do hope you guys can grab an idea how to handle it to predict data.
