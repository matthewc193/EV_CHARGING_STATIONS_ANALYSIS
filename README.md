# EV_CHARGING_STATIONS_ANALYSIS
This project investigates whether New Zealand’s electric vehicle (EV) charging infrastructure has kept pace with the growth of electric vehicles over recent years and whether charging stations are logically placed to meet demand. By integrating the Motor Vehicle Register and EV Roam Charging Stations datasets from data.govt.nz, the analysis compares trends in EV registrations against the expansion and geographic distribution of public charging stations nationwide.

This project implements a full end-to-end data pipeline, using Alteryx to ingest, clean, and reformat raw JSON data, and Snowflake as a data warehouse for data modeling and analytics. The data is imported into Power BI and delivers an interactive Power BI dashboard presenting key metrics such as EVs per charging connector, with the ability to filter by date and Territorial Local Authority (TLA). 

![Alt text for the image](Dashboard_Screenshot.png)




