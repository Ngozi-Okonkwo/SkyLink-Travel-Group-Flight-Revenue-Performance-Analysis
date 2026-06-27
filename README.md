# SkyLink-Travel-Group-Flight-Revenue-Performance-Analysis
Commercial intelligence dashboard analysing airline revenue, route performance, customer segments, and seasonal demand using Power BI.

# Executive Summary
This project analysed 10,000 flight booking records between 2018 and 2020 to provide commercial insights into airline performance, route profitability, customer behaviour, booking channels, and seasonal demand patterns. Using Power BI, Power Query, and DAX, the analysis transformed raw operational data into a six-page interactive dashboard that supports data-driven business decisions.

The study revealed that Southwest Airlines generated the highest revenue ($0.69M), while Lufthansa recorded the highest premium cabin adoption rate (54.79%), indicating a strong high-yield customer base despite lower booking volumes. International routes produced higher revenue per booking than domestic routes, and the Cheap Flights platform emerged as the most valuable booking channel, generating both the highest revenue and average ticket price. Seasonal analysis further showed that demand consistently peaked during the summer months, creating opportunities for dynamic pricing and targeted off-season promotions.

# Business Problem
SkyLink Travel Group required a commercial intelligence solution to understand the factors influencing airline revenue, route performance, traveller behaviour, booking channel effectiveness, and seasonal demand patterns. The goal was to identify high-value opportunities that could inform partnership strategies, route investments, and revenue optimisation initiatives.

# Project Objectives
The project aimed to answer the following business questions:

1.   Which airlines contribute the most revenue and command the highest ticket prices?
1.   Which routes deliver the strongest combination of demand and profitability?
1.   Which booking channels attract the most valuable customers?
1.   How does revenue vary across seat classes, trip types, and travel purposes?
1.   What seasonal patterns influence bookings and revenue?
1.   Which traveller segments are more likely to choose premium cabins?
1.   Which routes underperform despite strong demand?
1.   Which airlines and routes deserve greater commercial investment?

# Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modelling and
- Data Visualization 

# Dataset Overview
The dataset contained 10,000 flight booking records spanning January 2018 to January 2020 and included:

- 22 airlines

- 15 origin airports

- Multiple domestic and international routes

- Booking agencies and sales channels

- Traveller demographics and travel purposes

- Seat classes and trip types

- Ticket prices and travel dates

# Key metrics included:

- Total Revenue: $8.37M

- Average Ticket Price: $837

- Total Bookings: 10,000

- Return Trip Rate: 49.60%

- Premium Cabin Rate: 50.59%

# Methodology
The project followed a business-driven analytical approach consisting of four stages:

### Business Understanding
The analysis began by defining key business questions that would guide dashboard development and ensure that every visual contributed to actionable commercial insights.

### Data Preparation
- Power Query was used to clean and transform the dataset. Key activities included:

- Standardising airline names to remove duplicate spellings and abbreviations

- Trimming hidden whitespaces and cleaning text fields

- Correcting swapped airport codes and city names using three-character airport code validation

- Validating blank return dates as legitimate one-way journeys

- Retaining 74 blank destination states after confirming they represented international destinations

### Additional calculated fields were created, including:

- Route

- Route Code

- Trip Scope (Domestic vs International)

- Seat Tier (Standard vs Premium)

- Trip Type Labels

# Data Modelling and DAX
A simple model was implemented using a single fact table supported by a dedicated Date table for time intelligence analysis.

Custom DAX measures were developed to calculate:

- Total Revenue

- Average Ticket Price

- Total Bookings

- Premium Cabin Rate

- Return Trip Rate

- Revenue per Booking

- Airport Revenue Rankings

- Month-on-Month Revenue Trends

- Booking Growth Indicators

## Dashboard Development
The final solution was designed as a six-page interactive dashboard comprising:

1.  Home Page
2.  Executive Summary
3.  Airline & Channel Performance
4.  Route Intelligence
5.  Revenue Deep Dive
6.  Insights & Recommendations

# Key Findings
## Airline Performance
- Southwest Airlines generated the highest revenue at $0.69M, primarily through high booking volumes. Southwest, American Airlines, and Delta Air Lines collectively accounted for more than half of total network revenue.

- Lufthansa recorded the highest premium cabin adoption rate at 54.79%, demonstrating a strong high-value customer base despite lower route coverage.

## Booking Channels
- Cheap Flights emerged as the most valuable commercial partner, generating $0.41M in revenue and the highest average ticket price of $935 per booking, outperforming major competitors such as Expedia and Travelocity.

## Route Performance
- Domestic routes contributed 57.4% of total revenue through booking volume, while international routes generated higher revenue per booking, making them stronger yield opportunities.

- Atlanta–Mascot, SeaTac–Garhoud, and Denver–Haarlemmermeer were identified as the highest-performing routes.

## Customer Behaviour
- Business travellers generated the highest overall revenue, with Business Class corporate travellers forming the most valuable customer segment.

- One-way and return trips produced nearly identical revenue contributions, suggesting that pricing strategies have a greater impact on profitability than trip preferences.

## Seasonal Trends
- Revenue consistently peaked during summer months, particularly in June and July, while off-peak periods displayed greater volatility, highlighting opportunities for dynamic pricing and promotional campaigns.

# Business Recommendations
Based on the findings, the following recommendations were proposed:

1. Strengthen commercial partnerships with Southwest, American Airlines, and Delta Air Lines.
1. Expand Lufthansa's route coverage to leverage its strong premium customer base.
1. Increase investment in international routes due to their superior revenue per booking.
1. Prioritise corporate traveller retention through loyalty programmes and premium upgrade offers.
1. Introduce dynamic pricing strategies during off-peak periods to reduce seasonal volatility.
1. Negotiate stronger partnerships with Cheap Flights to protect a high-performing sales channel.

# Limitations
- The dataset covers January 2018 to January 2020, with only one month of data available for 2020.
- Additionally, 74 blank destination state values were retained as valid international records and excluded from state-level analyses.
