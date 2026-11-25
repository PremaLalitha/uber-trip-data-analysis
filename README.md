# Uber Trip Data Analysis – NYC (April 2014)

## Project Overview

This project focuses on analyzing Uber pickup data in New York City during April 2014. The objective is to understand pickup demand patterns, identify peak hours, analyze weekday trends, and compare pickup activity across different Uber operating bases.

The project uses Python for data cleaning and exploratory data analysis and Power BI for interactive dashboard development.

## Objectives

- Analyze Uber pickup demand by hour.
- Identify daily and weekday pickup patterns.
- Understand pickup distribution across Uber operating bases.
- Explore geographical pickup locations.
- Identify peak-demand periods and high-activity areas.
- Build an interactive Power BI dashboard.

## Dataset

- **Dataset:** Uber NYC Pickup Data – April 2014
- **Source:** FiveThirtyEight
- **File:** `uber-raw-data-apr14.csv`
- **Initial records:** 564,516
- **Records after duplicate removal:** 556,767

### Dataset Columns

| Column | Description |
|---|---|
| Date/Time | Date and time of pickup |
| Lat | Pickup latitude |
| Lon | Pickup longitude |
| Base | Uber operating base code |

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI Desktop

## Project Workflow

1. Data collection and loading.
2. Data inspection and understanding.
3. Missing-value and duplicate checking.
4. Data cleaning and duplicate removal.
5. Date and time conversion.
6. Feature engineering – Hour, Day, Month and DayOfWeek.
7. Exploratory data analysis and visualization.
8. Exporting the cleaned dataset.
9. Creating interactive dashboards using Power BI.

## Power BI Dashboard

### Page 1 – Uber Trip Analysis: NYC Pickup Overview

The overview dashboard contains:
- Total Uber pickups
- Total Uber operating bases
- Total pickup days
- Hourly pickup demand
- Daily pickup trend
- Weekday-hour demand heatmap
- Geographical pickup distribution
- Weekday pickup comparison
- Pickup distribution by Uber base

### Page 2 – Uber Pickup: Advanced Analysis

The advanced dashboard contains:
- Hourly pickup demand by Uber operating base
- Daily pickup demand by Uber operating base
- Uber pickup contribution by operating base
- Interactive Base and Hour slicers

## Key Observations

- Pickup activity is higher during the evening hours, particularly around 5 PM to 7 PM.
- Wednesday shows the highest pickup volume among the weekdays in the dashboard.
- Sunday shows the lowest pickup volume among the weekdays.
- Operating bases B02682 and B02598 contribute the largest shares of pickups.
- Pickup locations are heavily concentrated around New York City.

## How to Run the Project

1. Clone or download this repository.
2. Install Python.
3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Place the original dataset inside the `dataset` folder.
5. Open the Jupyter Notebook inside the `notebooks` folder.
6. Run the notebook cells sequentially.
7. Open the Power BI report to explore the interactive dashboards.

## Limitations

The dataset contains pickup date and time, pickup coordinates, and Uber operating base information. It does not contain drop-off locations, fares, trip duration, or passenger counts. Therefore, this project focuses only on pickup-demand analysis.

## Author

Developed as a Data Analytics portfolio project using Python and Power BI.
