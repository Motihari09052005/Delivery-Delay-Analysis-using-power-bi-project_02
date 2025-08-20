# Delivery-Delay-Analysis-using-power-bi-project_02
This project analyzes online delivery performance to identify zones, time slots, weather conditions causing maximum delays. using power bi ,delivery data is visualized through bar charts, heatmaps and slicers for interactive exploration. key insights such as top 5 delays zones, weather impact, and delay trends help improve planning and logistics .t

Functional Components
   Import delivery order data into Power BI
 ➗ Create calculated column:
Delay = Actual - Scheduled
   Visualize delays using bar charts & heatmaps
    Add slicers for Zone, Weather, and Time Slots
   Summarize Top 5 delay-prone zones
Power BI Visualizations
 Bar Chart: Delays by Zone
 Heatmap: Delays by Time Slot & Zone
 Slicers: Weather condition, Zone filter, Time slot filter
 Summary Card: Average Delay 
1. Zones with Highest Delays:
o North Zone has the highest average delay (~29.35 minutes)
o Followed by East (~28.8 minutes) and Central (~27.9
minutes)
o South (~27.3 minutes) has the lowest average delay
2. Weather Impact on Delays:
o Stormy weather leads to the longest delays (~34.5 minutes)
o Foggy (~32.7 minutes) and Rainy (~30.1 minutes) also
cause high delays
o Clear weather (~23.5 minutes) and Cloudy (~20.7
minutes) have the least delays
3. Time Slot Analysis:
o Evening (5 PM – 9 PM) shows the highest delays (~30.2
minutes)
o Morning (5 AM – 12 PM) also has significant delays (~28.7
minutes)
o Afternoon (12 PM – 5 PM) has the lowest average delay
(~22.4 minutes)
Top 5 Delay-Prone Zones (by average delay):
1. North (~29.35 mins)
2. East (~28.8 mins)
3. Central (~27.9 mins)
4. West (~27.7 mins)
5. South (~27.3 mins) 
 Overall Delay Statistics:
 Average delay: ~28 minutes
 Minimum delay: 0 minutes (on-time deliveries)
 Maximum delay: 60 minutes
 Median delay: 30 minutes
 Worst Delay Orders (per Zone):
 Central: ORD0020 → 60 mins delay
 South: ORD0187 → 60 mins delay
 East: ORD0017 → 55 mins delay
 North: ORD0057 → 55 mins delay
 West: ORD0178 → 55 mins delay
 Extreme Delay Example:
 Order ID: ORD0020
 Zone: Central
 Weather: Stormy
 Delay: 60 minutes (max)
Delivery Status Ratio:
 95.2% of orders were delayed
 Only 4.8% were on time
 Distance vs Delay:
 Correlation between distance and delay is -0.09 → very
weak negative correlation
   Meaning: Longer distances don’t necessarily cause more
delays (other factors like weather and time slots matter
more)
