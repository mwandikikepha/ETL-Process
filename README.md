******ETL-Process******

Overview

This project focuses on cleaning, processing, and enriching raw Uber ride data to make it analysis-ready. The dataset includes details such as ride distance, fare, and payment method. The goal is to ensure the data is consistent, accurate, and structured for analytics, reporting, or machine learning tasks.

**** Steps Performed****

**1. Data Loading**

Imported the dataset into a Pandas DataFrame.

**2. Handling Missing Values**

Replaced missing values in numerical columns (e.g., ride distance, fare) with the median.

Replaced missing values in categorical columns (e.g., payment type, ride status) with the mode.

**3. Feature Engineering**

Created a new column Ride_Category based on ride distance:

No category → 0 km

Short → 0–5 km

Medium → 5–15 km

Long → 15–50 km

**4. Validation**

Verified column data types.

Confirmed no remaining null values.

Ensured consistency across ratings, cancellations, and payment methods.

Tools & Libraries

Python

Pandas
