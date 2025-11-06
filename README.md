# EDA-fortune-global-500

Problem Statement

The objective of this short EDA (Exploratory Data Analysis) was to perform a preliminary statistical and structural examination of the Fortune Global 500 (2023) dataset that I had previously scraped from Wikipedia. The goal was to understand the dataset’s composition, check for missing values or inconsistencies, and analyze the basic distribution of company rankings and revenues across industries and countries.

What I Did

1. Data Loading and Inspection:

Imported the cleaned dataset (fortune_global_500_2023.csv) using pandas.read_csv().

Displayed the first few records using df.head() to verify data structure.

2. Data Structure Analysis:

Checked the shape of the dataset, confirming 55 rows and 5 columns — Industry, Company, Country, Rank, and Revenue (in million USD).

Validated data types (object for categorical and int64 for numerical columns).

3. Data Quality Check:

Verified that there were no missing values using df.isnull().sum(), confirming data completeness.

4. Descriptive Statistics:

Used df.describe() to summarize numerical features.

Found that the average company rank was around 128, and the mean revenue was approximately $115,907 million, indicating large-scale multinational companies.

The maximum revenue reached over $500 billion, highlighting the dominance of the top firms.

Tools Used

Python (Pandas, NumPy): For data analysis and statistical computation.

Matplotlib & Seaborn: For data visualization (used for future correlation and distribution insights).

Kaggle Notebook: For performing, testing, and saving the EDA in a cloud environment.

Recommendations

1. Further Analysis: Conduct visual analysis to compare industry-wise and country-wise revenue distribution.

2. Correlation Study: Examine the relationship between company rank and revenue to identify industry performance trends.

3. Data Expansion: Add more years or historical data to observe long-term trends in company growth and rankings.

4. Outlier Study: Investigate extreme revenue values to understand business dominance or data skewness.

Conclusion

This short EDA confirmed that the scraped dataset is clean, well-structured, and ready for advanced analysis or visualization. The data accurately represents global corporate giants, with significant variations in revenue across industries. Through this exercise, I gained hands-on experience in data validation, summary analysis, and dataset quality assessment, laying a strong foundation for future analytics or predictive modeling on global business performance trends.
