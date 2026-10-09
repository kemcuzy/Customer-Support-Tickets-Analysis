# # Customer Support Tickets Analysis

### Turning Customer Support Data into Actionable Business Insights

**Project Type:** Data Analytics | Customer Experience | Business Intelligence
**Tool:** Microsoft Excel
**Project Status:** Completed


# 1. Introduction

Customer support plays an essential role in customer retention, brand reputation, and business growth. Every support ticket represents a customer who needs assistance, has encountered a problem, or requires clarification about a product or service.

However, collecting support tickets is not enough. Businesses need to understand the types of issues customers report, how efficiently support teams respond, whether tickets are resolved effectively, and how these experiences influence customer satisfaction.

This project analyzes a customer support ticket dataset to evaluate support operations, identify potential service bottlenecks, and uncover opportunities to improve the overall customer experience.

The analysis uses Microsoft Excel to transform raw customer support data into meaningful insights through data preparation, Pivot Tables, charts, and an interactive dashboard.

### Project Objectives

* Analyze ticket volume by type, subject, product, and priority.
* Evaluate first response time across support channels.
* Examine ticket status and resolution patterns.
* Assess customer satisfaction across different groups and ticket statuses.
* Identify potential operational inefficiencies and customer experience challenges.
* Develop actionable recommendations to improve customer support performance.


## 2. Analytical Approach and Data Story

The project followed a structured analytical process, moving from understanding the dataset to developing insights and business recommendations.

The central business question was:

**How can customer support data help an organization improve response efficiency, ticket resolution, and customer satisfaction?**

The analysis was organized into the following stages:

1. **Data understanding:** Reviewed the dataset structure, columns, and business relevance.
2. **Pre-analysis:** Examined data quality, missing values, field consistency, and data types.
3. **Exploratory analysis:** Used Pivot Tables to investigate ticket distribution and service performance.
4. **Data visualization:** Created charts to communicate key findings clearly.
5. **Dashboard development:** Combined important metrics and visualizations into a single dashboard.
6. **Post-analysis:** Interpreted the findings and developed recommendations for stakeholders.

### The Data Story

The dataset tells the story of customer interactions with a support team. It helps investigate which products and issues generate support demand, how response performance differs across communication channels, how tickets are distributed across statuses and priorities, and how customer satisfaction varies.

By connecting these areas, the analysis supports a broader understanding of the customer support process, from the initial request to its eventual resolution and the customer's reported experience.



## 3. Instruments and Tools Used

The following tools and Excel features were used in the project:

| Tool or Feature        | Purpose                                                   |
| ---------------------- | --------------------------------------------------------- |
| Microsoft Excel        | Data preparation, analysis, and reporting                 |
| Excel Tables           | Structured data management                                |
| Pivot Tables           | Summarizing ticket data by categories                     |
| Pivot Charts           | Visualizing analytical results                            |
| Excel formulas         | Calculating and transforming response time                |
| Conditional Formatting | Highlighting important values and performance differences |
| Slicers                | Filtering dashboard results interactively                 |
| Excel Dashboard        | Presenting KPIs and key findings in one view              |



## 4. Pre-Analysis: Understanding the Dataset

The dataset contains customer and ticket information, including:

* Ticket ID
* Customer Name
* Customer Email
* Customer Age
* Customer Gender
* Product Purchased
* Date of Purchase
* Ticket Type
* Ticket Subject
* Ticket Description
* Ticket Status
* Resolution
* Ticket Priority
* Ticket Channel
* First Response Time
* Customer Satisfaction Rating

### Data Preparation

Before analysis, attention was given to data quality and the suitability of each field for analysis.

The preparation process included:

* Reviewing column names and data types.
* Checking for missing values in important fields.
* Reviewing categorical fields for consistency.
* Checking the response time field and converting it into hours for easier interpretation.
* Structuring the dataset for Pivot Table analysis.
* Ensuring Ticket ID was counted rather than summed when calculating ticket volume.

**Analytical consideration:** First Response Time must be interpreted according to its original format. If Excel stores the values as date-time serial numbers, they must be converted correctly before calculating average response time.

The dataset includes a Date of Purchase field, but ticket volume trends should only be interpreted as trends in support demand over time if the available date is appropriate for that purpose. Purchase date and ticket creation date are not necessarily the same.



## 5. Initial Observations

The dashboard and preliminary analysis highlighted several areas worth investigating.

### 5.1 Ticket Status

The dashboard reported:

* Total tickets: 8,469
* Closed tickets: 2,769
* Open and pending tickets: 5,700

These figures suggest that a substantial portion of the recorded tickets was not classified as closed at the time represented by the dataset.

The open and pending categories should be examined separately because open tickets may require action from the support team, while pending tickets may be awaiting customer responses or other follow-up.

### 5.2 Response Time by Channel

The response time chart showed the following average response times:

| Support Channel | Average Response Time |
| --------------- | --------------------: |
| Chat            |            7.96 hours |
| Email           |            7.99 hours |
| Phone           |            8.03 hours |
| Social media    |            8.12 hours |

Social media recorded the highest average response time, while chat recorded the lowest.

The difference between the fastest and slowest channels was approximately 0.16 hours, or 9.6 minutes.

Although the difference is relatively small, monitoring channel performance can help identify opportunities to improve response efficiency.

### 5.3 Customer Satisfaction by Gender

The dashboard showed these average satisfaction ratings:

| Customer Gender | Average Satisfaction Rating |
| --------------- | --------------------------: |
| Male            |                        3.03 |
| Female          |                        2.97 |
| Other           |                        2.97 |

Male customers recorded a slightly higher average rating than female customers and customers in the Other category.

These differences should be interpreted cautiously. They do not establish that gender causes differences in satisfaction, and the number of observations in each group should be considered before drawing conclusions.

### 5.4 Product Ticket Count

The product analysis compared ticket counts across products, including Canon EOS, GoPro Hero, Nest Thermostat, Amazon Echo, and other products.

Canon EOS had the highest displayed ticket count among the products shown in the dashboard, with 240 tickets.

High ticket volume can indicate greater product usage, recurring technical problems, usability challenges, or other support needs. Further investigation of ticket subjects and descriptions is necessary to determine the underlying causes.



## 6. In-Analysis: Key Analytical Areas

### 6.1 Ticket Type and Issue Analysis

**Objective:** Identify the most frequently reported customer issues.

The analysis groups tickets by Ticket Type and Ticket Subject and counts Ticket IDs to determine which issues generate the greatest support demand.

This helps businesses distinguish between isolated incidents and recurring problems that may require broader intervention.

**Business value:** Identifying frequent issues can guide improvements in product quality, customer education, documentation, and support procedures.

### 6.2 Response Time Performance

**Objective:** Compare the efficiency of different support channels.

Average First Response Time was compared across chat, email, phone, and social media.

The analysis identified chat as the fastest channel and social media as the slowest based on the displayed averages.

**Business value:** Channel-level performance monitoring helps managers review staffing, response workflows, and service-level targets.

### 6.3 Resolution and Ticket Status Analysis

**Objective:** Understand the distribution of tickets across closed, open, and pending statuses.

The dashboard indicated that 5,700 tickets were open or pending, compared with 2,769 closed tickets.

This highlights the importance of investigating the outstanding workload, identifying reasons for delays, and distinguishing customer-dependent waiting time from internal processing time.

**Business value:** Status monitoring supports backlog management, follow-up planning, and improved visibility into unresolved customer issues.

### 6.4 Resolution by Priority

**Objective:** Assess how tickets of different priority levels are distributed across statuses.

The analysis compares critical, high, medium, and low-priority tickets across closed, open, and pending categories.

This helps determine whether urgent tickets are being handled appropriately and whether high-priority issues remain unresolved.

**Business value:** Priority-based monitoring helps teams allocate resources according to urgency and potential customer impact.

### 6.5 Customer Satisfaction Analysis

**Objective:** Understand how satisfaction ratings vary across customer groups and support outcomes.

The analysis examines average Customer Satisfaction Rating by gender and ticket status.

The satisfaction-by-status analysis should use the average rating for each status, rather than the total or count of ratings, to support meaningful comparisons.

**Business value:** Satisfaction analysis helps organizations identify customer experience gaps and investigate whether service outcomes align with customer expectations.

### 6.6 Product-Based Analysis

**Objective:** Identify products associated with the highest number of support tickets.

Ticket counts were compared across purchased products to highlight products that may require further investigation.

High ticket volume alone does not prove a product is defective. Ideally, ticket counts should also be compared with product sales or the number of customers using each product.

**Business value:** Product teams can use the findings to prioritize product reviews, troubleshooting guides, and improvements in customer education.

### 6.7 Channel Performance Analysis

**Objective:** Evaluate the performance of the available customer support channels.

The analysis considers average response time and, where appropriate, ticket volume and satisfaction.

Chat recorded the fastest average response time, while social media recorded the slowest.

**Business value:** This comparison helps managers identify differences in service delivery and determine where operational improvements may be needed.



## 7. My Dashboard

The Customer Support Tickets Analytics dashboard consolidates important metrics and visualizations into one reporting interface.

### Key Performance Indicators

* **Total Tickets:** 8,469
* **Open and Pending Tickets:** 5,700
* **Closed Tickets:** 2,769
* **Highest Displayed Gender Satisfaction:** Male, with an average rating of 3.03

### Dashboard Visualizations

The dashboard includes:

1. Resolution by Priority
2. Response Time by Channel
3. Product Ticket Count
4. Customer Satisfaction by Gender
5. Ticket Status Distribution
6. Customer Gender and Ticket Status slicers

These visualizations allow users to examine ticket workload, response performance, product-related support demand, and customer satisfaction.

The dashboard's purpose is to make the analysis easier to understand and help stakeholders identify areas requiring further investigation.

**Dashboard screenshot:** Add the full dashboard image here.

*Figure 1: Customer Support Tickets Analytics Dashboard developed in Microsoft Excel.*



## 8. Who This Analysis Matters To and Why

### Customer Support Managers

The analysis helps managers monitor ticket workload, compare response times, review unresolved tickets, and identify opportunities to improve service delivery.

### Customer Service Representatives

The findings can help representatives understand recurring issues, improve follow-up practices, and focus on urgent tickets.

### Operations Managers

Ticket status and response time metrics provide information for evaluating workflows, workload distribution, and potential operational bottlenecks.

### Product Managers and Product Teams

Product ticket counts and issue categories can highlight areas that deserve further product investigation or customer education.

### Business Executives

The dashboard offers a concise view of customer support performance that can inform resource allocation and service improvement priorities.

### Customers

Although customers are not the direct users of the dashboard, they benefit when organizations use support analytics to provide faster responses, more effective resolutions, and clearer communication.



## 9. Post-Analysis Insights

The analysis produced several important findings.

### Insight 1: Outstanding Tickets Require Attention

The dashboard recorded 5,700 open and pending tickets out of 8,469 total tickets, representing approximately 67.3% of the recorded ticket volume.

This indicates that outstanding tickets deserve further investigation. The next step is to determine how many are genuinely overdue and how long they have remained unresolved.

### Insight 2: Response Performance Differs Across Channels

Chat had the lowest average response time at 7.96 hours, while social media had the highest at 8.12 hours.

This identifies a channel-level performance difference that managers can monitor when reviewing response targets and operational processes.

### Insight 3: Product Ticket Volume Can Guide Investigation

Canon EOS recorded 240 tickets among the products displayed in the dashboard.

This makes it a useful starting point for examining ticket subjects, recurring complaints, and possible product-specific support needs.

### Insight 4: Gender Satisfaction Differences Are Small

The dashboard showed average satisfaction ratings of 3.03 for male customers and 2.97 for female and other customers.

The difference is small and should be investigated alongside ticket type, priority, resolution status, and group sizes before drawing conclusions.

### Insight 5: Ticket Status Should Be Evaluated Alongside Priority

The resolution-by-priority chart makes it possible to compare ticket status across critical, high, medium, and low priorities.

The next step is to calculate the percentage closed within each priority group and examine whether critical and high-priority tickets are being addressed within the organization's service-level targets.



## 10. Overall Recommendations

### 10.1 Strengthen Backlog Management

* Review open and pending tickets regularly.
* Identify overdue tickets and assign ownership.
* Establish follow-up procedures for tickets awaiting customer responses.
* Track ticket age and time to resolution.

### 10.2 Improve Response Time Monitoring

* Set clear response targets for each support channel.
* Investigate why social media has the highest average response time.
* Monitor performance against service-level agreements.
* Review average response time alongside ticket volume and staffing levels.

### 10.3 Improve Priority Handling

* Establish clear rules for critical and high-priority tickets.
* Monitor closure rates by priority.
* Escalate urgent issues that exceed response or resolution targets.
* Review unresolved critical tickets regularly.

### 10.4 Investigate Recurring Product Issues

* Examine ticket subjects and descriptions for frequently reported problems.
* Compare ticket counts with product sales or customer numbers where possible.
* Work with product teams to investigate recurring complaints.
* Develop troubleshooting resources for common issues.

### 10.5 Use Satisfaction Ratings to Improve Service

* Examine satisfaction ratings by ticket status and ticket type.
* Investigate low-rated interactions to understand the reasons for dissatisfaction.
* Review customer feedback alongside response and resolution metrics.
* Avoid relying on demographic differences alone to guide service decisions.

### 10.6 Improve Future Analysis

Future versions of this project could include:

* Ticket creation date for accurate ticket volume trend analysis.
* Ticket closure date for time-to-resolution analysis.
* SLA compliance rate.
* First-contact resolution rate.
* Backlog ageing analysis.
* Repeat-contact rate.
* Ticket volume normalized by product sales or customer count.

These additions would provide a more comprehensive view of support efficiency and customer experience.



## 11. Conclusion

This Customer Support Tickets Analysis demonstrates how Microsoft Excel can transform raw support records into actionable business intelligence.

By examining ticket status, response time, product ticket counts, priority handling, and customer satisfaction, the project identifies areas where additional investigation and operational improvement may be valuable.

The most prominent finding is the large proportion of tickets classified as open or pending, which makes backlog management an important area for further review. The response time comparison also identifies differences across channels, while product and satisfaction analyses provide additional perspectives on customer support performance.

Ultimately, customer support analytics is not simply about counting tickets. It is about understanding customer problems, measuring service delivery, identifying operational gaps, and helping businesses make evidence-based decisions.

**The goal is to turn customer support data into better processes, more effective resolutions, and a stronger customer experience.**




**Project takeaway:** Turning customer support data into insights that help organizations monitor service performance and improve customer experience.
