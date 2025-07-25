# Fight-Data

## 📊✈️ Project: Airline Data Analysis
This notebook performs Exploratory Data Analysis (EDA) on airline flight data to gain insights into travel patterns, pricing, delays, and other operational aspects. It is a foundational step for preparing the dataset for modeling or business intelligence.

📁 Contents
Loading and Inspecting Data

- Read dataset using pandas

- Initial data checks: shape, columns, data types, missing values

- ## Data Cleaning

- Handling null values (fillna, dropna)

- Removing duplicates

- Fixing inconsistent formats (e.g., converting Date_of_Journey)

Feature Engineering

- Extracting Day, Month, Year from Date_of_Journey

- Mapping Total_Stops to numeric

- Encoding categorical features: Airline, Source, Destination using OneHotEncoder

- Processing duration and time-related columns

## Data Visualization

- Distribution plots (price, duration)

- Count plots (airline frequency, stops)

- Boxplots to explore price variance across features

## Correlation and Insights

- Feature correlation matrix

- Key patterns and business insights identified

## 🛠️ Technologies Used
- [Python 3.13.3](https://www.python.org/downloads/release/python-3133/)

- Pandas

- Matplotlib / Seaborn

- Scikit-learn

## 🧠 Next Steps
- Feature selection for machine learning

- Model building (e.g., price prediction, delay forecasting)

- Dashboard or reporting tool integration (e.g., Tableau, Power BI)
