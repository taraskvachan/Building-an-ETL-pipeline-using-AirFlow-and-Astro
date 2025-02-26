# Building an ETL pipeline using AirFlow and Astro

## Project Description

This project is an ETL pipeline built using Apache Airflow. It automates the process of fetching weather data from the Open-Meteo API, transforming it, and loading it into a PostgreSQL database.

Airflow Hooks:
<ul>
<li>HttpHook: Used to fetch data from Open-Meteo API</li>
<li>PostgresHook: Handles database interactions</li>
</ul>

Airflow Tasks:
<ul>
<li>extract_weather_data(): Calls the API and retrieves weather data</li>
<li>transform_weather_data(): Parses and restructures the relevant data fields</li>
<li>load_weather_data(): Inserts the transformed data into a PostgreSQL table</li>
</ul>

## Graf

![1](https://github.com/user-attachments/assets/b2a1f615-803c-48c6-9a09-d3a8f73e78d5)
