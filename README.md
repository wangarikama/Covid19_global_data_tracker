# COVID-19 Data Analysis
This project analyzes COVID-19 trends using the Our World in Data COVID-19 dataset.
It allows users to select a country and view case and death trends over a chosen date range.

# Objectives
Load and explore COVID-19 data.

Allow user selection of country and date range.

Visualize COVID-19 cases and deaths.

Identify patterns and trends in the data.

# Tools and Libraries
Python 3

pandas for data loading and manipulation.

matplotlib for plotting.

(Optional) Jupyter Notebook for development.

# Dataset
Source: Our World in Data
Sample of available columns:

iso_code – Country code.

continent – Continent name.

location – Country name.

date – Date of record.

total_cases, new_cases, total_deaths, new_deaths – Key COVID-19 metrics.

total_tests, people_vaccinated, total_boosters – Testing and vaccination data.

population, gdp_per_capita, life_expectancy – Demographic and economic indicators.

The dataset contains 67 columns in total.

# How to Run
1. Clone or download this repository.

2. Place the dataset owid-covid-data.csv in the project folder.

3. Install dependencies:

pip install -r requirements.txt
4. Run the script:

python covid_analysis.py
5. Enter your preferred country and date range when prompted.

# Insights
COVID-19 cases and deaths follow waves in most countries.

Vaccination rates correlate with reduced severe cases and deaths.

Testing levels vary widely across countries.

