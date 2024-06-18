# Uber_Data_Analysis
This project involves data analysis of various Uber datasets to derive insights on pickup trends in New York City. The analysis includes data preprocessing, cleaning, and visualizations to understand patterns such as the busiest months, days, and hours for Uber pickups, as well as geographic hotspots.
# Project Structure
## 1.Data Cleaning and Preprocessing: 
     Handled missing values, duplicate entries, and converted date fields to appropriate data types.
## 2.Exploratory Data Analysis (EDA): 
      Analyzed the data to identify trends and patterns.
## 3.Visualizations: 
     Created visual representations of the data using libraries such as matplotlib, seaborn, and plotly.
# Data Cleaning and Preprocessing
## 1.Loading Data:
 Loaded uber-raw-data-janjune-15_sample.csv and checked its shape.
 Identified and removed duplicate entries.
 Checked for and handled missing values.
## 2.Data Type Conversion:
  Converted Pickup_date from string to datetime format.
## 3.Feature Engineering:
  Extracted month, day, weekday, hour, and minute from the Pickup_date
# Analysis
## 1.Monthly Pickup Analysis:
     Added a month column and visualized the count of pickups for each month.
## 2.Weekly and Daily Analysis:
      Added weekday, day, and hour columns.
   Analyzed the number of pickups for each weekday and hour.
## 3.Base Number Analysis:
      Analyzed the number of active vehicles for each base number using Uber-Jan-Feb-FOIL.csv.
## 4.Geographic Analysis:
        Combined multiple datasets into a single DataFrame.
        Identified rush locations using latitude and longitude.
        Created heatmaps to visualize geographic hotspots.
 # Libraries Used
       pandas: Data manipulation and analysis.
       matplotlib: Plotting and visualization.
       seaborn: Statistical data visualization.
       plotly: Interactive visualizations.
       folium: Geographic data visualization.
  # Conclusion
This analysis provides valuable insights into Uber pickup patterns in New York City. The findings can be used to improve service efficiency and understand demand trends.
