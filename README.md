# Uber-Analysis
This project presents an end-to-end analysis of Uber rides using Power BI. The dashboard provides a clear view of customer behavior, driver performance, revenue, cancellations, and operational efficiency. It enables decision makers to quickly identify patterns, trends, and insights to optimize Uber’s services.
📂 Dataset Details

The dataset (from Kaggle) includes information such as:

Booking Information: Booking ID, status (completed, cancelled, incomplete).

Ride Metrics: Ride distance, wait time, seat time.

Customer & Driver Metrics: Ratings, cancellation reasons.

Time Dimensions: Month, Weekday, Hour.

Location Dimensions: Pickup and Drop locations.

Payment Method: UPI, Cash, Card, Wallet, etc.

🖥️ Dashboard Pages

1. Executive Summary

KPIs:

Total Bookings (450K)

Total Revenue (156M)

Avg Ride Distance (25 km)

Avg Driver Rating (4.23)

Avg Customer Rating (4.40)

High-level split of Completed vs Cancelled rides.

Filters (Slicers): Weekday, Month, Pickup Location.

2. Ride Patterns by Time

Completed vs Incomplete rides by Month.

Completed vs Incomplete rides by Weekday.

Identifies seasonal and weekly ride patterns.

3. Revenue & Payments Analysis

Revenue & Bookings trend by Month.

Revenue & Bookings trend by Weekday.

Revenue & Bookings distribution by Payment Method (UPI, Cash, Wallet, Cards).

Insight: UPI dominates both bookings and revenue (~45%).

4. Location Insights

Revenue & Bookings by Top Pickup Locations.

Revenue & Bookings by Top Drop Locations.

Allows analysis of hotspot areas for demand.

5. Vehicle Performance

Vehicle distribution (Auto, Bike, Go Mini, Sedan, XL, etc.).

Avg Ride Distance by Vehicle Type.

Ratings (Driver vs Customer).

Insight: Larger vehicles (SUV/XL) tend to have longer ride distances.

6. Hourly Ride Analysis

Revenue & Bookings by Hour of Day (AM/PM).

Identifies peak booking hours for operational planning.

7. Cancellations & Delays

Cancelled Rides by Driver (e.g., personal issues, customer issues).

Cancelled Rides by Customer (e.g., wrong address, change of plans, driver asked to cancel).

Incomplete Rides reasons (vehicle breakdown, customer demand).

Avg CTAT (Customer Time Around Trip) and Avg VTAT (Vehicle Time Around Trip).

📊 Key Insights

📈 Total Revenue: 156M from ~450K bookings.

🕒 Peak booking times are concentrated in certain weekday hours.

🚘 Vehicle mix shows Go Mini and Auto as most common, but SUV/XL drives longer distances.

💳 Payment Preference: UPI (45%) dominates, followed by Cash (~25%).

❌ Cancellations: Major reasons include wrong addresses (customer) and customer-related issues (driver).

🧭 Navigation

The dashboard uses a navigation panel to move between pages.

Filters (Weekday, Month, Pickup Location) allow users to dynamically explore data.

⚙️ Tools & Technologies

Power BI Desktop (data cleaning, modeling, dashboard building).

Power Query Editor (data transformation).

DAX (custom measures).

🚀 How to Use

Open the .pbix file in Power BI Desktop.

Use the navigation menu (left sidebar) to switch between pages.

Apply filters (Month, Weekday, Location) to customize insights.

Hover over charts for tooltips and deeper insights.
