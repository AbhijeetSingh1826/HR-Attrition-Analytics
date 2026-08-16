# HR Employee Attrition Analytics

A Power BI dashboard I built to dig into why employees at a company are leaving, using the IBM HR Analytics dataset (1,470 employees, 35 attributes).

![Dashboard Overview](assets/overview.png)

## Why I built this

Employee attrition is one of those problems every company deals with but rarely digs into properly. I wanted to see what actually drives people to quit, not just track that they did, so I built this dashboard to break attrition down by department, role, overtime, satisfaction, and marital status.

## What I found

- People who work overtime leave at 30.5%, almost triple the rate of people who don't (10.4%). This was the single biggest gap in the whole dataset.
- Single employees leave more than married or divorced employees (25.5% vs 12.5% and 10.1%).
- Sales Representatives have by far the worst attrition of any role, 39.8%. Compare that to Sales Managers at just 5.4% in the same department.
- Low job satisfaction matters too: employees who rated satisfaction 1 out of 4 attrite at 22.8%, almost double the rate of those who rated it 2.
- Overall attrition is 16.1% (237 out of 1,470 people), and Sales and HR are both running above the company average while R&D sits below it.

## Takeaway

If I had to point to one group to focus retention efforts on, it would be Sales Reps who work overtime and report low satisfaction. That's a small, specific slice of the workforce, and going after it directly is a lot more realistic than a broad "improve retention everywhere" initiative.

## Pages in the dashboard

1. **Overview** - headline numbers, headcount by role and department, attrition split
2. **Attrition Drivers** - attrition rate broken down by overtime, satisfaction, marital status, department
3. **Department Deep-Dive** - drill into department-level headcount, income, and attrition by role

## Tools

Power BI, DAX, Excel for cleaning the raw data before loading it in.

## Files in this repo

- `HR_Attrition_Analytics.pbix` - open this in Power BI Desktop to explore the dashboard yourself
- `assets/` - screenshots of each page

---
Abhijeet Singh
