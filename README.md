# AtliQ-Grands-Hospitality-Analysis

## Introduction
AtliQ Grands is a prominent Indian hotel chain with over 20 years of experience. Operating in major cities like Delhi, Mumbai, Bangalore, and Hyderabad, the company offers a diverse portfolio of hotels, including luxurious properties like AtliQ Palace and business-focused accommodations such as AtliQ Seasons. 

However, AtliQ Grands is facing challenges with declining revenue and market share. To address these challenges, the company has embraced data analytics to inform its decision-making process. This project focuses on analyzing booking data from multiple sources to identify opportunities for revenue growth and enhanced competitiveness.

---

## Problem Statement
AtliQ Grands, a reputable Indian hotel chain, is experiencing a decline in revenue and market share. To reverse this trend, the company is leveraging data analytics to:
1. Analyze booking data from internal and third-party platforms.
2. Identify trends, patterns, and actionable insights.
3. Develop strategies to increase revenue and improve competitiveness.

---

## Dataset
The project utilizes the following five datasets:

1. **dim_date.csv**  
   - Contains details about dates, months, weeks, and day types.

2. **dim_hotels.csv**  
   - Includes information about properties such as property ID, name, category, and city.

3. **dim_rooms.csv**  
   - Provides room details including room ID and room class.

4. **fact_aggregated_bookings.csv**  
   - Aggregated booking data including property ID, check-in date, room category, successful bookings, and capacity.

5. **fact_bookings.csv**  
   - Detailed booking data, including booking ID, property ID, booking and check-in dates, number of guests, room category, booking platform, ratings, booking status, revenue generated, and revenue realized.

---

## Data Cleaning & Transformation
The following steps were performed to prepare the data for analysis:
1. **Clean Invalid Data**:
   - Removal or correction of inconsistent and erroneous entries.
2. **Outlier Removal**:
   - Identified and removed statistical outliers to enhance data quality.
3. **New Column Creation**:
   - Added derived columns to facilitate more detailed and meaningful analysis.

---

## Insights Generated
The analysis yielded the following key insights:

1. **Average Occupancy Rate by Room Category**:
   - Presidential rooms have the highest average occupancy rate at **59.30%**.

2. **Average Occupancy Rate by City**:
   - **Delhi** has the highest occupancy rate at **60.40%**, while Bangalore has the lowest at **55.29%**.

3. **Weekday vs. Weekend Trends**:
   - Weekends show significantly higher occupancy rates than weekdays, indicating opportunities for targeted marketing or pricing adjustments.

4. **Monthly Occupancy for June**:
   - In June, Delhi recorded the highest occupancy rate at **62.47%**, followed by Hyderabad at **58.46%**.

5. **Revenue Per City**:
   - Mumbai generates the highest revenue among the cities.

6. **Month-by-Month Revenue**:
   - Revenue fluctuates month-to-month, with **May 2022** generating the highest revenue at **40.83 crore INR**.

7. **Revenue by Booking Platform**:
   - The "Others" category contributed the highest revenue, followed by "MakeYourTrip."

---

## Conclusion & Recommendations
### Recommendations
1. **Weekend Promotions**:
   - Develop and implement weekend-specific promotions, such as special deals, events, or amenities, to attract more guests during weekends.

2. **Expand Operations in Delhi**:
   - Invest in expanding the hotel chain's presence in Delhi by opening more properties or enhancing existing ones, given its higher occupancy rates.

### Conclusion
This analysis underscores the potential of leveraging data-driven strategies to identify opportunities for revenue growth, optimize resources, and improve market competitiveness.

---

## Technologies Used
- **Python**: For data analysis and visualization.
- Libraries: `pandas`, `matplotlib`, `seaborn`.

---
