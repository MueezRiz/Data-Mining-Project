# Data-Mining-Project
Analysis on weather and climate dataset. Electricity Demand Forecasting Project

Overview

This project involves a Jupyter Notebook (Data_Mining_Project.ipynb) that processes and analyzes electricity demand data alongside weather data to forecast electricity demand for various cities. The notebook extracts data from a ZIP file, performs data preprocessing, conducts anomaly detection, and visualizes the results using forecasting techniques.

Project Structure

Data Source: The dataset is contained in Data.zip, which includes:

cleaned_balance_data.csv: Electricity demand data for various cities.

cleaned_subregion_data.csv: Additional electricity demand data.

JSON files: Weather data for different cities, containing features like temperature, humidity, and wind speed.


Output:

merged_data.csv: A merged dataset combining electricity demand and weather data.

Visualizations of actual vs. predicted electricity demand for a sample city.


Dependencies

To run the notebook, ensure you have the following Python libraries installed:

pandas
numpy
matplotlib
scikit-learn
scipy
xgboost

