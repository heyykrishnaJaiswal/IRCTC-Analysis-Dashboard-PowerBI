🚆 IRCTC Business Insights Dashboard | Power BI

*Track Performance. Drive Growth. Deliver Excellence.

An interactive business intelligence dashboard developed using **Microsoft Power BI** to analyze railway booking activity, revenue performance, user engagement, train operations, occupancy, and route-wise booking trends.

The dashboard transforms railway-related synthetic data into visual business insights through KPI cards, trend analysis, interactive station filters, donut charts, and route performance visualizations.

> **Disclaimer:** This project uses synthetic data for educational and portfolio purposes. The displayed metrics are illustrative and do not represent official IRCTC statistics.

---
📌 Project Overview

The IRCTC Business Insights Dashboard provides a consolidated view of key railway business indicators.

The dashboard is designed to help users explore booking performance, revenue distribution, customer activity, and popular railway routes through an interactive reporting interface.

It includes five major KPI cards, a source-station filter, monthly booking analysis, revenue breakdowns, route-wise booking comparisons, and an automated key-insights section.

The project demonstrates the practical application of business intelligence, data visualization, and analytical reporting using Power BI.

🎯 Project Objectives

* Analyze total railway bookings and monthly booking patterns.
* Monitor total revenue and its distribution across booking categories.
* Understand user activity through user-related KPIs.
* Display train operation metrics and average occupancy.
* Compare booking activity across railway routes.
* Analyze booking channels and booking types.
* Build an interactive dashboard for exploring business performance.
* Present key metrics in a clear and visually appealing format.

🛠️ Tools and Technologies

| Technology                 | Purpose                                                     |
| -------------------------- | ----------------------------------------------------------- |
| Microsoft Power BI Desktop | Dashboard development and reporting                         |
| Power Query                | Data preparation and transformation, where implemented      |
| DAX                        | KPI calculations and analytical measures, where implemented |
| CSV                        | Source dataset                                              |
| Data Visualization         | Presenting trends, distributions, and comparisons           |
| Business Intelligence      | Analyzing business metrics and performance                  |

---

📊 Dashboard Overview

The dashboard contains the following analytical components.

#1. Key Performance Indicators (KPIs)

The top section presents five major performance indicators.

| KPI               | Description                                            |
| ----------------- | ------------------------------------------------------ |
| Total Bookings    | Displays the total booking count.                      |
| Total Revenue     | Displays the total revenue value.                      |
| Total Users       | Shows the number of users represented in the analysis. |
| Trains Operated   | Displays the train operation count.                    |
| Average Occupancy | Shows the average occupancy metric.                    |

Each KPI card includes a headline value and a small trend visualization or percentage indicator.

#2. Source Station Filter

The dashboard provides a source-station selector for exploring the data by station.

Available station options shown in the dashboard:

* ADI — Ahmedabad
* CSMT — Mumbai
* HWH — Howrah
* HYB — Hyderabad
* LKO — Lucknow
* NDLS — New Delhi
* SBC — Bengaluru

Selecting a station allows users to explore the corresponding data, depending on the dashboard's configured filter interactions.

#3. Booking Trend Analysis

The Booking Trend chart compares total bookings with previous-month bookings across the twelve months.

**Analysis includes:**

* Monthly booking performance.
* Comparison with previous-month booking values.
* Identification of booking peaks and declines.
* Exploration of monthly fluctuations.

The visualization helps users understand changes in booking activity over time.

#4. Revenue by Booking Type and Channel

The dashboard contains two donut charts that summarize revenue distribution.

**Booking channel analysis:**

* IRCTC Website
* IRCTC App
* Authorised Partner

**Booking type analysis:**

* Reserved
* Tatkal
* Premium Tatkal

The charts help compare the contribution of different booking channels and ticket categories to the revenue represented in the dataset.

#5. Top Routes by Booking

The horizontal bar chart compares bookings across railway routes.

Routes visible in the dashboard include:

* Delhi – Mumbai
* Delhi – Howrah
* Mumbai – Pune
* Bengaluru – Chennai
* Lucknow – Delhi

The chart makes it easier to compare booking volumes and identify routes with higher booking activity.

#6. Automated Key Insights

The bottom section presents automatically generated analytical observations.

Examples of the types of insights displayed include:

* The month with the highest total bookings.
* The month with the lowest total bookings.
* The percentage difference between high and low booking months.
* The total revenue represented in the analysis.
* The total users represented in the dataset.
* The revenue range across the selected months.

These insights help summarize important findings without requiring users to interpret every chart individually.

The specific observations and values change according to the data and dashboard filters.

---

📈 Key Metrics Displayed

The screenshots demonstrate two different dashboard states.

The values below are transcribed from the screenshots and are illustrative, not verified real-world statistics.

| Metric                   | Dashboard Screenshot 1 | Dashboard Screenshot 2 |
| ------------------------ | ---------------------: | ---------------------: |
| Total Bookings           |                     8K |                    20K |
| Total Revenue            |                    35M |                    53M |
| Total Users              |                     8K |                    19K |
| Trains Operated          |                    540 |                    540 |
| Average Occupancy        |                  80.09 |                  79.92 |
| Displayed Booking Change |                 10.29% |                 10.31% |
| Displayed Revenue Change |                 10.84% |                 10.72% |
| Displayed User Change    |                 10.16% |                 10.12% |

**Important:** These are values displayed in the provided screenshots. The differences may result from different filter selections or report states. The screenshots alone do not establish the exact cause.

The revenue values use abbreviated `M` notation in the dashboard, while the detailed key-insights section displays more precise numeric values.

---
💡 Business Insights and Applications

The dashboard supports several types of business analysis.

### Booking Performance

Monthly comparisons help identify periods with relatively high or low booking activity.

### Revenue Distribution

Booking channel and ticket-category visualizations help explore how revenue is distributed across different categories.

### Route Performance

Route comparisons help identify which routes account for higher booking volumes in the selected data.

### User Engagement

The total-users KPI provides a summary of user activity represented in the dataset.

### Operational Monitoring

Train counts and occupancy metrics provide a high-level view of the operational indicators included in the report.

### Decision Support

Combining KPIs, trend charts, and automated insights helps users interpret business metrics in one place.

These are potential applications of the dashboard, rather than claims that the project has produced measurable improvements in actual railway operations.

---

## 🗃️ Dataset Information

The project uses a CSV dataset named:

`irctc_business_insights_synthetic_data.csv`

**Dataset characteristics:**

* **Format:** CSV
* **Domain:** Railway business analytics
* **Purpose:** Power BI dashboard development and analysis
* **Data type:** Synthetic/sample data
* **Usage:** Educational and portfolio purposes

The dataset provides sample records for exploring booking activity, revenue-related metrics, users, occupancy, booking categories, and route-level performance, to the extent those fields are present.

The exact column names, record count, and data types should be verified against the included CSV file.

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/IRCTC-Business-Insights-PowerBI.git
```

Replace `YOUR-USERNAME` with your GitHub username.

Alternatively, download the repository as a ZIP file.

### Step 2: Install Power BI Desktop

Install Microsoft Power BI Desktop on your Windows computer.

### Step 3: Open the Report

Open the following file in Power BI Desktop:

`IRCTC Analysis.pbix`

### Step 4: Check the Data Source

If Power BI cannot locate the CSV file:

1. Open the report in Power BI Desktop.
2. Select **Transform data**.
3. Review the source path for the CSV file.
4. Update the path to match the location of the downloaded dataset.
5. Apply the changes and refresh the report.

### Step 5: Explore the Dashboard

Use the station selector and available chart interactions to explore booking, revenue, user, occupancy, and route metrics.

#Step 6: Refresh the Report

If the source data is updated, refresh the report to recalculate the metrics and update the visualizations.

🔮 Future Enhancements

* Add more detailed month-over-month and year-over-year analysis.
* Improve KPI comparisons and trend indicators.
* Add additional station and route filters.
* Introduce forecasting for booking and revenue trends.
* Improve data validation and documentation.
* Add a dedicated executive summary page.
* Explore predictive analytics using suitable historical data.
* Optimize dashboard layout for different screen sizes.

---
📚 Learning Outcomes

This project demonstrates practical experience with:

* Power BI dashboard design.
* Business KPI visualization.
* Data exploration and interpretation.
* Monthly trend analysis.
* Revenue distribution analysis.
* Route-level comparisons.
* Interactive report filters.
* Business intelligence reporting.
It also provides an opportunity to communicate analytical findings through a structured, visual reporting interface.



⚠️ Disclaimer
This is an independent educational project created for learning and portfolio demonstration.
The project uses synthetic data. Its displayed metrics and observations must not be interpreted as actual IRCTC operational results.
This project is not affiliated with, endorsed by, or sponsored by IRCTC or Indian Railways.


👨‍💻 Author 
--Krishna Jaiswal
Aspiring Data Analyst | Power BI | SQL | Python | Data Analytics

⭐ Feedback
If you find this project useful for learning Power BI and business analytics, consider starring the repository.
Suggestions and constructive feedback are welcome.
