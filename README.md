## What is Data Analysis?
The collection, transformation, and organization of data in order to draw conclusions, make predictions, and drive informed decision-making.


## Data Analysis Process Phases: 
- **Ask**: define the problem and confirm stakeholder expectations
- **Prepare**: collect and store data for analysis
- **Process**: clean and transform data to ensure integrity
- **Analyze**: use data analysis tools to draw conclusions
- **Share**: interpret and communicate results to others to make data-driven decisions
- **Act**: put your insights to work in order to solve the original problem
---

## Data Lifecycle:
Plan, capture, manage, analyze, archive and destroy. 

- **Planning**: Decide what kind of data is needed, how it will be managed, and who will be responsible for it. 
    - _What plans and decisions do you need to make? What data do you need to answer your question?_

- **Capture**: data is collected from variety of different sources. 
    - _Where does your data come from? How will you get it?_

- **Manage**: Care for and maintain the data. This includes determining how and where it is stored and the tools used to do so.
    - _How will you store your data? What should it be used for? How do you keep this data secure and protected?_

- **Analyze**: data is used to solve problems, make decisions, and support business goals.
    - _How will the company analyze the data? What tools should they use?_

- **Archive**: storing data in a place where it's still available, but may not be used again.
    - _What should they do with their data when it gets old? How do they know when it's time?_

- **Destroy**: Remove data from storage and delete any shared copies of the data.
    - _Should they ever dispose of any data? If so, when and how?_ 
---

## Data Analysis Process vs Data Lifecycle
- Both have 6 important phases.
- **Data analysis** involves following a process to analyze data.
- **Data life cycle** deals with the stages that data goes through during its useful life.

## Data Lifecycle examples:
**U.S. Fish and Wildlife Service:**
A glimpse of how government, finance, and education institutions can view data life cycles a little differently.
https://www.fws.gov/data/life-cycle

**Financial institutions:**
Financial institutions may take a slightly different approach to the data life cycle as described in The Data Life Cycle, an article in Strategic Finance magazine: https://sfmagazine.com/post-entry/july-2018-the-data-life-cycle/

***Data life cycle will vary from company to company or by industry or sector.***

## SQL
![image](https://user-images.githubusercontent.com/63278449/155258123-2a839238-a717-411e-b951-abdf6b66d01c.png)

The syntax of every SQL query is the same: 

- Use SELECT to choose the columns you want to return.
- Use FROM to choose the tables where the columns you want are located.
- Use WHERE to filter for certain information.

## Google bigquery example

```SQL
SELECT SUM(totals.pageviews) AS TotalPageviews
FROM 'bigquery-public-data.google_analytics_sample.ga_sessions_20170101'
```
