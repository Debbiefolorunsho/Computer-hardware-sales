# Computer-software-sales

## Executive Summary
This project offers an in-depth analysis of sales in the computer software industry, focusing on key insights derived from data obtained from [Maven's Analytics](https://mavenanalytics.io/challenges). The dataset underwent significant transformations to unveil valuable trends and patterns, providing valuable insights into sales performance and market dynamics within the software sector.
## Project Description
- **Goals:** The goal of the project was to create a dynamic and interactive Power BI dashboard that enables sales managers to track their team's quarterly performance effectively.
- **Business Needs:** The business needed a solution to visualize and analyze key sales metrics such as revenue, sales agents' performance, deal stages, and quarterly trends.
- **Insights Discovery:** Through data exploration and visualization techniques, insights were discovered on total revenue, sales agents' contributions, deal stages comparison, and quarterly revenue trends.
- **Presentation:** The insights were presented using various visualizations including cards for key metrics, slicers for filtering data, column charts for top performers, area charts for trend analysis, and pie charts for deal stage comparison, providing a comprehensive view of sales performance.

[Click on this to interact with my Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGEyMTE3MGMtZTVhYS00NjYzLTk1MGItZDFmZjRmMDNjN2E1IiwidCI6IjFkZDZlZmUxLTk4MDctNGM1Yy04NzJiLWJmZDExZDIyNGEzMSJ9)

## Overview of the data

The original data was sourced from Maven's Analytics and includes four primary tables: Sales Agents, Accounts, Products, and Sales Pipeline. The data encompasses various aspects of a fictitious company's B2B sales pipeline in the computer hardware industry.

**Sales Agents Table:**

Columns:
- Sales agent
- Manager
- Regional office
- Sales agent ID
  
**Accounts Table:**

Columns:
- Account (company name)
- Sector
- Year established
- Revenue
- Employees
- Office location
- Subsidiary_of (parent company)
- Account ID
  
**Products Table:**

Columns:
- Product (product name)
- Series
- Sales price
- Product ID
  
**Sales Pipeline Table:**

Columns:
- Opportunity ID (unique identifier)
- Sales agent ID
- Product ID
- Account ID
- Deal stage (sales pipeline stage: prospecting > engaging > won/lost)
- Engage date (date when the engaging deal was initiated)
- Close date (date when the deal was won/lost)
  
**Data Cleaning and Transformation:**

The data underwent significant cleaning and transformation processes using Excel, including:

- Addition of new columns for relationship modeling: Product ID in the Products table, Sales agent ID in the Sales Agents table, and Account ID in the Accounts table.
- Ensuring data consistency and integrity by removing duplicates and blank rows.
- Formatting text columns to ensure uniformity and readability.
- Establishing relationships between tables using unique identifiers for accurate data modeling.

These steps ensured a structured and comprehensive dataset, ready for in-depth analysis and visualization in Power BI.

## Tools And Technologies Used

- **Microsoft Excel:** Microsoft Excel was used at the start of the project to provide an understanding of the data structure, data cleaning and transformation, including the addition of new columns for relationship modeling, before moving to Power BI Query Editor for further transformations.
- **Power Query Editor:** This is an advanced feature of Power BI that allows transformation and cleaning to be carried out on a dataset. The Power Query Editor was used in carrying out transformations across different columns such as removing duplicates, removing blank rows, formatting columns, replacing values, etc.   
- **Power BI:** This was the major tool used in this project. Power BI was used in coming up with the visualization and dashboards for the insights generated from this project. Power BI service, a component of Power BI was also utilized in creating a web link that allows interactivity and navigation with the report.

## Project Workflow

![project workflow](https://github.com/Debbiefolorunsho/Computer-hardware-sales/blob/main/Project%20Workflow.png?raw=true)

**1. Project Objective**
The primary goal of this project is to create a dynamic and interactive Power BI dashboard that enables sales managers to monitor their team's quarterly performance effectively. The dashboard provides comprehensive insights into sales performance, market trends, and opportunity management, supporting strategic decision-making.

**2. Data Collection**
Data for this project was sourced from Maven's Analytics, comprising CRM sales opportunities and B2B sales pipeline data from a fictitious company specializing in computer hardware sales. The dataset includes details on accounts, products, sales teams, and sales opportunities.

**3. Data Cleaning and Preparation**

**Excel:** Initial data cleaning was performed in Excel, where new columns were added to facilitate relationship building during data modeling:
- product_Id to the product table
- sales_agent_Id to the sales team table
- Account_Id to the account table

The cleaned data was then imported into Power BI Query Editor for further transformation, which included:

- Removing duplicates and unwanted columns
- Removing blank rows
- Formatting text columns using Clean, Trim, and Capitalize functions
- Promoting headers and renaming columns for clarity
- Replacing outdated values in date columns
- Appending new queries to fill in missing data for certain periods
  
**4. Data Analysis and Visualization**

Using Power BI, the transformed data was analyzed and visualized. Key measures and visualizations included:

**Measures Created:**
- Total Revenue
- Won Deals
- Lost Deals
- Engaging Deals
- Prospecting Deals
- Total Products
- Total Countries
- Total Accounts
- Total Sales Agent
  
**Visualizations:**
- Total revenue by quarter
- Sales performance by sales agent and manager
- Breakdown of deal stages
- Comparison of top accounts by revenue
- Trends in quarterly revenue
- Overview of engaging, won, prospecting, and lost deals
  
**5. Recommendations**

Based on the insights derived from the dashboard:

- Focus on High Performers: Sales managers should leverage the strategies and approaches used by top-performing agents like Darcel Schlecht to mentor and guide other agents.
- Optimize Sales Strategies: Analyze the characteristics of won deals versus lost deals to refine sales strategies and improve conversion rates.
- Enhance Training Programs: Use the data to identify areas where sales agents may need additional training or support, particularly in converting engaging and prospecting deals into won deals.
- Monitor Market Trends: Continuously track and analyze market trends to stay ahead of competitors and adjust sales strategies accordingly.
- Strengthen Key Accounts: Focus on strengthening relationships with top accounts that contribute significantly to revenue, ensuring their needs are met and exploring opportunities for upselling and cross-selling.
