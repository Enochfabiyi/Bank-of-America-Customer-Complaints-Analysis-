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

![](https://github.com/Enochfabiyi/Bank-of-America-Customer-Complaints-Analysis-/blob/main/1_4dvuVZOSm4qA218csmvQng.webp)

## Insights

The analysis began by examining key performance indicators (KPIs) to provide a snapshot of the overall complaints. The total number of complaints was 62,516, with 1,494 complaints marked as “in progress.” The average acknowledgement time for complaints was 1.22 days, and 94% of complaints received a timely response.

Next, the data was analyzed by product categories. “Checking and Savings Accounts” had the highest number of complaints (24,814), followed by “Credit/Prepaid Cards” with 16,197 complaints. Other notable categories included “Credit Reporting/Repair” (7,710), “Mortgage” (6,601), and “Money Transfer/Service” (3,453).

The trend of complaints over time revealed that July had the highest number of complaints, followed by June, with February recording the lowest number. This seasonal variation suggests potential changes in customer experience or reporting periods.

Common issues faced by consumers were also analyzed. “Managing an Account” emerged as the most frequent issue, with 15,100 complaints, followed by “Report Inaccuracy” (4,900), “Statement Discrepancy” (4,400), “Closing Account” (4,000), and “Payment Process Issues” (2,800). These top five issues were identified for deeper focus.

Finally, a detailed table was created to highlight complaints that were still in progress, allowing for real-time tracking and response. The in-progress complaints were observed to be exclusively from 2023, providing an interesting insight into the time frame for unresolved complaints.

These insights collectively give a clear overview of the complaint patterns and responses, allowing for targeted actions and continuous improvement in customer service and complaint resolution processes.

## Recommendations

Improve Acknowledgement Time — The average acknowledgement time is 1.22 days, which could be reduced further. Companies should aim for faster responses to enhance customer satisfaction. Consider setting a target for an acknowledgement time of under 1 day, possibly through automation or prioritization strategies.

Focus on High-Complaint Products — Checking and Savings Accounts and Credit/Prepaid Cards have the highest number of complaints. It might be beneficial to analyze these products in more detail to identify recurring issues. Offering training or improving support around these products could reduce complaints significantly.

Address Common Issues Proactively — Managing an Account, Report Inaccuracy, and Statement Discrepancy are the top recurring issues. Proactively addressing these through clearer communication or FAQs on the website could lower the volume of complaints. Additionally, consider creating a more robust customer service process to handle these issues faster.

Enhance Timely Response Rates — With 94% of complaints receiving a timely response, there’s room for improvement. Striving for a 100% timely response rate can improve customer trust and satisfaction. This could be achieved by optimizing workflows, leveraging technology for faster processing, or increasing staffing during peak times.

Track and Resolve In-Progress Complaints Efficiently — The 1,494 complaints still in progress should be closely monitored. Regularly check in on the status of these complaints to ensure they are resolved promptly. Establishing a dedicated team to manage in-progress complaints and ensure no cases are left unresolved for too long could improve response times and outcomes.

Address 2023 In-Progress Complaints — The fact that 2023 is the only year with in-progress complaints suggests that there may be issues with handling complaints from that year. It would be worth investigating the backlog to ensure that no complaints from 2023 are left unresolved. Implementing a system to track unresolved complaints from past years could be helpful.

Use Data to Anticipate Issues — By analyzing the trends and issues reported in previous months, you can anticipate potential spikes in certain types of complaints. For example, if you notice recurring complaints related to payment processing, steps can be taken in advance to address these concerns (e.g., system improvements, customer education, etc.).

Regularly Update Customers on Progress — For in-progress complaints, keep customers updated regularly on the status of their cases. Clear communication regarding the expected resolution time will likely improve customer satisfaction, even if the issue isn’t immediately resolved.

## Link to Dashboard

Explore the full interactive dashboard [here](https://app.fabric.microsoft.com/view?r=eyJrIjoiZjNiZDZmMzYtMjZlMC00MDdkLWJiYjAtNGIyZGJkMTg1YTExIiwidCI6ImRhZjMyMGRmLTc4ODMtNDA0Ny1hZWVjLTAxNTliMjRkZGFmZSIsImMiOjZ9)

## Conclusion

In conclusion, the analysis of the 62,516 complaints reveals key insights into customer issues, with Checking and Savings Accounts and Credit/Prepaid Cards receiving the highest number of complaints. July saw the peak in complaints, while the most common issues were account management and report inaccuracies.

The data also shows that most complaints receive timely responses, but some remain in progress, particularly in 2023. These insights highlight areas for improvement, including quicker responses and addressing recurring issues, helping to drive more effective customer service strategies.





