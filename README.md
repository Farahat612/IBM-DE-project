# Bank Market Data Extraction and ETL Project
This is a Data Engineering project that's part of IBM Data Engineering certificate through Coursera.

## Overview

This Python project demonstrates a basic Extract, Transform, Load (ETL) process for collecting bank and market capitalization data, extracting exchange rates using an API, and transforming and loading the data into a structured format.

## Project Description #Scenario

For this project, you will assume the role of data engineer working for an international financial analysis company. Your company tracks stock prices, commodities, forex rates, inflation rates. Your job is to extract financial data from various sources like websites, APIs and files provided by various financial analysis firms. After you collect the data, you extract the data of interest to your company and transform it based on the requirements given to you. Once the transformation is complete you load that data into a database.


## Tasks

### Task 01: Web Scraping
- Collects data about the largest banks in the world from a Wikipedia page.
- Utilizes the BeautifulSoup library for web scraping.
- Stores the extracted data in a Pandas DataFrame.

### Task 02: Extract API Data
- Retrieves currency exchange rate data from the ExchangeRate-API.
- Loads the data into a Pandas DataFrame and saves it as a CSV file.
- Demonstrates the use of the `requests` library for API calls.

### Task 03: ETL (Extract, Transform, Load)
- Combines the bank and market cap data extracted in Task 01.
- Transforms the market capitalization currency using the exchange rate data from Task 02.
- Loads the transformed data into a separate CSV file.
- Follows the ETL process to clean and structure the data.

## Project Structure

- `Task01_Web_Scraping.ipynb`: Jupyter Notebook containing the web scraping code.
- `Task02_Extract_API_Data.ipynb`: Jupyter Notebook for extracting API data.
- `Task03_ETL.ipynb`: Jupyter Notebook for the ETL process.
- `datasets/`: Directory containing data files.
   - `exchange_rates.csv`: CSV file containing exchange rate data.
   - `bank_market_cap_*.json`: JSON files containing bank and market cap data.

## Setup and Usage

To run this project, follow these steps:

1. Clone the repository to your local machine.

2. Install the required Python libraries:
  ```bash
   pip install pandas requests
  ```

3. Execute the Jupyter Notebooks in the following order:
  •	Task01_Web_Scraping.ipynb
  •	Task02_Extract_API_Data.ipynb
  •	Task03_ETL.ipynb

4. Follow the instructions within each notebook to complete each task.



## Contributing
Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please create a GitHub issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

