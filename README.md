# Wind-Energy-Forecasting

## Project Description:
This project aims to develop a system for predicting surplus renewable energy availability (wind) at least 24 hours in advance. The purpose is to enable a company to offer free energy to local clients when there is an excess of renewable energy in their area. The system will help mitigate costs by avoiding false positives, where free energy is offered unnecessarily.

## Dataset:
- We have total 24 years of dataset from 2010 - 2024 having 196 files.
- We have considered only 10 years of data from 2014 - 2024.

## Model:
Decision Tree Regressor

## How to run:
- Open the DataExploration.ipynb file.
- Run each cell one by one.
- Same for Modelling.ipynb file.

## Assumptions:
We will be considering only wind power as UK is known for the one of the best location for wind power in the world.
We are assuming we have 500 household that can take advantage of surplus energy.
### Considering

- 200 household of flat or 1 bedroom = 1800 kWH per year
- 150 household of 2-3 bedrooms = 2700 kWH per year
- 150 household of 4-5 bedrooms = 4100 kWH per year
Average electricity consumption of household
	Average KW consumed per hour = 157.53 KW (Total consumption)

## References: 
	https://en.wikipedia.org/wiki/Wind_power_in_the_United_Kingdom
	https://www.geeksforgeeks.org/wind-energy-formula/
	https://www.ofgem.gov.uk/information-consumers/energy-advice-households/average-gas-and-electricity-use-explained