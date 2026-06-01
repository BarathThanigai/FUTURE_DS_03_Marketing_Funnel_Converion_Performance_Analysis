# Marketing Funnel & Conversion Performance Analysis

## Project Overview

This project performs a comprehensive marketing funnel and conversion analysis using the Bank Marketing Campaign dataset. The objective is to understand how prospects move through the marketing funnel, identify conversion bottlenecks, evaluate channel effectiveness, and uncover customer segments with the highest likelihood of conversion.

Since the source dataset does not contain explicit funnel stages, a proxy funnel was constructed using campaign interaction data and customer response behavior. The analysis helps identify opportunities to improve lead qualification, campaign targeting, and overall marketing performance.

---

## Dashboard Preview

![Dashboard](Dashboard1.png)

![Dashboard](Dashboard2.png)

![Dashboard](Dashboard3.png)

![Dashboard](Dashboard4.png)

![Dashboard](Dashboard5.png)

---

## Objectives

- Data Cleaning & Preparation: Prepare campaign data for analysis
- Funnel Analysis: Model prospect progression through the marketing funnel
- Conversion Analysis: Measure customer conversion performance
- Channel Performance Analysis: Compare outreach channels
- Audience Segmentation: Identify high-converting customer groups
- Campaign Effectiveness Analysis: Evaluate impact of contact frequency
- Seasonal Trend Analysis: Identify high-performing campaign periods
- Visualization: Build an interactive Power BI dashboard for business insights

---

## Dataset Description

The project uses the Bank Marketing Campaign dataset containing customer outreach and campaign interaction records.

Key attributes include:

- age: Customer age
- job: Occupation category
- marital: Marital status
- education: Education level
- default: Credit default status
- housing: Housing loan status
- loan: Personal loan status
- contact: Contact communication type
- month: Last contact month
- day_of_week: Last contact weekday
- duration: Call duration in seconds
- campaign: Number of campaign contacts
- pdays: Days since previous contact
- previous: Number of previous contacts
- poutcome: Outcome of previous campaign
- y: Final campaign outcome (conversion)

---

## Funnel Methodology

The original dataset contains outreach interactions and conversion outcomes rather than explicit funnel stages.

To enable funnel analysis, a proxy marketing funnel was constructed:

- Contacted → Total outreach records
- Engaged → Contacts with above-median call duration
- Qualified → Engaged contacts with positive prior interaction indicators
- Customer → Successful campaign conversion (`y = yes`)

This approach allows meaningful funnel analysis despite the absence of native CRM or website funnel stages.

---
