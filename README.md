# FIFA World Cup Analysis (1930–2022)

**Overview**

This project dives deep into 92 years of FIFA World Cup history, analyzing patterns in performance, rankings, goals, and audience engagement.

While football is rich with data, stakeholders often lack a centralized analytical view. Raw stats are scattered across formats, and drawing comparisons across decades is time-consuming. Using SQL as the analytical backbone and Power BI for storytelling, this project bridges that gap — turning raw match data into insights.

⸻

**Business Problem**

Despite being the world’s biggest sporting event, decision-makers across federations, teams, and media still struggle with:
	•	Identifying which teams consistently perform well and win.
	•	Tracking FIFA ranking progress and regressions over time.
	•	Understanding the influence of home advantage on match outcomes.
	•	Analyzing attendance trends and fan engagement globally.
	•	Highlighting top individual performances across tournaments.

In short, too much data, too little clarity.

⸻

**The Solution – SQL + Power BI**

SQL was used extensively to clean, transform, and generate analytical views from raw files:
	•	Cleaned and corrected ASCII issues, inconsistent naming, and delimiter issues.
	•	Standardized all columns across 4 datasets: Matches, Rankings, World Cups, and Top Scorers.
	•	Created joins to build a relational model across hosts, champions, teams, and match records.
	•	Used SQL CTEs, window functions, aggregations, and subqueries to explore deep insights like:
	•	Most consistent finalists
	•	Team performance by win %
	•	Goal trends by player and tournament
	•	Penalty shootout occurrences
	•	Attendance highs over the decades

Power BI then brought those SQL-driven insights to life — transforming static stats into an interactive visual experience.

⸻

**Dashboard Highlights**
	•	KPIs: Total Goals, Matches Played, Most Successful Team
	•	Interactive Line Chart: Matches Played per World Cup (1930–2022)
	•	Geo Map: Average Attendance by Country
	•	Pie Chart: Most World Cup Titles Won
	•	Bar Chart: Top Goal Scorers in History
	•	Matrix: Dynamic FIFA Rankings (Previous vs. Current Points)

With custom formatting, a dark-golden theme, and performance-driven layout — this dashboard balances visual appeal with analytical depth.

⸻

**What We Discovered**
	•	Brazil is the most successful national team (5 titles).
	•	Just Fontaine scored a record 13 goals in one World Cup (1958).
	•	Number of matches has grown steadily, reflecting tournament expansion.
	•	Europe and South America lead in both performance and audience turnout.
	•	FIFA rankings reflect not only performance, but consistent improvement or decline across seasons.

⸻

**Tech Stack**
	•	SQL (MySQL) – Data preparation, transformation, and insights.
	•	Power BI – Dashboard development and visual storytelling.
	•	Power Query – ETL operations to model the data inside Power BI.
	•	DAX – Created custom KPIs and dynamic calculations.
	•	JSON/CSV – Raw data from Kaggle and historical archives.
	•	GitHub – Version control and documentation.

⸻

**Real-World Impact**

This project simulates a real business scenario where:
	•	Sports organizations need clear dashboards to support decisions on team performance, talent scouting, and fan engagement.
	•	Media analysts require quick visuals on World Cup history to support storytelling.
	•	Data teams are responsible for preparing large-scale historical data for non-technical decision-makers.

It also demonstrates end-to-end project ownership — from raw file cleaning to SQL logic to visual analytics.

⸻

**SQL-First Approach**

Instead of relying on Power BI alone, all data shaping was done using SQL, ensuring:
	•	Reusability and performance
	•	Transparent logic
	•	Sharper insights

SQL scripts used in this project are available in the world_cup_analysis.sql file in the repository.

⸻

**Outcomes**
	•	Replaced messy datasets with structured, query-ready formats
	•	Delivered SQL-powered insights with business context
	•	Created a polished Power BI dashboard optimized for decision-makers
	•	Solved real analytical questions using data from 1930 to 2022
	•	Built a reusable framework for similar sports analytics dashboards

⸻

**Future Scope**
	•	Add predictive insights using machine learning (e.g., who’s likely to win next).
	•	Automate data refresh using live APIs or updated ranking datasets.
	•	Expand to include player-level performance dashboards.
	•	Embed the Power BI dashboard online for public access.

⸻

**Final Thoughts**

This project is more than a dashboard — it’s a case study in real-world SQL analytics. It solves a meaningful business problem, blends storytelling with logic, and reflects professional, production-grade work.

If you’re looking to evaluate my SQL, data modeling, and dashboard design skills — this is the one to look at.
