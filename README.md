# Splunk-Fraud-Detection-Dashboard

**Introduction**

This project was part of the Commonwealth Bank’s Introduction to Cyber Security program. I ingested a dataset of financial transactions into Splunk, used SPL queries to analyze fraud patterns, and built a Fraud Detection Dashboard.

The dashboard visualizes fraud by category, merchant, age group, and time period, providing insight into transaction risks.

Skills demonstrated

Ingesting structured datasets into Splunk

Configuring sourcetypes and indexes

Writing SPL queries to isolate and aggregate fraud

Creating clear visualizations

Building dashboards to communicate findings effectively

&nbsp;  
**Dataset Preview**

Preview of prepared_data.csv (first 10 rows).
Quick review of the dataset fields: Step, Customer, Age, Gender, Merchant, Category, Amount, Fraud.

<img width="975" height="566" alt="image" src="https://github.com/user-attachments/assets/4281e3e2-3c55-4c61-9541-110ffc312afd" />

&nbsp;  
&nbsp;  

**Count by Category**



**Statistics Table**
Transaction counts grouped by category. Establishes a baseline of customer activity.

<img width="1089" height="529" alt="image" src="https://github.com/user-attachments/assets/0da4be9c-5824-409a-88d9-ddffa68779c5" />

&nbsp;  
Bar chart showing category distribution. Makes trends easier to see.

<img width="1017" height="442" alt="image" src="https://github.com/user-attachments/assets/a6fe2127-0de6-4f33-bb4f-cb0c7ced7e7f" />

&nbsp;  
Saving the Count by Category panel into a new Fraud Detection Dashboard. Demonstrates ability to convert ad-hoc searches into reusable visualizations.

<img width="831" height="491" alt="image" src="https://github.com/user-attachments/assets/ace154a5-f5e0-415a-99fd-e4634a70e56c" />


&nbsp; 
&nbsp;  

**Count of Fraudulent Payments**

Bar chart showing fraudulent vs non-fraudulent payments. Fraud accounts for a smaller share but is still significant.

<img width="975" height="320" alt="image" src="https://github.com/user-attachments/assets/877596c9-ce9e-4841-abfc-09041eff7d3a" />

&nbsp; 
&nbsp;  

**Count by Age**

Bar chart of transactions by age group. Highlights the 19–25 group (1.0) as the most active.

<img width="975" height="374" alt="image" src="https://github.com/user-attachments/assets/3b687bb2-9003-487f-a908-fb27a1fb4a0f" />

&nbsp; 
&nbsp;  

**Count by Merchant**

Bar chart showing top 10 merchants by transaction count. Provides visibility into where activity clusters.

<img width="975" height="340" alt="image" src="https://github.com/user-attachments/assets/079034c6-66ce-4a6f-9b30-38815ea2c893" />

&nbsp; 
&nbsp;  

**Fraudulent Transactions by Age**

Pie chart showing proportion of fraudulent vs non-fraudulent transactions across age groups.

<img width="975" height="306" alt="image" src="https://github.com/user-attachments/assets/ac514b54-5291-4d11-a4a5-7e54a3783f68" />

&nbsp;  
&nbsp;  
**Fraudulent Transactions by Category**

Line chart of fraudulent transactions by category. Transportation dominates fraud cases.

<img width="975" height="284" alt="image" src="https://github.com/user-attachments/assets/f068f90b-77fa-482c-9ecf-bac1c3312935" />

&nbsp;  
&nbsp;  
**Fraudulent Transactions by Month (Step)**

Bar chart of fraudulent transactions by time step (May–Aug). Provides a time-based perspective on fraud.

<img width="1870" height="635" alt="image" src="https://github.com/user-attachments/assets/5e43fd81-3314-4493-8a23-433ca2c39868" />

&nbsp; 
&nbsp;  

**Final Dashboard**
 
Completed Fraud Detection Dashboard with six panels.
Includes: Count by Category, Fraudulent Payments, Age, Merchant, Fraud by Category, and Fraud by Month. Exported for reporting.

<img width="1857" height="766" alt="image" src="https://github.com/user-attachments/assets/37ec2010-27df-4e57-bc4f-0d19b3454fd0" />
<img width="1846" height="727" alt="image" src="https://github.com/user-attachments/assets/e5904260-076c-430b-85d2-d211d305e51c" />
<img width="1836" height="737" alt="image" src="https://github.com/user-attachments/assets/856a2032-d750-45ed-995e-b74ec2d1757d" />
<img width="1833" height="363" alt="image" src="https://github.com/user-attachments/assets/0254f389-b26d-4ac4-ba3a-beec821fa01a" />






&nbsp; 
&nbsp; 

**Conclusion**

Through this project, I demonstrated my ability to ingest data into Splunk, configure sourcetypes, write SPL queries, and build dashboards to detect fraudulent activity.

This project highlights core SOC skills: turning raw transaction logs into actionable visual insights.
