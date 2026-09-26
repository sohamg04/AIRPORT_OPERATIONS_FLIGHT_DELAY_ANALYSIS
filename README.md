# Airport Operations & Flight Delay Analytics

## Project Overview

An end to end data analytics project focused on analyzing flight operations delays cancellations airline performance and airport activity using Python Pandas SQL and Power BI.

## Business Problem

Flight delays and cancellations can affect airline operations and passenger experience. This project analyzes flight data to identify delay patterns major delay causes airline performance and operational trends.

## Dataset

The project uses flight operations data containing information related to:

- Flight schedules
- Departure delays
- Arrival delays
- Cancellation details
- Airlines
- Airports
- Delay causes

The working dataset contains 10000 flight records across 31 attributes.

## Data Cleaning

The data was prepared using Python and Pandas.

Key steps included:

- Handling missing values in delay cause columns
- Handling cancellation reason values
- Creating a delay indicator
- Creating delay severity categories
- Preparing the cleaned dataset for Power BI analysis

## Delay Analysis

The analysis identified:

- 10000 total flights
- 3752 delayed flights
- 37.52% delay rate
- 392 cancelled flights
- 7.35 average departure delay

Delayed flights were further categorized into:

- Minor
- Moderate
- Severe

## Power BI Dashboard

An interactive Power BI dashboard was developed to analyze flight operations and delay performance.

### Dashboard KPIs

- Total Flights
- Delayed Flights
- Delay Rate
- Cancelled Flights
- Average Departure Delay

### Dashboard Visuals

- Delay Rate by Airline
- Total Delay Minutes by Cause
- Top 10 Airlines by Total Delay
- Total Flights by Origin Airport
- Delay Rate by Time Period
- Delay Rate by Route

## Key Analysis

The dashboard allows analysis of:

- Airline level delay performance
- Major causes of flight delays
- Airlines with the highest total delay minutes
- Flight volume across origin airports
- Delay rates across different time periods
- Route level delay performance

## Dashboard Preview

![Airport Operations & Flight Delay Analytics](airport-delay-dashboard.png)

## Technologies Used

- Python
- Pandas
- SQL
- Power BI
- DAX
- Excel

## Project Structure

```text
airport-operations-flight-delay-analytics
│
├── airlines.csv
├── airports.csv
├── flights-compressed.csv
├── flights_clean_powerbi.csv
├── airport-delay-dashboard.png
└── README.md
