# Revenue Analysis Dashboards for Atliq Technologies

## Project Overview
This project involves creating **interactive Tableau dashboards** to visualize and analyze the revenue of Atliq Technologies over a 4-year period. By integrating a live database with Tableau, the dashboards dynamically update whenever the underlying database is modified, providing real-time insights into the company's revenue trends.

The project demonstrates a seamless pipeline for data extraction, transformation, and visualization using **MySQL** for database management and **Tableau** for creating visual insights.

---

## Objectives
1. **Revenue Analysis**:
   - Visualize revenue trends over the last 4 years.
   - Identify patterns, peaks, and dips in revenue across different time periods.
2. **Dynamic Updates**:
   - Ensure that visualizations update automatically whenever the database is modified.
3. **Database Integration**:
   - Create and manage relationships between tables in Tableau to provide comprehensive insights.
4. **Business Impact**:
   - Provide a centralized view of revenue performance for stakeholders to aid in data-driven decision-making.

---

## Project Workflow
1. **Database Setup**:
   - A database was created using **MySQL Workbench**, and a SQL text file was used to populate it with 4 years of Atliq Technologies' revenue data.
   - Relationships between tables were designed to ensure data normalization and query efficiency.

2. **Data Connection**:
   - The database was connected to Tableau using its live connection feature.
   - Relationships between tables in Tableau were established to enable dynamic, multi-table visualizations.

3. **Dashboard Creation**:
   - Two dashboards were created in Tableau:
     1. **Revenue Overview Dashboard**:
        - Displays yearly and monthly revenue trends.
        - Highlights the top-performing months and years.
     2. **Detailed Revenue Breakdown Dashboard**:
        - Breaks down revenue by categories such as products, regions, or business units.
        - Allows users to filter and drill down for deeper insights.
        
4. **Dynamic Updates**:
   - Any updates made to the SQL text file in MySQL Workbench are reflected in the dashboards, enabling real-time analytics.

---

## Tools and Technologies
- **MySQL**:
  - Database management for storing and updating the revenue data.
  - SQL text file used to populate and modify the database.
- **Tableau**:
  - Used for connecting to the live MySQL database.
  - Created interactive, visually appealing dashboards to analyze revenue trends.
- **SQL**:
  - Queries for managing data and creating relationships between tables.

---

## Key Features
1. **Real-Time Updates**:
   - Dashboards dynamically update when the MySQL database is modified, ensuring the visualizations reflect the latest data.
   
2. **Interactive Dashboards**:
   - Users can filter data by time period, categories, or regions to tailor insights to their needs.
   
3. **Multi-Table Relationships**:
   - Efficient relationships between tables in Tableau allow for complex queries and detailed visualizations.

4. **Comprehensive Revenue Analysis**:
   - Provides both a high-level overview and detailed breakdown of revenue, empowering stakeholders with actionable insights.

---

## Results and Insights
1. **Revenue Trends**:
   - Identified significant revenue peaks in specific months and years.
   - Highlighted underperforming periods, aiding in future planning.

2. **Category Performance**:
   - Pinpointed top-performing product categories and regions.
   - Enabled granular analysis of business units contributing to revenue.

3. **Dynamic Decision-Making**:
   - Real-time updates allowed for on-the-fly business decisions based on the latest data.

---

## How to Use the Project
1. **Setup MySQL Database**:
   - Import the SQL text file into MySQL Workbench to create and populate the database.
   
2. **Connect to Tableau**:
   - Open Tableau and establish a live connection to the MySQL database.
   - Ensure relationships between tables are correctly set up in Tableau.

3. **View the Dashboards**:
   - Open the Tableau workbook to interact with the dashboards.
   - Apply filters to explore revenue trends and detailed breakdowns.

4. **Update Data**:
   - Modify or append data in the SQL text file and update the MySQL database.
   - Refresh the Tableau dashboards to reflect the latest data.

---

## Contributors
- **Pradipta Dutta** - Data Scientist

