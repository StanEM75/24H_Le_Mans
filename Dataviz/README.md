# 24 Hours Le Mans - Pre-Processing & DataViz

![Project Image](https://www.lifeventsgroup.com/images/sport-sport-mecanique-24h-du-mans-05.jpg)

## 🚀 Introduction

This project focuses on data pre-processing related to the 24 Hours of Le Mans 2023 dataset. Once the data has been processed, the goal will be to identify initial trends during the EDA, and then to focus on the leading cars. We want to understand if it's possible, based on this dataset, to determine which factors contributed to the winners securing the race. Finally, we will perform a detailed analysis of Peugeot's performance compared to that of the top 5.

## 🛠️ Technos Used

- **Python**
- **Pandas**
- **Plotly**
- **Matplotlib / Seaborn**

## 🔑 Project Workflow

1. **Collecting the CSV File**
- CSV file containing data related to the 2023 edition the 24 Hours of Le Mans.
- Data hour by bour: car, drivers, category, number of laps, number of pitstops, best lap, best lap KpH.

2. **Exploring the Data**
- Main statistics
- Data Types
- Null Values

3. **Cleansing the Data**
- Changing data format, mostly for date columns.
- Remove useless spaces to avoid getting same values in different formats.

4. **EDA**
- First exploration : number of laps per car, per category, per drivers. Pitstops and Best Lap per Car.
- Further exploration with Plotly : max speed or number of laps a car can do without needing to stop.

5. **Focus on the Top 5**
- Calculate the rankings and the best lap of every car in the top 5.
- Evaluate the performance and make some assumptions about the main factors for this performance.

6. **Focus on the Peugeot Performance**
- Check the number of pitstops, the average speed, the best lap, the ranking over time.
- Compute the average value for all the KPIs within the Top 5 cars.
- Compare with the Peugeot's performance and give some recommendations.
