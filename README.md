Project Overview

This project is a Power BI dashboard created to analyze IT support ticket data and evaluate support performance using a KPI scorecard. The dashboard helps in understanding support workload, ticket urgency, and department wise performance in a clear and simple way.

The main purpose of this project is to compare actual support activity with defined targets and highlight areas that require attention using traffic light indicators.

Dashboard Description

The dashboard displays key IT support metrics such as total tickets, percentage of high priority tickets, ticket distribution by department, and priority mix. Users can interact with the dashboard by selecting departments to see how performance changes across different teams.

Ticket volume targets automatically adjust based on the selected departments. This ensures that KPI results remain meaningful whether one department or all departments are selected.

KPIs Included
Total Tickets

This KPI shows the total number of support tickets for the selected departments on a fiscal year basis. The target scales dynamically depending on how many departments are selected.

High Priority Tickets Percentage

This KPI shows the percentage of tickets marked as high priority. Fixed thresholds are used to identify normal, warning, and critical urgency levels.

KPI Status Logic

Green means performance is within the defined target.
Yellow means performance is close to the target and should be monitored.
Red means performance is above acceptable limits and needs attention.

Traffic light indicators are used throughout the dashboard to make performance status easy to understand at a glance.

Data Source

The dashboard uses a publicly available IT support ticket dataset sourced from Kaggle. The data was cleaned and prepared to simulate real world IT support reporting. No confidential or company specific data is used.

Tools Used

Power BI for data modeling and visualization
DAX for KPI calculations and dynamic target logic
CSV file as the data source

Purpose of This Project

This project was created for learning and portfolio purposes. It demonstrates the ability to design KPI scorecards, apply dynamic target logic, and communicate insights clearly using Power BI.
