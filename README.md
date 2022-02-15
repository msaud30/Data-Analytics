# Data-Analytics
Data Analytic Notes

# Data Analysis Process Phases: 
- **Ask**: Define the problem and confirm stakeholder expectations
- **Prepare**: Collect and store data for analysis
- **Process**: Clean and transform data to ensure integrity
- **Analyze**: Use data analysis tools to draw conclusions
- **Share**: Interpret and communicate results to others to make data-driven decisions
- **Act**: Put your insights to work in order to solve the original problem

---

## Google bigquery example

```SQL
SELECT SUM(totals.pageviews) AS TotalPageviews
FROM 'bigquery-public-data.google_analytics_sample.ga_sessions_20170101'
```
