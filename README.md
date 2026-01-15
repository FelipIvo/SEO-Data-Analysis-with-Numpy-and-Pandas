📊 SEO Data Analysis with Pandas and NumPy

This project demonstrates a simple SEO data analysis workflow using Python, Pandas, and NumPy.
It simulates SEO metrics and performs basic statistical analysis to extract insights such as averages, correlation, and click-through rate (CTR).

🚀 Project Overview

The script creates a simulated dataset containing SEO-related information, including:

URLs

Target keywords

Google search position

Number of clicks

Number of impressions

Using this data, the script performs:

Descriptive statistics (mean of clicks and impressions)

Correlation analysis between Google position and clicks

CTR (Click-Through Rate) calculation

This project is useful for educational purposes, SEO analysis demonstrations, or as a starting point for more advanced analytics.

🛠️ Technologies Used

Python 3

Pandas

NumPy

📈 Analysis Performed
1. Data Visualization

The script prints the initial DataFrame to allow inspection of the SEO data.

2. Mean Calculation

Using NumPy, it calculates:

Average number of clicks

Average number of impressions

3. Correlation Analysis

It computes the correlation coefficient between:

Google search position

Number of clicks

This helps evaluate how ranking position impacts user engagement.

4. CTR Calculation

A new column (CTR) is added to the DataFrame using the formula:

CTR = (Clicks / Impressions) * 100


This metric represents the percentage of impressions that resulted in clicks.

▶️ How to Run

Clone the repository:

git clone https://github.com/FelipIvo/SEO-Data-Analysis-with-Numpy-and-Pandas.git


Install dependencies:

pip install pandas numpy


Run the script:

python seo_analysis.py

📌 Example Output

Printed SEO dataset

Mean clicks and impressions

Correlation matrix

Updated DataFrame with CTR values
