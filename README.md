# Time series analytics - Sales forecasting

Use case: To forecast sales for a particular product category of Walmart.

## Description

This project is to forecast sales for Walmart superstore using time series analytics by going through industry best practices to deal with time series problems. The process includes:

-   Check stationary
-   Transform data
-   Decompose data into components
-   Detect anomaly
-   Test white noise
-   Identify orders for model components
-   Build models and measure their performance.

## Getting Started

### Dependencies

* Please check **requirement.txt** file.

### Data

The author attached the data file in the repository. It was retrieved from Kaggle at: https://www.kaggle.com/datasets/juhi1994/superstore

### Performance
![download](https://user-images.githubusercontent.com/91911269/233193537-c8af8922-d348-4794-93de-1a11a7cc1848.png)

**Final thoughts:**

- The accuracy has **improved a lot** from ARIMA to SARIMAX.
- Look at the plot, Green line at least could embrace the trends of Blue line, compared to very bad performance of Orange line.
- The reasons that SARIMAX is not good as expected are:
(1) We have **outliers right in front of prediction testing period**. In real industry problem, at least we will have information about the the outliers and we would know how to deal with the data.
(2) The **training data is not much**, we have 4 years for training and 1 year for predction. 

At least, through the works, I hope you guys could have the idea about how to use SARIMAX to predict sales.
