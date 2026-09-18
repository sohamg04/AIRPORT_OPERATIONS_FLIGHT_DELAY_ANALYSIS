# Airport Operations & Flight Delay Analytics

## Project Overview

An end to end data analytics project focused on analyzing flight operations delays cancellations and airport performance using Python Pandas SQL and Power BI.

## Business Problem

Flight delays and cancellations can affect airport operations and passenger experience. This project analyzes flight data to identify delay patterns operational trends and airport level performance.

## Dataset

The project uses flight operations data containing information related to:

- Flight schedules
- Departure and arrival delays
- Cancellation details
- Airline information
- Airport information
- Delay causes

The working dataset contains 10000 flight records across 31 attributes.

## Data Cleaning

The data was cleaned and prepared for analysis using Python and Pandas.

Key steps included:

- Handling missing values in delay cause columns
- Handling cancellation reason values
- Creating a delay indicator
- Creating delay severity categories
- Preparing the cleaned dataset for Power BI analysis

## Delay Classification

Flights were classified using departure delay values.

The analysis identified:

- 6248 flights as not delayed
- 3752 flights as delayed

Delayed flights were further categorized into:

- Minor
- Moderate
- Severe

The analysis identified:

- 2173 minor delays
- 1198 moderate delays
- 381 severe delays

## Cancellation Analysis

The project also analyzed flight cancellations and cancellation reasons.

Total cancellations identified:

- 392 cancelled flights
- 9608 non cancelled flights

## Power BI Dashboard

An interactive Power BI dashboard was developed to analyze flight operations and delay patterns.

Key dashboard analysis includes:

- Total Flights by Destination Airport
- Delay Rate by Destination Airport
- Delay Rate by Day of Week
- Flight Delay Analysis
- Cancellation Analysis
- Airport Performance

## Key Insights

- 3752 of the 10000 analyzed flights were classified as delayed
- Delay severity analysis showed differences between minor moderate and severe delays
- Destination airports were compared based on flight volume and delay rate
- Day of week analysis was used to identify variations in delay rates
- Flight cancellations were analyzed using cancellation status and reason

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
└── README.md
