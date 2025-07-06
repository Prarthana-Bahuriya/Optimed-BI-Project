# Optimed Health Partners BI Project

## Project Overview

This repository hosts the Business Intelligence (BI) solution developed for Optimed Health Partners using Power BI. The primary goal of this project was to enhance their call center operations by providing actionable insights into key performance indicators (KPIs), agent performance, and scheduling efficiency. This was a jump-start project completed over 6-7 weeks.

## Business Cases Addressed

The BI solution was designed to address several critical business challenges:

* **Reducing Abandoned Calls/Hold Times:** Providing visibility into abandoned call rates and average hold times to identify areas for improvement.

* **Balancing Inbound and Outbound Calls for Schedule Enhancement:** Offering insights into call volume patterns to optimize agent scheduling.

* **Improving Agent Response Rate:** Monitoring response times to ensure timely customer service.

## Key Features & Dashboards

The Power BI solution comprises several interactive dashboards, each designed to provide specific insights for different stakeholders within Optimed Health Partners, particularly the IT Director (Clive) and his team.

### 1. Executive Summary/Dashboard

* **Goal:** To provide the IT Director with a high-level overview of top KPIs and insights into agent scheduling.

* **Key Metrics:** Total Call Volume, % of Calls Answered < 30s, Avg Time to Answer, Avg Queue Response Time (Min), % of Abandoned Calls.

* **Visualizations:** Trends of call volume, agent count, and abandoned calls by hour of day; comparison of inbound vs. outbound calls.

### 2. Abandoned Calls Report

* **Goal:** To allow the IT Director and IT Team to drill down and filter abandoned call data for detailed analysis.

* **Key Metrics:** Avg Time to Abandon, Total Call Volume, Total Abandoned Calls, % of Abandoned Calls.

* **Visualizations:** Abandoned call counts by hour of day, month, weekday, and day.

### 3. Response Rate Report

* **Goal:** For the IT Director and Teams to drill down on metrics regarding response rates.

* **Key Metrics:** % of Calls Answered < 30s, Avg Queue Response Time (Min), Avg Time to Answer.

* **Visualizations:** Average agent time to answer by hour of day and direction; total call volume and % of calls answered within 30 seconds by hour of day; average queue response time by weekday and day.

### 4. Agent Insights Report

* **Goal:** For the IT Director & Agent Supervisor to understand more details on agent performance and scheduling.

* **Key Metrics:** Avg Call Duration (Min), % of Abandoned Calls.

* **Visualizations:** Count of agents by weekday and direction; count of agents by hour of day and direction.

### 5. Scheduling Report

* **Goal:** For the IT Director and Team to drill down on scheduling correlation between outbound and inbound calls in relation to agents.

* **Key Metrics:** Avg Queue Response Time (Min), Avg Call Duration (Min).

* **Visualizations:** Outbound vs. Inbound calls vs. average call duration by hour of day; outbound vs. inbound calls vs. abandoned calls by hour of day; outbound vs. inbound calls vs. average queue response time by hour of day.

## Business Value and Impact

The successful completion of this project has added significant value to Optimed Health Partners' decision-making process, particularly for the IT Director. This solution is crucial for helping them achieve two major targets:

* **Keep the Abandoned Call Rate below 5%.**

* **Keep the Response Rate below 30 seconds.**

By providing clear, data-driven insights, the BI solution empowers the Optimed team to proactively manage call center operations and improve customer satisfaction.

## Data Model - Star Schema

The Power BI solution is built upon a robust Star Schema data model, designed for optimal performance and ease of analysis. The core of the model includes a `FactCall` table, which is connected to several dimension tables:

* `DimCallType`

* `DimQueue`

* `DimUser`

* `DimDate`

* `DimTime`

This structure ensures efficient querying and allows for flexible slicing and dicing of data across various dimensions.


## Future Enhancements

* Integration with additional data sources for a more comprehensive view.

* Implementation of advanced analytics and predictive modeling for forecasting call volumes and agent needs.

* Further refinement of existing dashboards based on user feedback.

* Development of mobile-optimized versions of key reports.

---

**Thank You!**

Feel free to reach out with any questions or feedback.
