# Insurance-Analytics-Power-BI-Project

**OVERVIEW**  
An end-to-end Power BI initiative on data analysis of insurance policies, claims, demographics of customers, and sentiment based on customer feedback. The solution is based on the combination of SQL Server data with Excel feedback data, the use of data profiling and cleanup, and advanced visualization and is implemented with the use of row-level security (RLS) and automatic refresh, as well as in Power BI Service.

**PROJECT HIGHLIGHTS**
Microsoft SQL Server — Insurance policy & claims dataset (10,000 records)  
Excel Workbook — Customer feedback dataset (97 records)  

**POWER BI REPORT PAGES**
**PAGE 1 - OVERVIEW** 
<img width="1127" height="634" alt="image" src="https://github.com/user-attachments/assets/992142e7-255b-462d-b05d-6bc5cb1b939c" />

* KPI Cards: Premium Amount, Coverage Amount, Claim Amount
* Bar Chart: Premium by Policy Type
* Donut Chart: Active vs Inactive Policies
* Ribbon/Stacked Chart: Claims by Status (Rejected/Settled/Pending)
* Line Chart: Claim Amount by Age Group
* Matrix: Coverage Amount by Policy Type × Claim Status
* Slicers: Claim Number, Policy Number, Customer ID

**PAGE 2 - CUSTOMER AND POLICY DETAILS**
<img width="1127" height="643" alt="image" src="https://github.com/user-attachments/assets/7b16030b-4168-4490-9ae6-ef8c03c2e68d" />
Tabular view of:
* Policy Number, Customer ID, Claim Number
* Premium & Claim amounts
* Policy Start/End dates
* Age, Age Group
* Active/Inactive flag
  
**PAGE 3 - CUSTOMER SENTIMENT ANALYSIS**
<img width="1139" height="644" alt="image" src="https://github.com/user-attachments/assets/0d1abb1a-0916-4791-a2ae-ce89a9f14f59" />

* Word Cloud (Custom Visual): Highlights recurring terms in feedback
* Table: Customer Name, Sentiment Score, Exact Feedback
* Bar Chart: Count of customers by feedback category (Excellent, Good, Needs Improvement)

**Deployment & Refresh**
Published to Power BI Service  
Dashboard created by pinning important visuals across pages
Scheduled refresh configured using On-premises Gateway (Personal mode)  







