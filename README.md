# Bank of America Customer Complaints Analysis

## Introduction

This case study focuses on analyzing the customer complaints dataset of Bank of America (BoA) from 2017 to 2023. The primary goal is to explore consumer complaints related to BoA’s financial products and services, uncover patterns, and develop insights that can inform data-driven strategies to improve the company’s customer service.

The dataset contains detailed information on customer complaints, including submission dates, issues, responses, and the timeliness of these responses. By analyzing the data, we aim to provide BoA with valuable insights into their complaint management process, highlight trends over time, and recommend actionable steps to reduce customer dissatisfaction and improve service efficiency.

## Problem Statement

Bank of America faces a high volume of customer complaints across various products and services. The goal of this analysis is to identify key trends, assess response times, and evaluate the company’s handling of these complaints. By uncovering actionable insights, the analysis aims to help improve customer satisfaction and optimize response efficiency.

## Objectives

1. Analyze complaints across different products to identify the most frequent issues.

2. Track complaint trends on a monthly basis to understand peak periods.

3. Identify the top 5 most common issues faced by customers.

4. Monitor the status of complaints and highlight those still in progress.

## Data Description

The dataset consists of complaints submitted by customers regarding various financial products. It includes the following key columns:

Complaint ID: Unique identifier for each complaint.

Submitted Via: The channel through which the complaint was submitted (e.g., online, phone).

Date Submitted: The date when the complaint was submitted.

Date Received: The date when the company received the complaint.

State: The geographical location of the complainant.

Product: The financial product related to the complaint (e.g., checking/savings account, credit card).

Issue: The specific issue raised in the complaint.

Company Public Response: The company’s public response to the complaint.

Company Response to Consumer: The response the company provided to the consumer.

Timely Response: Whether the company responded to the complaint in a timely manner.

## Data Cleaning

The initial dataset contained 62,516 rows and 12 columns. During the data cleaning process, the following steps were taken:

1. Removed Unnecessary Columns: The columns “Sub Product” and “Sub Issues” were deleted due to many blanks and to simplify the analysis. Instead, focus was placed on the “Product” and “Issue” columns.

2. Renaming Columns: The “State” column was abbreviated, so it was renamed to include the full name of each state for clarity.

3. Handling Missing Values: The “Company Public Response” column had some blanks, which were filled with “No public Response” to ensure consistency in the dataset. The “Timely Response” column also contained blanks, which were filled with “Unknown” to preserve the integrity of the data.

4. Renaming Data for Clarity: The product and issue columns contained long descriptions, which were shortened to more concise yet meaningful terms, ensuring that the visualization remained clear and easy to understand.

## Tools Used

The tool used for this analysis is Microsoft Power BI. It was used for data cleaning, analysis, dashboard creation, and reporting. Power BI’s Power Query Editor helped clean and transform the data, while DAX was used for analysis and generating KPIs. The final insights were presented in an interactive dashboard to provide a comprehensive overview of the complaints data.

## Dashboard Overview 







