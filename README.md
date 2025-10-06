✈️ Airline Analysis in Power BI

This project focuses on analyzing delayed and cancelled flights in the United States to uncover insights and trends in airline performance. The analysis aims to identify factors that influence flight punctuality and to demonstrate data visualization, storytelling, and dashboard design in Power BI.

🔗 Interactive Dashboard: https://app.powerbi.com/links/cMcj2yQwpe?ctid=4a39c578-6df0-42b9-a7e0-e9eac6d91816&pbi_source=linkShare


⸻

📊 Project Overview

Air travel in the US is impacted by various factors such as weather conditions, air traffic control delays, and airline-specific operations. Using historical flight data, this project:
	•	Examines delays and cancellations by carrier, airport, season, and reason.
	•	Highlights patterns and bottlenecks in flight punctuality.
	•	Builds interactive dashboards that allow stakeholders to explore flight trends and performance metrics.

This project demonstrates not only technical data visualization skills in Power BI but also the ability to translate raw data into actionable insights.

⸻

📂 Dataset

Key attributes include:
	•	✈️ Airline / Carrier – the operating airline
	•	🛫 Origin and Destination Airports
	•	📅 Year, Month, Day – flight dates
	•	⏳ Arrival and Departure Delays – measured in minutes
	•	❌ Cancellations and Diversions – and their causes
	•	🌦️ Delay Categories – weather, late aircraft, carrier, NAS (National Airspace System), security

Note: The dataset was cleaned and transformed before being loaded into Power BI.

⸻

⚙️ Data Preparation

Data preparation was performed to ensure consistency and usability for visualization:
	1.	Data Cleaning:
	•	Removed duplicates and invalid records
	•	Handled null and missing values
	2.	Feature Engineering:
	•	Derived delay categories (e.g., significant delay thresholds)
	•	Created new KPIs like on-time performance rates
	3.	Modeling:
	•	Built relationships between fact (flights) and dimension (time, airline, airport) tables
	•	Applied appropriate data types and hierarchies for Power BI visuals

⸻

📈 Dashboard Highlights

The Power BI dashboard provides an interactive and intuitive interface for exploring flight performance.
Key features include:
	•	KPI Cards: Total flights, % on-time, % delayed, % cancelled
	•	Trend Analysis: Monthly and seasonal trends in delays and cancellations
	•	Geospatial Visualizations: Map of airports with delay patterns
	•	Root Cause Breakdown: Contribution of weather, carrier issues, late aircraft, etc.
	•	Airline & Airport Performance: Rankings by delay frequency and cancellation rate
	•	Filtering & Drill-Down: User-friendly slicers for time period, carrier, airport, and delay cause

