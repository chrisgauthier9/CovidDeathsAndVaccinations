# READ ME

## **Overview**

This project delves into analyzing COVID-19 data spanning from January 26, 2020, to April 30, 2021. Using SQL techniques such as joins, common table expressions (CTEs), and aggregate functions, the project explores various aspects of the pandemic, including total cases, deaths, vaccination rates, and population percentages affected by COVID-19.

## **Data Sources**

1. [Our World in Data - COVID-19 Deaths](https://ourworldindata.org/covid-deaths)
    - The data is sourced from the World Health Organization (WHO) and includes confirmed cases and deaths reported by countries worldwide.

## **Data Description**

### CovidDeaths Table

- `iso_code`: ISO code of the country
- `continent`: Continent of the country
- `location`: Country name
- `date`: Date of observation
- `population`: Population of the country
- `total_cases`: Total confirmed cases of COVID-19
- `new_cases`: New confirmed cases reported on the date
- `new_cases_smoothed`: Smoothed new confirmed cases reported on the date
- `total_deaths`: Total deaths due to COVID-19
- `new_deaths`: New deaths reported on the date
- `new_deaths_smoothed`: Smoothed new deaths reported on the date
- Additional columns related to ICU patients, hospitalizations, etc.

### CovidVaccinations Table

- **`iso_code`**: ISO code of the country
- **`continent`**: Continent of the country
- **`location`**: Country name
- **`date`**: Date of observation
- **`new_tests`**: Number of new COVID-19 tests conducted on the date
- **`total_tests`**: Total number of COVID-19 tests conducted
- **`total_tests_per_thousand`**: Total number of COVID-19 tests conducted per thousand people
- **`new_tests_per_thousand`**: Number of new COVID-19 tests conducted per thousand people on the date
- **`new_tests_smoothed`**: Smoothed number of new COVID-19 tests conducted on the date
- Various other columns related to COVID-19 vaccinations, demographic information, and economic indicators.

## **Project Description**

The project entails extensive data exploration using SQL techniques to analyze COVID-19 data from January 26, 2020, to April 30, 2021. It follows these key stages:

1. **Data Exploration**: Employing SQL queries to delve into the COVID-19 datasets, focusing on understanding the data structure, identifying patterns, and extracting relevant insights. This involves querying various aspects of the data, including confirmed cases, deaths, vaccinations, population demographics, and economic indicators.
2. **Query Development**: Crafting SQL queries to perform a wide range of analyses, such as total cases vs. total deaths, percentage of the population infected with COVID-19, countries with the highest infection rates compared to population, countries with the highest death counts per population, and global COVID-19 statistics including new cases, deaths, and death percentages.
3. **Common Table Expressions (CTEs)**: Utilizing CTEs to streamline complex queries, facilitate data manipulation, and enhance query readability. This includes creating temporary tables to store intermediate results, performing calculations, and joining datasets to derive meaningful insights.
4. **Aggregate Functions**: Leveraging SQL aggregate functions such as SUM, COUNT, AVG, and MAX to calculate summary statistics and aggregate data across different dimensions. These functions enable the computation of key metrics such as total cases, total deaths, vaccination rates, and percentage of the population vaccinated.

## **Acknowledgments**

- The project is based on the tutorial provided by Alex The Analyst.
- Data is sourced from Our World in Data, relying on data from the World Health Organization (WHO).

Thank you for your interest in my project! If you have any questions or feedback, please feel free to contact me at [chrisgauthier@me.com](mailto:chrisgauthier@me.com).
