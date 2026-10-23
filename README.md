# Power BI Recruitment Analytics Dashboard

## Project Overview

This project shows how Power BI can analyze recruitment performance through interactive dashboards, KPIs, funnel analysis, and sourcing metrics.

The dashboard uses a fictional recruitment dataset designed around common hiring stages for cybersecurity and technical roles.

## Objectives

- Track candidates across the recruitment process.
- Compare candidate sourcing channels.
- Analyze recruitment performance by job role.
- Monitor offer acceptance and joining rates.
- Identify potential recruitment bottlenecks.
- Present recruitment insights through interactive visualizations.

## Tools and Technologies

- Microsoft Power BI Desktop
- Microsoft Excel
- Power Query for data preparation
- DAX for calculated measures
- GitHub for project documentation and portfolio presentation

## Dashboard Features

- **KPI Cards:** Total candidates, candidates joined, offers accepted, and joining rate.
- **Source Analysis:** Candidate volume and joining performance across Naukri, LinkedIn, and referrals.
- **Recruitment Funnel:** Screening passed, interview selected, offers accepted, and candidates joined.
- **Job-Role Analysis:** Recruitment performance across SOC Analyst, Pre-Sales Engineer, and Cybersecurity Engineer roles.
- **Offer Status Analysis:** Accepted, declined, pending, and not-issued offers.
- **Interactive Slicers:** Filter results by job role and candidate source.
- **Recruitment Insights:** Summary of sourcing performance, offer acceptance, and improvement opportunities.

## Key Findings

Based on the fictional sample dataset of 20 candidates:

| Metric | Result |
|---|---:|
| Total Candidates | 20 |
| Candidates Joined | 9 |
| Offers Accepted | 9 |
| Joining Rate | 45% |
| Screening Passed | 17 |
| Interview Selected | 13 |
| Referral Joining Rate | 60% |
| Offer Acceptance Rate | 81.8% |

Referrals had the highest joining rate in this sample, while Cybersecurity Engineer had the highest joining rate among the three job roles.

These results are illustrative and should not be treated as statistically conclusive.

## Data Model and Measures

The dataset includes candidate ID, job role, source, application date, screening status, interview status, offer status, joining status, and joining date.

DAX measures were created to calculate:

- Total Candidates
- Candidates Joined
- Offers Accepted
- Joining Rate
- Screening Passed
- Interview Selected
- Referral Joining Rate
- Offer Acceptance Rate
- Funnel Candidates

## Repository Structure

- `README.md` — Project documentation
- `recruitment_data.xlsx` — Fictional sample dataset
- `Recruitment_Analytics_Dashboard.pbix` — Power BI report
- `images/dashboard-overview.png` — Dashboard screenshot
- `images/dashboard-filter-demo.png` — Optional interactive-filter example

## How to Use

1. Download the Excel dataset and Power BI report.
2. Open the `.pbix` file using Power BI Desktop.
3. If prompted, update the Excel data source path.
4. Refresh the data if required.
5. Use the slicers to explore recruitment results by job role and source.

## Skills Demonstrated

- Recruitment metrics and funnel analysis
- HR data analysis
- Microsoft Excel
- Power Query data preparation
- DAX measures
- Power BI visualization
- Dashboard design
- Recruitment process improvement
- Technical documentation using GitHub

## Disclaimer

This portfolio project was created for learning and demonstration. All candidate records are fictional and do not represent actual employees, applicants, or company recruitment results.
