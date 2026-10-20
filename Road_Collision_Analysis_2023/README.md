# 🚦 Road Collision Analysis | Power BI Dashboard

![Road Collision Analysis - Dashboard](/Images/road_collision_db_page%201.gif)
# 🚧 Introduction
An interactive **Power BI dashboard** designed to explore road collision patterns, casualties, injuries, vehicle involvement, and how accident counts vary by time, day, speed limit, and area type.

The project transforms road collision data into clear visual insights to support exploratory analysis and data-driven road-safety discussions.

---

## 🎯 Target Audience

This dashboard is designed for:

- **Road Safety Authorities:** Monitor collision patterns and identify areas that may require safety improvements.
- **Traffic Management Teams:** Analyze accident trends by day and time to support traffic planning.
- **Government & Transportation Agencies:** Use data insights to support road safety policies and infrastructure planning.
- **Urban Planners:** Explore collision hotspots and understand accident distribution across urban and rural areas.
- **Data Analysts:** Practice data analysis, DAX, data visualization, and interactive dashboard development using Power BI.
- **Researchers & Students:** Explore road collision patterns and develop data-driven insights into traffic safety.

**Main Goal:** To transform road collision data into actionable insights that support better traffic management, road safety awareness, and evidence-based decision-making.

## 📊 Dashboard Preview
*This report is split into three distinct pages to provide both a high-level summary and a detailed analysis.*
### Page 1: Road Collision Overview
![Road Collision Analysis - Overview](/Images/road_collision_db_page%201.gif)

Your mission control for road safety, highlighting key KPIs and collision trends to identify accident hotspots and support safer roads.

###  Page 2 :Time and Speed Analysis
![Road Collision Analysis - Time and Speed](/Images/road_collision_db_page%202.gif)

Analyzing how collision patterns vary by time of day and road speed limits.

###  Page 3 :Road surface & weather and Light Conditions Analysis

![Road Collision Analysis - Time and Speed](/Images/road_collision_page%203.gif)
---

## 🎯 Project Objectives

- Monitor the overall number of collisions, casualties, vehicles, and injuries.
- Compare collision counts across days of the week.
- Explore how collisions vary by time of day.
- Analyze casualties across speed-limit categories.
- Compare collision patterns across urban and rural areas.
- Explore the geographic distribution of collisions.
- Investigate the relationship between congestion and collision counts throughout the day.

## 📌 Key Performance Indicators (KPIs)

The dashboard overview displays these headline metrics:

| KPI | Displayed Value |
|---|---:|
| Total Collisions | 104K |
| Total Casualties | 133K |
| Total Vehicles | 190K |
| Total Injuries | 56K |

*Values are reproduced from the dashboard screenshots and may be rounded for display.*

## 🔍 Dashboard Insights

The following observations are based on the visuals shown in the dashboard. They describe patterns in the displayed data and should not be interpreted as proof of causation.

- **Day of the week:** Friday has the highest displayed collision count at approximately **17.1K**, while Sunday has the lowest at approximately **11.7K**.
- **Speed-limit categories:** The dashboard shows approximately **99K casualties** in the low-speed category, **26K** in the medium-speed category, and **9K** in the high-speed category. Confirm the category definitions and underlying data before drawing safety conclusions.
- **Area type:** The area-type chart shows **67% urban** and **33% rural**. This represents the split shown in the visual; it should not be described as a normalized accident *rate* unless exposure data (such as traffic volume or distance travelled) is available.
- **Time of day:** The displayed time chart peaks at **5:00 PM (1,068 collisions)** among the shown time points.
- **Monthly trend:** The monthly chart shows variation across the year, with labeled values ranging from approximately **7.5K to 9.6K** in the displayed months.
- **Geographic distribution:** The map highlights collision clusters in parts of southern England, including areas around London and the south coast.
- **Congestion and collisions:** The dashboard compares congestion and collision values by time period. This can help identify patterns, but it does not establish that congestion causes collisions.

## 🧰 Tools & Skills

- **Power BI Desktop** — report design and interactive visualizations
- **DAX** — KPI measures and analytical calculations
- **Power Query** — data preparation and transformation (if used in the project)
- **Data Visualization** — KPI cards, bar charts, line charts, pie chart, and map
- **Exploratory Data Analysis (EDA)** — identifying patterns and comparing categories

## 🖥️ Dashboard Features

- Day-of-week slicer
- Time-of-day slicer
- Clear Filter button
- KPI cards for collisions, casualties, vehicles, and injuries
- Day-of-week collision comparison
- Casualties by speed-limit category
- Time-of-day collision analysis
- Monthly collision trend
- Urban/rural distribution
- Geographic collision map
- Congestion versus collisions comparison



## 🚀 How to Use

1. Download or clone this repository.
2. Open the `road collision.pbix` file using **Power BI Desktop**.
3. If prompted, configure the data source and refresh the data.
4. Use the slicers to filter by day and time period.
5. Explore the charts and map to investigate collision patterns.


## 💡 Potential Next Steps

- Add a date table and more detailed time-period analysis.
- Compare collision severity and casualty outcomes.
- Add year-over-year and month-over-month comparisons.
- Analyze collisions by weather, lighting, road surface, and road type when those fields are available.
- Create normalized collision rates using traffic volume or vehicle-distance data, if available.
- Add tooltips, drill-through pages, and bookmarks for deeper analysis.
- Document the data source, cleaning steps, and DAX measures.

## ⚠️ Data & Interpretation Notes

- Dashboard values are rounded as displayed in the visuals.
- The findings are descriptive and do not prove causation.
- A high collision count does not necessarily mean a higher collision risk. Risk comparisons may require exposure data, such as traffic volume, population, or distance travelled.
- Confirm the source, reporting period, definitions, and completeness of the dataset before using the results for formal road-safety decisions.

## 👤 Author

**Ali Hanafy**

- GitHub: [Ali Hanafy](https://github.com/mrali851h/Power-BI-Dashboard)
- LinkedIn: [Ali Hanafy](https://www.linkedin.com/in/ali-hanafy-5a8462384)

