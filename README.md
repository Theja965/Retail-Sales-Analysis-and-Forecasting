# Retail-Sales-Analysis-and-Forecasting

## Project Overview

This project provides an end-to-end analysis of a retail sales dataset. The primary objectives are to perform a thorough exploratory data analysis (EDA) to uncover patterns in customer behavior and sales trends, and to develop a time-series model to forecast future sales. This analysis can help inform inventory management, staffing, and marketing strategies.

## Dataset

The dataset (`retail_store_sales1.csv`) contains transactional data for a retail store from 2022 to early 2025. It includes information such as transaction dates, product categories, prices, quantities sold, and payment methods.

## Methodology

The analysis follows a structured workflow:
1.  **Data Cleaning and Preprocessing:** Handled missing values, corrected data types, and ensured data consistency for accurate analysis.
2.  **Exploratory Data Analysis (EDA):** Investigated the dataset to answer key business questions, such as identifying the overall sales trend over time and determining the top-performing product categories by revenue.
3.  **Time-Series Forecasting:** Prepared the data for time-series modeling and implemented Facebook Prophet to forecast sales for the next 30 days. The model's components (trend, weekly, and yearly seasonality) were analyzed to understand the underlying patterns driving the forecast.

## Key Findings

-   **Sales Trends:** The EDA revealed distinct weekly and yearly seasonal patterns in sales volume.
-   **Top Categories:** Patisserie and Food items are the highest contributors to total revenue.
-   **Sales Forecast:** The Prophet model successfully captured the seasonality in the data and produced a forecast for the upcoming month, complete with uncertainty intervals. The side-by-side visualization in the notebook effectively compares the model's fit on historical data against the future projection.

## Technologies Used

-   Python
-   Pandas
-   Matplotlib & Seaborn
-   Prophet
-   Jupyter Notebook

## Installation and Usage

To replicate this analysis, please follow these steps:

1.  Clone the repository to your local machine:
    ```bash
    git clone [https://github.com/Theja965/Retail-Sales-Analysis-and-Forecasting.git](https://github.com/Theja965/Retail-Sales-Analysis-and-Forecasting.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd Retail-Sales-Analysis-and-Forecasting
    ```
3.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.  Launch the Jupyter Notebook to view the analysis:
    ```bash
    jupyter notebook EDAFinalCopy.ipynb
    ```
