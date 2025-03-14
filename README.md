# NYC Bike-Sharing Analytics 🚲

## Overview
This project provides an **interactive analysis** of NYC's bike-sharing system using **R and Shiny**. It explores key insights on **trip duration, rental patterns, peak usage hours, and station preferences**. The dashboard enables users to filter data dynamically and visualize trends in bike-sharing behavior.

## Features 🚀
- **Trip Duration Analysis** – Compare ride times across gender, age groups, and seasons.
- **Usage Patterns** – Discover peak rental hours and usage trends.
- **Rental Trends** – Analyze how different user types (subscribers vs. occasional users) interact with the bike-sharing system.
- **Station Preferences** – Visualize preferred start and end locations using an interactive map.
- **Dynamic Filtering** – Adjust views based on selected demographics, seasons, or time of day.

## Data Sources 📊
The dataset used in this project comes from the **NYC Citi Bike program**, which provides anonymized trip data including:
- **Trip duration** (start and end times, total ride time)
- **User demographics** (gender, age group, subscription type)
- **Station details** (start and end locations)
- **Seasonal and hourly trends**

## Technologies Used 🛠️
- **R & Shiny** – For interactive dashboard development
- **ggplot2 & plotly** – Data visualization
- **dplyr & tidyr** – Data wrangling and preprocessing
- **leaflet** – Interactive mapping of bike stations

## Project Structure 📂
```
📁 NYC-Bike-Analytics
│-- 📜 data_prep.R            # Data preprocessing and cleaning
│-- 📜 plot_prep.R            # Visualization functions
│-- 📜 read_libraries.R       # Required libraries
│-- 📜 read_preped_data.R     # Load and filter processed data
│-- 📜 shiny_app.R            # Main Shiny dashboard script
│-- 📜 README.md              # Project documentation
```

## Key Insights 🔎
- **Morning and evening peaks** suggest bike-sharing is widely used for commuting.
- **Males rent bikes more frequently than females**, but females tend to have longer ride durations.
- **Autumn and summer have the highest rental activity**, while spring sees the lowest usage.
- **Subscribers dominate rentals**, while occasional users take longer rides.
- **Age group 20-30 is the most active**, with bike usage declining for older demographics.


## License 📄
This project is licensed under the **MIT License** – see the `LICENSE` file for details.


