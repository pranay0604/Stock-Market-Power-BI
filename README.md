# Stock-Market-Power-BI

 This Power BI project delivers a comprehensive dashboard that combines company metadata (sector, country, name) with real stock market performance data. It provides users with actionable insights on how various companies across sectors and countries are performing based on stock prices, sales volumes, and turnover.
The dashboard serves as a tool for analysts, investors, and decision-makers to evaluate sector trends, identify top-performing companies, and monitor trading activity.

## Dataset Overview

The dataset contains two key components:

### Company Information

| Column Name  | Description                              |
|--------------|------------------------------------------|
| CompanyID    | Unique company identifier                |
| CompanyName  | Official company name                    |
| Sector       | Market sector (e.g., Technology, Finance)|
| Country      | Country of registration or operation     |

### 📈 Stock Market Data

| Column Name   | Description                              |
|---------------|------------------------------------------|
| Open          | Opening stock price                      |
| Close         | Closing stock price                      |
| High          | Highest price in the day/session         |
| Low           | Lowest price in the day/session          |
| Transaction   | Number of individual trades              |
| UnitsSold     | Total units sold                         |
| Turnover      | Total revenue from trades                |

---

## Dashboard Features

The Power BI report includes:

### Map Visual
- Shows geographical spread of companies by country.

### Treemap
- Sector-wise distribution of companies.
- 
### 🧭 Gauge
- Visualize turnover vs a Target value.

### 🔘 Slicers
- Filter by:
  - Sector
  - Country
  - Company Name

---

## Data Quality & Cleaning

- Removed duplicates based on `CompanyID`.
- Filled missing values in `Sector` with `"No Data"`.
- Validated numerical fields (stock prices and turnover) for formatting and data types.

## Author

Name - Pranay Sontakke

LinkedIn - https://www.linkedin.com/in/pranay-sontakke/

GitHub - https://github.com/pranay0604

Email - sontakke0604@gmail.com

