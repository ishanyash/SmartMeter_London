# SmartMeter_London
This repository contains a comprehensive Jupyter notebook dedicated to the preprocessing of smart meter data, laying a robust foundation for subsequent Exploratory Data Analysis (EDA). The notebook is meticulously structured to transform raw data into a format that's conducive to in-depth analysis and insights extraction.

Key Features:

Date Time Formatting for EDA:

Utilizes libraries like pandas, calendar, datetime, and os for efficient data handling.
Features a preprocess_data function that:
Converts 'tstp' column to datetime, extracting date, month, day, time, and weekday.
Orders weekdays and months for intuitive analysis.
Transforms energy consumption data into a numeric format.
Calculates cumulative energy use.
Sets 'datetime' as the index for easier time-series analysis.
Batch Processing of Data Files:

Establishes a workflow for processing multiple data files ('block_*.csv').
Automates the creation of an output folder for processed files.
Applies the preprocess_data function to each file in a loop.
Ensures robustness with error handling mechanisms during file processing.
Data Aggregation:

Defines a pathway for storing aggregated data.
Concatenates all preprocessed datasets into a single comprehensive file.
Saves the merged dataset for downstream analysis.
Project Significance:

This preprocessing notebook is crucial for anyone looking to dive deep into smart meter data analysis. By structuring and cleaning the data effectively, it sets the stage for meaningful EDA and further advanced analytical tasks, such as time-series forecasting, anomaly detection, and pattern recognition in energy consumption.

Usage:

Ideal for data scientists and analysts in the energy sector, this repository serves as a template for managing and preprocessing large volumes of time-series data from smart meters. It showcases efficient data manipulation techniques and serves as a springboard for more complex data science projects in the utility industry.
