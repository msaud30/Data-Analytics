## What is Data Analysis?
The collection, transformation, and organization of data in order to draw conclusions, make predictions, and drive informed decision-making.


## Data Analysis Process Phases: 
- **Ask**: define the problem and confirm stakeholder expectations
- **Prepare**: collect and store data for analysis
- **Process**: clean and transform data to ensure integrity
- **Analyze**: use data analysis tools to draw conclusions
- **Share**: interpret and communicate results to others to make data-driven decisions
- **Act**: put your insights to work in order to solve the original problem

## Life cycle of data:
Plan, capture, manage, analyze, archive and destroy.

Planning: happens way before analysis project. A company might decide to capture information on how much electricity its customers use each year, what types of buildings are being powered, and what types of devices are being powered inside of them. The electricity company would also decide which team members will be responsible for collecting, storing, and sharing that data. All of this happens during planning, and it helps set up the rest of the project
---

## Google bigquery example

```SQL
SELECT SUM(totals.pageviews) AS TotalPageviews
FROM 'bigquery-public-data.google_analytics_sample.ga_sessions_20170101'
```
