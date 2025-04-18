# Root Cause Analysis & Hospitality Management Dashboard using Excel

![image](https://github.com/user-attachments/assets/cca961dc-cda3-4126-935b-273331cfa9ee)

## Table of Contents
- [Dataset Details](#dataset-details)
- [Project Goal](#project-goal)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Data Cleaning & Preparation](#data-cleaning--preparation)
  - [Descriptive Statistics](#descriptive-statistics)
  - [Visualization & Insights](#visualization--insights)
  - [Statistical Analysis](#statistical-analysis)
- [Overview](#overview)
  - [Listing Type Analysis](#listing-type-analysis)
  - [Recommendations](#recommendations)
- [Project Impact](#project-impact)

## Dataset Details
The dataset consists of resort booking records across multiple months, capturing key metrics like:
- Booking creation date
- Arrival date
- Cancellation status
- Average daily rate (ADR)
- Revenue and loss due to cancellations

## Project Goal
To minimize revenue losses during peak summer months (July & August) by identifying patterns in cancellations and recommending overbooking strategies.

## Exploratory Data Analysis

### Data Cleaning & Preparation
- Removed duplicates and null entries
- Converted date formats for booking and arrival
- Categorized bookings based on lead time: same-month (<30 days) and long-term (>30 days)

### Descriptive Statistics
- Found highest average daily rates and cancellation rates in July and August
- 39% cancellation rate observed in August
- 17% of bookings were made within 30 days of arrival

### Visualization & Insights
- High cancellation rates during peak months result in significant revenue loss (~$1M in 2016)
- Same-month bookings have only a 20% cancellation rate and a higher average daily rate ($191 vs $169)
- Most revenue loss is concentrated in July and August ($398K in July, $593K in August)

### Statistical Analysis
- Clear inverse relationship between booking lead time and cancellation rate
- Correlation between higher ADR and lower cancellation rate for same-month bookings

![image](https://github.com/user-attachments/assets/f54de3a0-0fc3-4b25-a362-1718dd9c2d5b)

## Overview

### Listing Type Analysis
- Bookings made >30 days in advance have a 38% cancellation rate
- Bookings made <30 days in advance have a 20% cancellation rate
- Average daily rate is higher for same-month bookings

### Recommendations
- Overbook July and August reservations to offset expected cancellations
- Prioritize accepting same-month reservations to reduce loss risk
- Optimize pricing for same-month bookings to capitalize on higher ADRs

## Project Impact
- Reduced the estimated revenue loss by building a predictive framework for overbooking
- Enabled more reliable revenue forecasting and informed decision-making during peak season
- Highlighted the importance of booking patterns on resort profitability

