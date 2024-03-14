# Covid Deaths and Vaccinations

# READ ME

## Project Links

> Tutorial: Alex The Analyst - COVID-19 SQL Tutorial
> 

## **Overview**

This project focuses on exploring COVID-19 data spanning from January 26, 2020, to April 30, 2021. It employs various SQL techniques such as joins, common table expressions (CTEs), aggregate functions, and converting data types.

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

This project aims to explore COVID-19 data using SQL queries to extract insights such as:

- Total cases vs. total deaths
- Percentage of population infected with COVID-19
- Countries with the highest infection rates compared to population
- Countries with the highest death counts per population
- Global COVID-19 statistics including new cases, deaths, and death percentages
- Percentage of population vaccinated against COVID-19

## **Acknowledgments**

- The project is based on the tutorial provided by Alex The Analyst.
- Data is sourced from Our World in Data, relying on data from the World Health Organization (WHO).

Thank you for your interest in my project! If you have any questions or feedback, please feel free to contact me at [chrisgauthier@me.com](mailto:chrisgauthier@me.com).
