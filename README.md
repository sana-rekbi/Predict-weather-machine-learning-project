# Predict The Weather with Machine Learning: Beginner Project

This project demonstrates how to predict local weather using machine learning techniques. It's designed as a beginner-friendly tutorial that walks you through downloading weather data, preparing it for machine learning, and using a Ridge Regression model to make predictions.

## Project Overview

In this project, you will:
1. Download weather data
2. Clean and preprocess the data
3. Fill in missing values
4. Analyze weather data for insights
5. Train a Ridge Regression machine learning model
6. Evaluate the model's performance
7. Add additional features such as rolling means, monthly, and daily averages
8. Run diagnostics on the trained model

## Key Features

- **Languages**: Python
- **Tools**: Jupyter Notebook, Pandas, Scikit-learn
- **Machine Learning Model**: Ridge Regression

## Dataset
1. **Access the NOAA website**  
   Go to [NOAA Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/search).

2. **Search for Data**  
   - Enter the years you want (e.g., starting from 1970).
   - Search for the closest airport to you, or use your city/country name if no airport is available.

3. **Add to Cart**  
   - Click **Add to Cart** for the selected airport/location.
   - If you can't find an airport nearby, try your city or country name instead.

4. **Download Data**  
   - Go to your cart: [NOAA Cart](https://www.ncdc.noaa.gov/cdo-web/cart).
   - Select **CSV** format and click **Continue**.
   - Check all the boxes for data types.
   - Enter your email and click **Continue**.

5. **Receive Download Link**  
   You'll receive an email with a link to download the data. Download the CSV file provided.

6. **Data Documentation**  
   Review the [NOAA data documentation](https://www.ncdc.noaa.gov/cdo-web/datatools/documentation) to understand the column formats and data types.

### Steps

1. **Download the Data**  
   The first step is to download the dataset from the Dataquest repository.

2. **Data Loading and Preprocessing**  
   We'll use Pandas to load the dataset into a DataFrame, clean it, and handle missing values.

3. **Feature Engineering**  
   After analyzing the data, we create additional features such as rolling means, and monthly and daily averages to improve the model.

4. **Model Training**  
   A Ridge Regression model is trained on the prepared dataset to predict the weather.

5. **Model Evaluation**  
   We evaluate the model's performance using standard evaluation metrics and fine-tune it to improve accuracy.

6. **Prediction Function**  
   A function is created to make predictions based on the model.
