# HR Attrition & Financial Impact Analytics

## Project Overview

This project uses Power BI to examine employee attrition patterns, workforce characteristics, and an illustrative financial sensitivity model.

The goal is to demonstrate how data preparation, analytical measures, and interactive visualizations can turn an HR dataset into insights that support business investigation and decision-making.

## Business Questions

* What is the overall employee attrition rate?
* How does observed attrition vary by overtime status, company tenure, and job satisfaction?
* How do employee departures differ across departments, job roles, and job levels?
* How does average monthly income compare between employees who stayed and employees who left?
* How can scenario modeling illustrate the potential financial scale associated with employee turnover?

## Dataset

The dataset contains 1,470 employee records and 35 columns, with one employee per row and `EmployeeNumber` serving as the employee identifier.

The analysis uses employee, job, compensation, satisfaction, tenure, and attrition fields.

## Tools and Techniques

* **Power BI** — dashboard development and interactive reporting
* **Power Query** — data preparation and type management
* **DAX** — measures for employee counts, departures, attrition rates, and scenario calculations
* **DAX Query View** — direct validation of executive metrics and grouped attrition results

## Key Findings

* Overall observed attrition was **16.12%**, representing 237 departures among 1,470 employees.
* Employees working overtime had a **30.53%** observed attrition rate, compared with **10.44%** among employees not working overtime.
* Employees with 0 years at the company had a **36.36%** observed attrition rate; those with 1 year had **34.50%**.
* Employees with the lowest job-satisfaction rating had a **22.84%** observed attrition rate, compared with **11.33%** for the highest rating.
* Average monthly income was approximately **$6,832.74** among employees who stayed and **$4,787.09** among employees who left.
* The Sales Representative job role had the highest observed attrition rate among the listed roles at **39.76%**.

These findings describe patterns in this dataset. They do not establish that any single factor caused employee departures.

## Financial Scenario Model

The dashboard includes a sensitivity model that applies assumed replacement-cost periods to the overall average monthly employee income and the number of recorded departures.

| Scenario | Assumed Period | Illustrative Estimate |
| -------- | -------------: | --------------------: |
| Low      |        1 month |         $1.54 million |
| Medium   |       2 months |         $3.08 million |
| High     |       3 months |         $4.62 million |

**Important limitation:** These are illustrative scenario estimates, not actual company expenses, verified replacement costs, or audited financial results. The assumptions are used to demonstrate scenario modeling and should not be interpreted as a validated turnover-cost methodology.

## Dashboard

The Power BI dashboard brings together executive metrics, attrition comparisons, employee segmentation, and the financial scenario model.

<!-- The dashboard screenshot will be added here after the image is uploaded to the repository. -->

## Limitations

* The analysis is descriptive and does not establish causation.
* The financial model relies on explicit assumptions rather than verified employer turnover expenses.
* Results reflect the supplied dataset and should not automatically be generalized to other organizations.

## Project Status

The Power BI analysis, dashboard, financial scenario model, and DAX Query View validation are complete. This repository packages the project for portfolio review.

