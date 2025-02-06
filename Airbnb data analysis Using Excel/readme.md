# Airbnb Data Analysis and Dashboard making using Excel

Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking.  

## Table of Contents

- [Data Set Details](#data Set Details)
- [Project Goal](#project Goal)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Data Cleaning & Preparation](#Data Cleaning & Preparation)
  - [Descriptive Statistics](#Descriptive Statistics)
  - [Visualization & Insights](#Visualization & Insights)
  - [Statistical Analysis](#Statistical Analysis)

- [Overview](#Overview)
   pic()
  - [Listing type Analysis ](#Listing type Analysis )
  - [Recommendations](#Recommendations)
- [Project Impact](#Project Impact) 
  

##Data Set Details

```Excel
-- Variables Names and Descriptions are:

	City: Name of the City
	Price: Price of Airbnb
	Day: If it is a weekday or weekend
	Room Type: Type or Airbnb - Entire Apt, Private Room, Shared Room
	Share Room: If the Room in Airbnb is shared by anyone
	Private Room: If the Stay has a Private room available
	Person Capacity: The Person Capacity of Airbnb
	Superhost: If the Airbnb host is a Superhost or not
	Multiple Rooms: If the Airbnb has multiple rooms (2-4) rooms
	Business: If the Business has more than 4 offers
	Cleaningness Rating: Cleanness Ratings of the Places
	Guest Satisfaction: Guest Satisfaction Score they left
	Bedrooms: Number of Bedrooms in the facility
	City Center (km): Distance to the center of the City from the staying place
	Metro Distance (km): Distance to the Metro Service from the staying place
	Attraction Index: Attraction Index of the Place
	Normalized Attraction Index: Normalised value of the Attraction Index
	Restaurant Index: Restaurant Index of the Place
	Normalized Restaurant Index: Normalised value of the Restaurant Index



## Project Goal
``` Performing Exploratory Data Analysis using Microsoft Excel and Telling a Story using a Dashboard with this dataset i.e. Building a Simple Dashboard using Excel. Also, Performing Statistical Analysis to find the determinants and associations between variables.
```


## Exploratory Data Analysis
In this project, we conducted Exploratory Data Analysis (EDA) using Microsoft Excel to understand key patterns and trends in Airbnb bookings across nine major European cities. The dataset includes various attributes such as price, room type, guest satisfaction, location proximity, and attraction indices.

#EDA Process:
##Data Cleaning & Preparation:

Checked for missing values and handled inconsistencies.
Standardized variable formats and ensured data accuracy.
picute (())

##Descriptive Statistics:

Calculated mean, median, and standard deviation for numerical variables (e.g., price, satisfaction score).
Summarized categorical variables such as room type distribution.
picture(())

##Visualization & Insights:

Used PivotTables and Charts to analyze pricing trends based on room type and city.
Created a heatmap for guest satisfaction vs. cleanliness rating.
Analyzed distance metrics (City Center & Metro) and their impact on price & guest satisfaction.
Compared attraction index and restaurant index across cities.

##Statistical Analysis:

Identified correlations between price, location, and guest satisfaction.
Analyzed the effect of Superhost status on guest ratings.
Examined whether weekend vs. weekday stays impact pricing.
Dashboard Creation:

Designed an interactive Excel dashboard summarizing key insights.
Included visual KPIs such as average pricing, best-rated cities, and room-type distribution.
Added slicers for dynamic filtering by city, room type, and business status.

### Overview
''' Project visual Overview '''


### Listing type Analysis 
```sql
-- Creating a view for RFM segmentation based on Recency (R), Frequency (F), and Monetary (M) scores

### Recommendations


## Project Impact
The RFM analysis has yielded valuable insights into customer behavior and preferences, guiding effective business strategies. The segmentation highlights:

**Growth Potential:** "New Customers" present growth opportunities, warranting targeted engagement efforts.

**Retention Focus:** Addressing "Potential Churners" minimizes attrition risk and encourages loyalty.

**Re-engagement Strategies:** Targeting "Lost Customers" with incentives can revive interest.

**Engaged Base:** "Active" customers respond well to loyalty programs and tailored content.

**High-Value Attention:** Strategies for "Slipping Away, Cannot Lose" group prevent loss of top spenders.

**Loyalty Recognition:** Rewarding "Loyal" customers deepens brand loyalty.

This analysis drives personalized strategies, optimizing engagement, retention, and revenue. Continuous adaptation based on real-time data is crucial for sustained success.
