# Uber-Supply-Demand-Gap-Analysis

The purpose of this project is to analyze Uber ride request data and derive meaningful insights about:

- Passenger behavior

- Trip patterns

- Operational issues (e.g. ride cancellations, delays)

- Driver performance

- Demand trends (by time and location)

The analysis aims to assist operational teams in making better business and resource allocation decisions.



## Problem Statement

Title: Analyzing Ride Request Data to Improve Uber's Operational Efficiency

1) Ride Cancellations Trips often get cancelled when no drivers are nearby, especially during off-peak hours, leading to user dissatisfaction and lost revenue.

2) Peak Hour Delays During rush hours, a surge in ride requests combined with traffic congestion causes longer wait times and delayed pickups.

3) Demand Imbalance City areas have constant demand, while Airport demand is time-based. This mismatch leads to idle drivers in low-demand zones and shortages in high-demand areas.

## Data Wrangling
| Step                    | Purpose                                      |
| ----------------------- | -------------------------------------------- |
| Import Libraries        | Enable data handling and visualizations      |
| Load CSV                | Read raw ride data into Python               |
| Clean Columns           | Fix hidden formatting issues                 |
| Convert Timestamps      | Make time-based analysis possible            |
| Calculate Trip Duration | Analyze ride efficiency and detect anomalies |
| Filter Bad Data         | Improve data accuracy by removing noise      |
| Extract Hour            | Help visualize demand trends by time of day  |

## Data Visualizations 

This project used various visualizations to explore Uber’s supply-demand dynamics. Ride status plots revealed high cancellation rates during peak hours, indicating driver shortages. Pickup point charts showed consistent City demand and time-specific spikes at the Airport. Hourly request histograms identified morning and evening peaks, while trip duration plots showed most rides lasted 20–60 minutes. A driver activity chart highlighted that a few drivers handled most trips. Bar and violin plots compared hourly demand between locations, and a heatmap visualized ride volume by hour and pickup point, revealing key demand gaps and optimization opportunities.

## Data Analysis

The analysis revealed critical gaps in Uber’s operations. High cancellation rates were linked to low driver availability, especially during peak hours. Demand analysis showed clear spikes in the early morning and evening, aligning with office commute times. City pickups dominated overall demand, while the Airport experienced sharp, time-specific surges. Trip duration analysis confirmed most rides were short to medium in length, and driver data showed that a small group of drivers handled the majority of requests. Overall, the findings highlight the need for better driver allocation strategies to reduce cancellations and balance demand across time and location.


