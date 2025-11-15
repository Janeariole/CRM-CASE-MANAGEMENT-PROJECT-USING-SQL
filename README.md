CRM Case Management Insights — SQL Portfolio Project

Analyzed 10,000+ bank complaints using SQL to uncover trends in complaint reasons, resolution timelines, channels, and repeat issues. Insights guided CRM case management requirements. Project includes schema, queries, and sample data to showcase SQL skills in a real-world banking context.
 CRM Case Management Insights — SQL Portfolio Project

Project Overview

This project simulates a real-world banking scenario where I analyzed customer complaints to guide the deployment of a CRM case management system. Using SQL, I extracted insights from a robust complaints dataset to identify patterns in complaint reasons, resolution timelines, repeat complaints, and channel effectiveness.

The goal was to inform functional requirements for a CRM solution that improves customer experience and operational efficiency.

Business Context

Banks receive thousands of complaints daily across multiple channels — mobile apps, ATMs, branches, call centers, and email. These complaints range from technical issues to service dissatisfaction.

To deploy an effective CRM case management system, it's critical to understand:
- What customers are complaining about
- How long it takes to resolve issues
- Which channels are most problematic
- Which customers are repeat complainants

Database Schema

The project uses a simulated dataset with over 10,000 complaint records. Key tables include:

- `Complaints`: complaint_id, customer_id, reason, channel, date_received, date_resolved, status, request_type
- `Customers`: customer_id, name, segment, region
- `Complaint_Resolution`: complaint_id, resolution_type, resolution_time_days
- `Complaint_History`: complaint_id, is_repeat, previous_complaint_id

SQL Insights

Here are examples of the insights extracted using SQL:

- Top Complaint Reasons: Identify the most frequent issues (e.g., wrong debits, ATM errors, staff attitude)
- Resolution Time by Channel: Compare average resolution times across mobile, ATM, branch, etc.
- Repeat Complaints Rate: Measure how many customers complain more than once
- Complaint Trends Over Time: Spot seasonal spikes or recurring patterns

 CRM Recommendations

Based on SQL analysis, I proposed CRM features such as:
- Auto-flagging repeat complaints for priority handling
- SLA tracking per complaint channel
- Predefined complaint categories for faster triage
- Dashboards for time-based complaint trends

  Files Included

- `data/complaints_data.csv`: Simulated dataset with 10,000+ rows
- `schema/create_tables.sql`: SQL script to create the database schema
- `queries/insights_queries.sql`: SQL queries used for analysis
- `notebooks/analysis.ipynb`: Optional notebook for visualizations
- `visuals/`: Folder for charts and graphs (e.g., complaint trends)

 How to Use

1. Clone the repo
2. Load `complaints_data.csv` into your SQL environment
3. Run `create_tables.sql` to set up schema
4. Execute queries from `insights_queries.sql`
5. Explore insights and adapt them to your own CRM use case

Author

Jane Ariole  
Banking Domain Business Analyst |  Enthusiast | CRM Strategist  
GitHub: [your-github-handle]  
LinkedIn: [your-linkedin-url]

License

This project is for educational and portfolio purposes only.
