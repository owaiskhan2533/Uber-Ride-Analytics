# Uber Ride Analytics Dashboard

An interactive **Power BI** dashboard that analyzes Uber ride bookings across vehicle types, revenue, payment methods, cancellations and customer behavior. It turns raw booking data into clear, actionable business insights.

---

## Project Overview

This dashboard answers questions like:

- How many rides were booked, completed, cancelled or left incomplete?
- Which vehicle types generate the most revenue?
- How do bookings and revenue change month by month?
- Which payment methods do customers prefer?
- Why do rides get cancelled, by customers and by drivers?
- Which pickup and drop locations are the busiest?

---

## Dashboard Pages

### 1. Home
Landing page with a short project description and navigation buttons to every page (Home, Overview, Vehicle, Revenue, Rider).

![Home] <a href="https://github.com/owaiskhan2533/Uber-Ride-Analytics/blob/main/Screenshots/Screenshot%202026-11-03%20231058.png"><a/>

---

### 2.Overview
High-level performance summary with KPI cards and trends.

- **KPIs:** Booking Count, Completed Rides, Average Distance, Total Distance, Revenue, Lost Bookings
- Completed bookings trend (Month / Quarter toggle)
- Revenue by vehicle type
- Monthly revenue distribution
- Top Pickup and Top Drop locations

![Overview](images/overview.png)

---

### 3. 🚕 Vehicle
Vehicle-wise breakdown in a detailed table with sparklines.

- Customer Count, Revenue, Booking Count, Completed Bookings and Contribution % per vehicle
- Monthly trend sparkline for each vehicle type
- Vehicles covered: Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL

![Vehicle](images/vehicle.png)

---

### 4. Revenue
Revenue and cancellation analysis.

- **KPIs:** Completion Rate %, Cancellation Rate %
- Monthly and quarterly revenue trend
- Revenue by payment method
- Cancellation reasons by customers
- Top customers by revenue

![Revenue](images/revenue.png)

---

### 5. Rider
Customer-level insights.

- Monthly and quarterly customer trend
- Customers by payment method
- Customer details table (Revenue, Completed, Lost, Avg Distance)
- Cancelled rides by reasons, with Driver / Incomplete / Customer slicers

![Rider](images/rider.png)

---

## Key Insights

| Metric | Value |
|---|---|
| Total Bookings | ~149K |
| Completed Rides | ~93K |
| Completion Rate | 62.21% |
| Cancellation Rate | 38.19% |
| Total Revenue | ~52M |
| Average Distance | 24.64 km |
| Total Distance | 2.51M km |
| Lost Bookings | ~57K |

- **Auto** is the top revenue vehicle (~13M), followed by **Bike** (~11M) and **Go Mini** (~10M). **Uber XL** is the lowest (~2M).
- **UPI** is the most used payment method (~23M revenue, ~46K customers), followed by **Cash**.
- Revenue dips in **February** (~3.97M) and peaks around **March** (~4.57M).
- Top customer cancellation reasons are **wrong address** and **change of mind** (~2.4K each).
- Driver-side cancellations are mostly due to **customer-related issues**, **too many passengers** and **personal or car-related problems**.
- Top pickup location is **Khandsa** (600) and top drop location is **Ashram** (592).

---

## Tools & Technologies

- **Power BI Desktop**: dashboard and visuals
- **DAX**: measures and KPIs
- **Power Query**: data cleaning and transformation

---

## Features

- Interactive navigation across 5 pages
- Month / Quarter toggle on trend charts
- Vehicle-type selector on the left panel
- Drill-down tables with sparklines
- Slicers for Driver / Incomplete / Customer cancellation views
- Clean, Uber-themed UI

---


## How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `Uber_Dashboard.pbix` in **Power BI Desktop**
3. Refresh the data if the dataset path changes
4. Use the navigation buttons and slicers to explore the dashboard

---

## Author

**Your Name**
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | 🐙 [GitHub](https://github.com/your-username)

---

⭐ If you found this project useful, give it a star!


