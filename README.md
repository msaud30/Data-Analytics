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

## Life cycle of data:
Plan, capture, manage, analyze, archive and destroy. 

- **Planning**: Decide what kind of data is needed, how it will be managed, and who will be responsible for it. Happens way before analysis of project. _For example, a company might decide to capture information on how much electricity its customers use each year, what types of buildings are being powered, and what types of devices are being powered inside of them. The electricity company would also decide which team members will be responsible for collecting, storing, and sharing that data. All of this happens during planning, and it helps set up the rest of the project._

- **Capture**: data is collected from variety of different sources. Public vs private databases.

- **Manage**: Care for and maintain the data. This includes determining how and where it is stored and the tools used to do so. Important for cleansing phase...

- **Analyze**: data is used to solve problems, make decisions, and support business goals. For example, _one of our electricity company goals might be to find ways to help customers save energy._

- **Archive**: storing data in a place where it's still available, but may not be used again. It makes sense to archive vs keeping data around...

- **Destroy**: Remove data from storage and delete any shared copies of the data. Electricity company example. _They would have data on multiple hard drives. To destroy it, the company would use a secure data erasure software. Any paper files would be shredded._
---

## Data Lifecycle examples:
**U.S. Fish and Wildlife Service**
A glimpse of how government, finance, and education institutions can view data life cycles a little differently.
https://www.fws.gov/data/life-cycle

**Financial institutions Data Life Cycles:**
Financial institutions may take a slightly different approach to the data life cycle as described in The Data Life Cycle, an article in Strategic Finance magazine: https://sfmagazine.com/post-entry/july-2018-the-data-life-cycle/

Capture, Qualify, Transform, Utilize, Report, Archive, & Purge

## Google bigquery example

```SQL
SELECT SUM(totals.pageviews) AS TotalPageviews
FROM 'bigquery-public-data.google_analytics_sample.ga_sessions_20170101'
```
