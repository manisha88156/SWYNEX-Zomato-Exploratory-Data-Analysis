# Zomato Delivery Data — Exploratory Data Analysis (EDA)

## Project Overview
This project explores Zomato delivery data to identify patterns and factors associated with food delivery time.
It was completed as Task 2 of my Data Analyst internship at SWYNEX Technologies Pvt. Ltd.

## Objectives
- Calculate important descriptive statistics.
- Analyze delivery time by weather, traffic, vehicle type, vehicle condition, festival status, and city category.
- Identify trends, patterns, and potential data-quality issues.
- Translate the analysis into useful business insights.

## Tools and Technologies
- SQL
- DuckDB
- Python
- Pandas
- Google Colab
- Data visualization

## Key Findings
1. **Traffic:** Average delivery time was 31.18 minutes in Jam traffic versus 21.27 minutes in Low traffic.
2. **Weather:** Average delivery time was 28.92 minutes in Cloudy weather versus 21.86 minutes in Sunny weather.
3. **Festival impact:** Orders marked Festival = Yes had an average delivery time of 45.52 minutes, compared with
    25.98 minutes for Festival = No.
5. **Vehicle condition:** Records with vehicle-condition code 0 had an average delivery time of 30.07 minutes.
   The meaning of the code should be verified before interpreting it.
7. **City category:** Metropolitian accounted for 34,087 of the 45,584 records.

## Dataset
The analysis uses the cleaned Zomato delivery dataset prepared for Task 1.

[View the Task 1 data-cleaning repository](https://github.com/manisha88156/SWYNEX-Data-Cleaning-Preparation)

## How to Run
1. Open the notebook `SWYNEX_Task_2_Exploratory_Data_Analysis.ipynb` in Google Colab.
2. Upload the cleaned CSV dataset when prompted, or update the notebook's file path to match the uploaded dataset.
3. Run the notebook cells in order.

## Limitations
- Some weather, traffic, festival, and city values are unknown or missing.
- Observed differences show associations and do not, by themselves, establish causation.
- Monthly order counts may be affected by uneven data coverage.

## Deliverable
The notebook contains the SQL-based analysis, summary results, visualizations, and business insights.

**Internship:** Data Analyst — SWYNEX Technologies Pvt. Ltd.
