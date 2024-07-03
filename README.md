This project involves web scraping Wikipedia to gather data on the top 100 largest companies in the USA by revenue, followed by cleaning and analyzing the dataset using Python/PowerBI.

Overview :
The goal of this project is to collect and analyze data from Wikipedia pages listing the top 100 largest companies in the USA by revenue. The project includes web scraping using BeautifulSoup for data extraction and pandas for data cleaning and analysis. The cleaned dataset is then stored in Excel format for further use and analysis.

Technologies Used:
- Python
- BeautifulSoup
- pandas
- openpyxl (Excel engine for pandas)
- PowerBI
  
Project Structure:
The project is organized into the following main components:

1 .Web Scraping Script:

- Wikipedia_largest_companies_USA_scraping.ipynb: Jupyter notebook containing the web scraping script using BeautifulSoup to extract company data from       Wikipedia.
  
2. Data Cleaning and Analysis:

- Dataset_cleaning.ipynb: Jupyter notebook where the extracted data is cleaned using pandas. This includes handling missing values, correcting errors, and ensuring data consistency.
  
3. Dataset:

- USA_companies: Excel file containing the dataset of the top 100 largest companies in the USA by revenue before cleaning.

- cleaned_largest_companies_USA_dataset.xlsx: Excel file containing the cleaned dataset of the top 100 largest companies in the USA by revenue.

Visualization and Analysis Questions:

This dataset provides insights into the top 100 largest companies in the USA by revenue. Here are some questions and topics for visualization that we will answear:

1. Revenue Distribution by Industry:
Visualize the distribution of revenues among different industries (e.g., Retail, Healthcare, Technology, Petroleum).
Compare and contrast the revenue contributions of different sectors.

2. Revenue Growth Analysis:
Analyze the revenue growth percentages across different companies.
Identify trends and outliers in revenue growth rates.

3. Employment Analysis:
Visualize the correlation between revenue and number of employees for these companies.
Explore industries or companies with unusually high or low employee counts relative to revenue.

4. Geographical Insights:
Map the headquarters locations of these top companies.
Identify any regional concentrations of high-revenue companies.

5. Sector Comparison:
Compare the revenue performance of companies in Healthcare, Technology, and Petroleum sectors.
Investigate differences in revenue growth rates between sectors.
