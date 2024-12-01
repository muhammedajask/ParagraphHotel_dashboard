# Power BI Dashboard: Paragraph Hotel & Resorts Analysis

This project analyzes **Paragraph Hotel & Resorts**' performance over 18 months, focusing on the last six months of **2017** and the entire year of **2018**. The dashboard reveals key performance metrics and highlights actionable insights for improving hotel operations and guest experience.

![Paragraph Hotel & Resorts Dashboard](paragraph_hotel_and_resorts.png)

## Project Overview

The analysis was conducted using **Power BI**, with **Power Query** for data cleaning and **DAX** functions for calculating key performance indicators (KPIs). The dashboard explores the hotel's revenue trends, booking behaviors, and guest preferences.

### Key Insights
- **Top-Performing Months**: September and October consistently lead in revenue each year.
- **Booking Channels**: Online bookings contribute the highest revenue, and when combined with offline bookings, they account for **85%** of total revenue.
- **Popular Room Category**: Room Category One is the most favored by guests. Underperforming rooms, like rooms 6 and 7, could be converted into this popular category to maximize occupancy.
- **Meal Plan Preferences**: Guests mostly prefer the **CP (Complimentary Breakfast)** meal plan.
- **Booking Lead Time**: 
  - **No Sudden Bookings**: Most bookings are made at least two weeks in advance.
  - **No Long-Term Bookings**: Bookings made a year in advance are minimal. The majority of bookings occur within a two-week to three-month window.

### Financial Performance
- **Revenue Trends**: 
  - The hotel generated **$1.66 million** in the last six months of 2017 and **$9.69 million** in 2018.
  - A total of **$11.35 million** was generated over 18 months from **109,000** rooms sold, with an **ADR (Average Daily Rate)** of **$104**, accommodating **67,000** guests.

### Key Challenges
1. **High Cancellation Rate**: 
   - The cancellation rate increased from **15%** in 2017 to **37%** in 2018, with an overall average of **33%**. Reducing the cancellation rate below **20%** should be a priority to minimize revenue loss.
   
2. **Low Loyalty Ratio**: 
   - The loyalty ratio stands at only **3%**, indicating a lack of repeat guests. Focusing on enhancing loyalty programs and offering attractive discounts could help boost customer retention.

## Data Preparation
- **Columns Removed**: Unnecessary columns like car parking, special requests, and number of children were removed.
- **Columns Modified**: The meal plan column was updated to reflect hotel standards (CP, EP, MAP, AP).
- **Lead Time Categorization**: Lead time was categorized by the number of days and renamed **booking_date**.
- **Date Transformation**: Year, month, and date were concatenated into a **stay_date** column using Power BI DAX.

## Tools Used
- **Power BI**: For data cleaning, transformation, and visualization.
- **DAX Functions**: For creating custom measures such as ADR, Loyalty Ratio, and Cancellation Ratio.

## Files in This Repository
- **Dataset**: [paragraph_hotel_dataset.csv](./paragraph_hotel_dataset.csv)
- **Power BI Dashboard**: [paragraph_hotel_dashboard.pbix](./paragraph_hotel_dashboard.pbix)

## How to Use This Dashboard
1. Download the `.pbix` file from [this link](./paragraph_hotel_dashboard.pbix).
2. Open it using **Power BI Desktop**.
3. Explore the visualizations and interact with filters to gain insights into the hotel’s performance for the selected years.

## Conclusion
This dashboard offers a comprehensive view of **Paragraph Hotel & Resorts'** performance, highlighting key trends in revenue, guest preferences, and operational challenges. The insights gained can help the hotel management improve their business strategy, reduce cancellation rates, and increase customer loyalty.
