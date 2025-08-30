-----

# Blinkit Business Intelligence Dashboard

## 📊 Introduction

This project is a comprehensive business intelligence dashboard built with Power BI to analyze and visualize the performance of Blinkit, a leading quick-commerce company. This dashboard transforms raw operational data into actionable insights, providing a 360-degree view of the business across sales, customer behavior, inventory management, marketing efforts, and customer feedback.

The primary goal is to empower stakeholders with an interactive and user-friendly tool to monitor Key Performance Indicators (KPIs), identify trends, and make data-driven decisions to foster growth.

-----

## 🎥 Demo

Here is a quick demonstration of the interactive features of the dashboard.

[Demo video](./demo.gif)

-----

## 🎯 Problem Statement

The dashboard was designed to address key business questions from a centralized platform:

  - What are the overall sales trends, and which products or regions are the top performers?
  - How effective are our marketing campaigns in terms of ROI, clicks, and conversions?
  - Who are our most valuable customers, and what is the customer retention and churn rate?
  - How can we optimize our inventory by tracking stock levels, movement, and damaged goods?
  - What is the overall customer sentiment, and what are the most common areas of feedback?

-----

## ✨ Dashboard Features

The report is divided into several key pages for focused analysis:

1.  **Overview:** A consolidated summary of the most critical KPIs from all sections for a high-level executive view.
2.  **Sales Overview:** Detailed analysis of sales performance by month, product category, customer segment, and geographic area.
3.  **Customer Analysis:** Insights into customer demographics, acquisition, retention, and lifetime value. Includes metrics like new vs. lost customers and repeat purchase rates.
4.  **Inventory Management:** Tracks total received stock, available stock, stock movement percentage, and damaged stock to help optimize the supply chain.
5.  **Marketing Performance:** Monitors the effectiveness of marketing campaigns by tracking clicks, impressions, conversions, revenue generated, and marketing spend.
6.  **Feedback Analysis:** Aggregates customer feedback and star ratings to identify areas of improvement in service, product quality, and app experience.

-----

## 🛠️ Tech Stack & Tools

  - **Database:** `MySQL` (for storing and querying the source data).
  - **BI Tool:** `Microsoft Power BI` (for data modeling, visualization, and dashboard creation).
  - **Data Analysis Expressions:** `DAX` (for creating custom calculations, KPIs, and complex measures).

-----

## ⚙️ Project Methodology

1.  **Data Extraction:** Connected Power BI to the MySQL database to import the relevant datasets (sales, customer info, inventory, etc.).
2.  **Data Modeling:** Established a relational schema within Power BI by creating relationships between tables to ensure data integrity and enable cross-filtering across the entire report.
3.  **DAX Measures & Calculations:** Developed numerous DAX measures to calculate complex KPIs such as YTD Sales, Period-over-Period Growth, Customer Churn Rate, and Marketing ROI.
4.  **Dashboard Development:** Designed an intuitive and visually appealing user interface with interactive elements like slicers, tooltips, and drill-through functionality for a seamless and insightful user experience.

-----

## 🚀 How to Use

1.  Clone the repository:
    ```bash
    git clone https://github.com/NeuralDataMind/Blinkit
    ```
2.  Download the `.pbix` file from the repository.
3.  Open the file using **Power BI Desktop**.
4.  Interact with the slicers and visuals to explore the data. *Note: You may need to configure the data source settings if you connect it to your own database.*

-----

## ✍️ Author

  - **Mallikarjun Reddy Bardipuram**
  - **LinkedIn:** [Link](https://www.linkedin.com/in/b-mallikarjun-reddy-9380b0217/)
  - **GitHub:** [Link](https://github.com/NeuralDataMind)
