# Uber_Trip_Analysis_BI_Dashboard

# Uber Trip Analysis - Power BI Dashboard

## Overview

The Uber Trip Analysis Dashboard is designed to provide in-depth insights into Uber trip data using Power BI. This project leverages a dataset containing 100,000+ rows of trip details and location information to help stakeholders understand trends in booking, revenue, trip efficiency, and demand distribution.

## Dataset Information

### Trip Details Table (11 Columns):
- **Pickup Time** – Timestamp of when the trip started
- **Drop Off Time** – Timestamp of when the trip ended
- **passenger_count** – Number of passengers in the trip
- **trip_distance** – Distance covered in the trip
- **PULocationID** – Pickup location ID
- **DOLocationID** – Drop-off location ID
- **fare_amount** – Base fare charged for the trip
- **Surge Fee** – Additional charges applied during high demand
- **Vehicle** – Type of vehicle used for the trip
- **Payment_type** – Mode of payment (Card, Cash, Wallet, etc.)

### Location Table (3 Columns):
- **LocationID** – Unique identifier for each location
- **Location** – Name of the location
- **City** – City corresponding to the location

## Business Requirements

### Uber Trip Analysis

The objective of this project is to analyze Uber trip data using Power BI and extract meaningful insights for decision-making. The dashboard is designed to help stakeholders optimize ride efficiency, enhance pricing strategies, and improve customer satisfaction.

## Key Performance Indicators (KPIs)

- **Total Bookings** – Count of trips booked over a given period.
- **Total Booking Value** – Total revenue generated from all trips.
- **Average Booking Value** – Average revenue per trip.
- **Total Trip Distance** – Total distance covered by all trips.
- **Average Trip Distance** – Average distance per trip.
- **Average Trip Time** – Average duration of trips.

## Expected Outcomes

✔ Identify trends in ride bookings and revenue generation.  
✔ Analyze trip efficiency based on distance and duration.  
✔ Compare booking values and trip patterns across different time periods.  
✔ Provide insights to optimize pricing models and improve customer experience.  

# Dashboard 1: Overview Analysis

## Visualizations & Insights

### Measure Selector

A disconnected table is used to create a dynamic measure selector for:
- **Total Bookings**
- **Total Booking Value**
- **Total Trip Distance**

Allows users to switch between key metrics interactively.

### Bookings Analysis by Payment Type
Breakdown of bookings based on payment methods (Card, Cash, Wallet, etc.)

### Trip Type Analysis (Day/Night)
Identifies variations in bookings based on time of the day.

### Vehicle Type Analysis
Grid table displaying KPIs (**Total Bookings, Total Booking Value, Avg Booking Value, Total Trip Distance**) across different vehicle types.  
Conditional formatting applied for better insights.

### Total Bookings by Day
Detects daily booking trends to identify peak and off-peak periods.  
Helps understand the impact of external factors (holidays, events, weather) on demand.

### Location Analysis
- **Most Frequent Pickup & Drop-off Points** – Identifies common starting and ending locations for trips. Optimizes driver availability and dynamic pricing.
- **Farthest Trip Analysis** – Determines the longest trip based on distance traveled. Useful for analyzing outlier trips and fare optimization.
- **Total Bookings by Location (Top 5)** – Identifies high-demand areas for better resource allocation.
- **Most Preferred Vehicle for Pickup Locations** – Determines vehicle type preferences at various pickup points.

### Additional Features
- **Dynamic Title** – Updates chart titles based on selected measure.
- **Slicers** – Interactive filters for Date, City, etc.
- **Tooltips** – Shows additional details like Average Booking Value or Trip Distance.
- **Bookmarks** – Includes:
  - "Data Details" Bookmark: Displays key metric definitions and dataset overview.
  - "Clear Filters" Button: Resets all selections instantly.
  - "Download Data" Button: Exports raw data to CSV/Excel using Power Automate.

# Dashboard 2: Time Analysis

## Objective
Understanding trip demand patterns based on time intervals to optimize operations and pricing.

## Visualizations

### Measure Selector
Allows selection of:
- **Total Bookings**
- **Total Booking Value**
- **Total Trip Distance**

Updates all charts dynamically.

### Pickup Time Analysis (10-Minute Intervals)
Area chart groups trip bookings into 10-minute intervals.  
Identifies peak and off-peak demand periods.

### Day-wise Trends
Line chart shows booking trends across Monday to Sunday.  
Helps compare weekday vs. weekend demand.

### Hour & Day Heatmap
- **Rows:** Hours of the Day (0–23)  
- **Columns:** Days of the Week (Mon-Sun)  
- **Values:** Selected KPI (e.g., Total Bookings)  

Highlights peak demand hours.

# Dashboard 3: Details Tab

## Features

### Grid Table with Key Fields
Displays essential trip details.

### Drill-Through Functionality
Users can right-click on data points in other dashboards and drill through to view detailed records.

### Bookmark for Full Data View
"View Full Data" toggle allows switching between filtered drill-through data and the complete dataset.

# Implementation Enhancements

## Power BI Features Used:
- Disconnected Table for Measure Selector
- Dynamic Titles
- Conditional Formatting
- Bookmarks & Buttons
- Power Automate for Data Export
- Interactive Slicers & Tooltips
- Inactive Relationship Activation for Location Analysis

## User Experience Enhancements:
- "Clear Filters" Button for quick resets.
- "Download Data" Button to export raw data.
- "Data Details" Bookmark for metric definitions and data insights.

# Conclusion

This Power BI Uber Trip Analysis dashboard provides a comprehensive view of ride trends, revenue insights, and demand forecasting. It helps stakeholders make data-driven decisions to optimize pricing strategies, improve trip efficiency, and enhance customer experience.

# How to Use This Repository

## Clone the Repository
```sh
git clone https://github.com/yourusername/Uber-Trip-Analysis.git
```

## Open Power BI and load the .pbix file.

## Explore the Dashboards using the interactive filters, charts, and tables.

## Customize & Extend by adding new measures, filters, or integrating additional datasets.

# Contact & Contributions

**Author:**Vaibhav Anand 
**Email:** anandvaibhav02@gmail.com  
 
Feel free to contribute, report issues, or suggest improvements! 🚀

