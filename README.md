# GDP-Growth-Analysis
In this Analysis, I examined the increase or decrease in the total value of all goods and services produced within a given period of time with Power BI.

This project is a comprehensive analysis of 89 countries' Gross Domestic Product (GDP) growth. The total GDP value for all countries is $62,264.3T. The purpose of this analysis is to understand the YoY (Year-over-Year) growth of the countries and to identify the top 10 countries with the highest Total GDP.

![image](https://user-images.githubusercontent.com/124893685/218312714-f1658084-cbc9-495e-916b-9f2dd0e6507a.png)

# Data Collection and Preparation
The data for this analysis was collected from a reputable source, [Kaggle](https://www.kaggle.com/datasets/zackerym/gdp-annual-growth-for-each-country-1960-2020), and processed to ensure its accuracy and completeness. The data included the following variables:

- Country Name - name of country
- Country Code - code of country (3 letters)
- Indicator Name - all fields filled with 'GDP (current US$)'
- Indicator Code - all fields contains 'NY.GDP.MKTP.CD' value
- Colums for each year
A comparison metric was added to the data to calculate the YoY growth of each country's GDP. The YoY growth was calculated by dividing the current year's GDP by the previous year's GDP and subtracting 1. This calculation provided a clear picture of each country's GDP growth over time.

A trend analysis was also conducted to understand the overall trend of the countries' YoY growth. This was done by creating a line chart that plotted the YoY growth over time for each country. The chart helped to identify the countries that were experiencing consistent growth, as well as those that were experiencing fluctuations in their GDP growth.

# Top 10 Countries by Total GDP
An analysis was carried out to identify the top 10 countries by Total GDP. The Total GDP was calculated by summing the GDP for each year for each country. The top 10 countries were then ranked in descending order based on their Total GDP.

# Running Total and % Contribution
The running total was calculated by adding the Total GDP for each country. This provided a comprehensive view of the total GDP for all 89 countries and helped to understand the relative contribution of each country to the Total GDP.

The % Contribution of each country to the Total GDP was calculated by dividing the Total GDP for each country by the Total GDP for all 89 countries and multiplying by 100. This calculation provided a clear picture of each country's contribution to the Total GDP.

# Conditional Formatting
Conditional formatting was applied to the % Contribution column to highlight countries with GDP contributions lower than 10% (light red) and those with GDP contributions higher than or equal to 10% (light green). This helped to quickly identify the countries that were making a significant contribution to the Total GDP and those that were not.

# Conclusion
This analysis provided a comprehensive view of the GDP growth of 89 countries over time and helped to identify the top 10 countries with the highest Total GDP. It also helped to understand the YoY growth and trend of each country's GDP, as well as the relative contribution of each country to the Total GDP. The results of this analysis can be used by governments, investors, and businesses to make informed decisions about the potential of the global economy and to identify opportunities for growth and development.
