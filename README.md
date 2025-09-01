# ETL-Process
📌 Overview

This project focuses on cleaning, processing, and enriching raw uber data to make it analysis-ready. The dataset contains ride details such as distance fare, and payment method. The main goal is to ensure the data is consistent, accurate, and structured for downstream tasks like analytics, reporting, or machine learning.

Steps Performed

Data Loading
Imported the dataset into a Pandas DataFrame for manipulation.
Handling Missing Values

Replaced missing values in numerical columns (e.g., ride distance, fare) with the column median.

Replaced missing values in categorical columns (e.g., payment type, ride status) with the column mode.

Feature Engineering

Created a new feature Ride_Category based on ride distance:
No category → Distance = 0
Short → 0–5 km
Medium → 5–15 km
Long → 15–50 km

Validation

Verified data types of all columns.
Checked and confirmed there were no remaining null values.
Checked for consistency across ratings, cancellations, and payment methods.

📊 Tools & Libraries
Python 
Pandas
