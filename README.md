# Covid-19-Exploration

## Overview  
This repository focuses on exploring and analyzing COVID-19 data using SQL queries. The data manipulation and analysis leverage various SQL techniques, including joins, CTEs (Common Table Expressions), temp tables, window functions, aggregate functions, and the creation of views.  

## Initial Data Selection  
The project starts by selecting relevant data from the "PortfolioProject..CovidDeaths" table, filtering out records where the continent is not specified, and organizing the results by location and date.  

## Key Analyses  
Likelihood of Death by Country  
The analysis compares total cases to total deaths in specific countries, calculating and presenting the percentage likelihood of death if one contracts COVID-19.  

## Population Infection Percentage  
This analysis illustrates the percentage of a population infected with COVID-19 over time in various locations.  

## Infection Rate vs. Population  
Identifying countries with the highest infection rates relative to their populations, this query calculates the percentage of the population infected and presents the corresponding numbers.  

## Death Count per Population  
This query identifies countries with the highest death count per population, showcasing the severity of the impact of COVID-19 in different regions.  

## Continent-Level Analysis  
Breaking down the data by continent, the project identifies continents with the highest death counts per population, providing insights into the regional impact of the pandemic.  

## Global Numbers  
An analysis of global COVID-19 numbers is performed, presenting the total cases, total deaths, and the percentage of deaths relative to new cases.  

## Vaccination Analysis  
The project explores the relationship between total population and COVID-19 vaccinations, including the percentage of the population that has received at least one vaccine dose. Different approaches, such as using CTEs and temp tables, are employed for this analysis.  

## View Creation  
A view named "PercentPopulationVaccinated" is created to store processed data for potential use in later visualizations or further analyses.  


