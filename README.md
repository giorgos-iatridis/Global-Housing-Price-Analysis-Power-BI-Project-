# Global-Housing-Price-Analysis-Power-BI-Project-

This project explores key socioeconomic indicators across different countries using Power BI.
The analysis is based on three main datasets:

- Housing prices and related property indicators
- Global unemployment rates
- Net household income by country

By combining these datasets, the project aims to provide insights into how housing markets, unemployment, and household income interact on a global scale. The final dashboards highlight trends, comparisons across countries, and potential correlations between these critical socioeconomic factors.

## Data

The data I'm going to use in this project is included in three tables.
1. Global housing prices and other important indexes (source: https://www.kaggle.com/datasets/atharvasoundankar/global-housing-market-analysis-2015-2024)
2. Unemployment data by Age, Year and Country (source: https://www.kaggle.com/datasets/sazidthe1/global-unemployment-data)
3. GDP per capita (current US$) (source: https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)

## Data Cleaning

First, I did some very important transformations in my tables:

**Income** Table:
- First Row as columns's headers
- Changed the type of the columns
- Deleted blank rows
- Replaced values to the right form (e.g., _Russia Federation_ to _Russia_)
- Filtered to keep countries (e.g., Deleted values like Eastern Asia, Low Income)
- Unpivoted Columns so the years 2014-2024 added as values in one column named _Year_ and not as headers of different columns

**Unemployment** Table:
- Fixed the numbers in the correct form and type (comma instead of dot, decimal number instead of text)
- Replaced values to the right form (e.g., _Russia Federation_ to _Russia_)
- Rounded decimal number to two digits
- Removed unuseful columns
- Renamed Columns

**Housing Indexes** Table:
- First Row as columns's headers
- Fixed the numbers in the correct form and type and rounded them to two decimal digits

#### Screenshots

##### Income Table Before
<img width="1669" height="711" alt="image" src="https://github.com/user-attachments/assets/35d411ea-f2ad-47c7-97e6-5b5c50a8798d" />

##### Income Table After
<img width="1894" height="751" alt="image" src="https://github.com/user-attachments/assets/09af6713-6c49-4a34-8e63-2d4660eb94db" />

##### Unemployment Table Before
<img width="1920" height="794" alt="image" src="https://github.com/user-attachments/assets/58ee033c-2ea1-48f1-bb3c-09b9135eaa7f" />

##### Unemployment Table After
<img width="1920" height="802" alt="image" src="https://github.com/user-attachments/assets/a3015e91-33ef-4ea3-9a19-f455e65d097a" />

##### Housing Indexes Table Before
<img width="1920" height="791" alt="image" src="https://github.com/user-attachments/assets/7f0fd077-fdf4-4c54-8cc0-4089e03fa2d8" />

##### Housing Indexes Table After
<img width="1911" height="788" alt="image" src="https://github.com/user-attachments/assets/49980f20-0abd-4cd7-b8cd-8e130769ecbf" />


