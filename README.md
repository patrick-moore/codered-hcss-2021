# Problem Statement

HeavyJob is an application for managing projects, timecards, and job costs in the Heavy Civil Construction Industry.
Our users have a variety of projects going on at any given time, and they need a way to quickly determine how those projects are progressing and identify potential problems.
Create a dashboard that displays various KPIs in an informative way (See below).

Feeling up for a challenge? Different metrics matter to different users so having the ability to customize which metrics are displayed is a big plus.

# KPI Information

Here are some suggested KPIs:

- Variance (Budget vs Actual) on Job (All, This Week, This Month, Last 7 Days, Last 14 Days)
- Total Cost on Job (All, This Week, This Month, Last 7 Days, Last 14 Days)
- Variance (Budget vs Actual) by Cost Types (All, This Week, This Month, Last 7 Days, Last 14 Days)
- Total Cost by Cost Types (All, This Week, This Month, Last 7 Days, Last 14 Days)
- Time Cards Submitted (Today, Yesterday, This Week, Last Week)
- Diaries Submitted (Today, Yesterday, This Week, Last Week)(Compare against time cards submitted?)
- Time Cards Needing Review (Today, Yesterday, This Week, Last Week) (Approve, Review, Accept, Rejected)
- Photos Submitted on a Job (Today, Yesterday, This Week, Last Week) (Show thumbnails of the photos?)
- Weather by Job (Today, Yesterday, Tomorrow, This Week, Last Week, Next Week)

Feel free to add expand on these or add your own. If needed, you can modify the data in `db.json`.

# Sample Data

> IMPORTANT NOTE:
> there are now 3 additional datasets - db-split, db-small, db-small-split
> db-small is a truncated version of the original db.json dataset
> db-split is the size of the original dataset, but with actual and budgets split into their own entity and referencable via projectId
> db-small-split is a combination of the db-split and db-small

A sample dataset is provided in the db.json file. Feel free to set up a backend if you want, but a development API can be started quickly by running:

`npm install`
`npm run db`

This utilizes the `json-server` package. More information is available here https://github.com/typicode/json-server.

After starting up `json-server` you can see a list of available endpoints by going to `http://localhost:3004`
