# Air Quality Forecasting

## Overview
This project compares **Linear Regression** and **Random Forest Regressor** for forecasting **Air Quality Index (AQI)** values based on pollutants like **CO**, **Ozone**, **NO2**, and **PM2.5**. The analysis includes data preprocessing, feature engineering, model training, evaluation, and comparison using key metrics such as **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² score**.

## Key Findings
- **Random Forest** outperforms **Linear Regression** in terms of accuracy, with lower MAE and RMSE and a higher R² score.
- The **Random Forest** model is better suited for capturing complex, non-linear relationships between air quality pollutants and AQI values.

## Files
- **AQI-and-Lat-Long-of-Countries.csv**: Air quality data for training and testing the models.
- **Air_Quality_Forecasting.ipynb**: Jupyter notebook containing the complete analysis, model training, evaluation, and visualizations.
- **requirements.txt**: Python dependencies for the project.

## Technologies Used
- Python
- **Pandas** for data wrangling
- **Scikit-learn** for machine learning models
- **Matplotlib** and **Seaborn** for data visualization
- **Plotly** for interactive visualizations

## How to Contribute
Feel free to fork the repository and create a pull request with improvements or suggestions. Contributions are welcome!
