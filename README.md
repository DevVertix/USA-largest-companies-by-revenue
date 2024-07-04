
# Largest companies in the USA


This project involves web scraping Wikipedia to gather data on the top 100 largest companies in the USA by revenue, followed by cleaning and analyzing the dataset using Python/PowerBI.

Overview :
The goal of this project is to collect and analyze data from Wikipedia pages listing the top 100 largest companies in the USA by revenue. The project includes web scraping using BeautifulSoup for data extraction and pandas for data cleaning and analysis. The cleaned dataset is then stored in Excel format for further use and analysis.

# Technologies Used:
- Python
- BeautifulSoup
- pandas
- openpyxl (Excel engine for pandas)
- PowerBI
  
# Project Structure:
The project is organized into the following main components:

1.Web Scraping Script:

- Wikipedia_largest_companies_USA_scraping.ipynb: Jupyter notebook containing the web scraping script using BeautifulSoup to extract company data from       Wikipedia.
  
2.Data Cleaning and Analysis:

- Dataset_cleaning.ipynb: Jupyter notebook where the extracted data is cleaned using pandas. This includes handling missing values, correcting errors, and ensuring data consistency.
  
3.Dataset:

- USA_companies: Excel file containing the dataset of the top 100 largest companies in the USA by revenue before cleaning.

- cleaned_largest_companies_USA_dataset.xlsx: Excel file containing the cleaned dataset of the top 100 largest companies in the USA by revenue.

# Visualization and Analysis Questions:

This dataset provides insights into the top 100 largest companies in the USA by revenue. Here are some questions and topics for visualization that we will answear:

1.Revenue Distribution by Industry:
Visualize the distribution of revenues among different industries (e.g., Retail, Healthcare, Technology, Petroleum).
Compare and contrast the revenue contributions of different sectors.

2.Geographical Insights:
Map the headquarters locations of these top companies.
Identify any regional concentrations of high-revenue companies.

3.Sector Comparison:
Compare the revenue performance of companies in Healthcare, Technology, and Petroleum sectors.
Investigate differences in revenue growth rates between sectors.

![Revenue Distribution by Industry]([images/revenue_distribution.png](https://private-user-images.githubusercontent.com/96891235/345853725-f444c0c8-267d-4bae-b7b5-dcabe80783e8.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAxMDExODAsIm5iZiI6MTcyMDEwMDg4MCwicGF0aCI6Ii85Njg5MTIzNS8zNDU4NTM3MjUtZjQ0NGMwYzgtMjY3ZC00YmFlLWI3YjUtZGNhYmU4MDc4M2U4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA0VDEzNDgwMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTNlODY1OTY3ZjIwZTRmZGRhZmQ5ODY5ZjI4NDMwODZhYWNjNGE5NDEzMmFmNDEzZWZkZGZiMTI5MTc2YjM1MjcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.U5gZdxLjwefMZPpjv-UuC2ymlM6ZepFvR9295BUHHCg))

