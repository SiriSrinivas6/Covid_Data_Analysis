# Covid_Data_Analysis

This SQL project analyzes COVID-19 data focusing on deaths and vaccinations.

### Data Source
The data for this project was sourced from an Excel file containing information on COVID-19 cases, deaths, vaccinations, population, and continent details. The Excel file was obtained from a reliable source such as the World Health Organization (WHO) or the Centers for Disease Control and Prevention (CDC).

[DEATHS](https://github.com/SiriSrinivas6/Covid_Data_Analysis/blob/f760736f09d10666779125b8d019bedf60b61645/CovidDeaths.xlsx)
[VACCINATIONS](https://github.com/SiriSrinivas6/Covid_Data_Analysis/blob/a027c56baa96aaa0ad1c0dd5cb91d9208de46f0e/CovidVaccinations.xlsx)

### Importing Data
Before performing any analysis, the data from the Excel file was imported into the SQL database. This process involved converting the Excel file into a format compatible with the database management system (DBMS) being used (e.g., CSV format) and then using SQL commands or a database management tool to import the data into the appropriate tables.

### Database Schema
The data was structured in the SQL database according to a predefined schema that accurately represents the various attributes and relationships present in the dataset. The schema was designed to facilitate efficient querying and analysis of the COVID-19 data.



## Selecting Data

For this project, we retrieved data from a reliable source such as the World Health Organization (WHO) or the Centers for Disease Control and Prevention (CDC). The dataset includes information on COVID-19 cases, deaths, vaccinations, population, and continent details. The data is structured in a way that allows us to perform various analyses and gain insights into the impact of COVID-19 across different regions.

## Total Cases vs Total Deaths

To analyze the likelihood of dying if contracting COVID-19 in a specific country, we compared the total number of confirmed cases with the total number of deaths. This comparison provides valuable insights into the severity of the outbreak in different countries and helps in understanding the fatality rate.

## Total Cases vs Population

By comparing the total number of COVID-19 cases with the population of each country, we calculated the percentage of the population that contracted COVID-19. This analysis helps in understanding the spread of the virus and its impact relative to the population size.

## Countries with Highest Infection Rate Compared to Population

We identified countries with the highest infection rates relative to their population size by calculating the ratio of total cases to population. This analysis helps in identifying regions that have been disproportionately affected by the pandemic.

## Countries with Highest Death Count per Population

To identify countries with the highest death counts per population, we calculated the ratio of total deaths to population. This analysis helps in understanding the mortality rate and the impact of COVID-19 on different populations.

## Breakdown by Continent

We analyzed COVID-19 data at the continent level to identify continents with the highest death counts per population. This breakdown helps in understanding regional variations in the impact of the pandemic and facilitates targeted interventions.

## Global Numbers

We provided an overview of global COVID-19 statistics, including total cases, total deaths, vaccination coverage, and other relevant metrics. This summary helps in understanding the overall impact of the pandemic on a global scale.
![Image](https://github.com/SiriSrinivas6/Covid_Data_Analysis/blob/fbfec37b901e79b956ef94968caae4a231d59052/Screenshots/1.png)

## Total Population vs Vaccinations

By comparing the total population with vaccination statistics, we assessed the coverage and progress of COVID-19 vaccination campaigns. This analysis helps in monitoring vaccination efforts and identifying areas that may need additional support.
![image]()

## Using Common Table Expressions (CTE)

We utilized Common Table Expressions (CTEs) to organize and simplify complex queries. CTEs allowed us to break down the analysis into smaller, more manageable steps and improve the readability of our SQL code.

## Temporary Table

Temporary tables were used to store intermediate results during analysis. By storing intermediate results in temporary tables, we were able to optimize performance and streamline the execution of complex queries.

## Filtering by Continent

We filtered the data to focus only on continents with available information, such as Africa, Asia, Europe, North America, South America, and Oceania. The data was ordered by specific criteria to facilitate meaningful comparisons and insights.

## Creating a View for Visualizations

A view was created to store pre-processed data for easier access and visualization purposes. This view encapsulates the results of our analysis and can be queried directly to generate visualizations or further analyze the data.
