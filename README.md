# Business-Insights-360

1.   📊 AtliQ Hardware Business Insights 360 – Power BI Project

   🌟 Project Overview

AtliQ Hardware has experienced rapid growth in recent years. To stay competitive and enable data-driven decision-making, the company invested in building an analytics solution using Power BI.

This project delivers a comprehensive Business Insights 360 dashboard that helps stakeholders answer critical questions across Finance, Sales, Marketing, Supply Chain, and Executive functions.

The project was developed as part of the Codebasics Power BI Course and focuses on transforming raw business data into actionable insights.

🔗 Live Report: https://app.powerbi.com/view?r=eyJrIjoiOWZhYmJiYWQtYmE1MC00ODRlLWIzZjAtMDJkZDc2YTY1YmMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9



💻 Tech Stack

The dashboard was built using the following tools and technologies:

🐬 SQL
📊 Power BI Desktop 
📈 Microsoft Excel
🧮 DAX (Data Analysis Expressions)
⚡ DAX Studio (Performance Optimization)
📜 Project Charter Document
🌐 Power BI Service
🐙 GitHub 


🛠️ Power BI Skills & Techniques Applied

Data Preparation & Modeling

Data Import from MySQL Database
Data Cleaning & Transformation
Snowflake Data Modeling
Creating Calculated Columns
Creating Measures using DAX
Building Date Tables using Power Query (M Language)
Report Development

KPI Indicators
Dynamic Titles based on Filters
Conditional Formatting
Bookmarks for Visual Switching
Page Navigation using Buttons
Drill-through & Interactive Visuals
DIVIDE Function for Error Handling
Performance Optimization

DAX Studio Performance Analysis
Data Validation Techniques
Report Optimization Best Practices
Power BI Service

Publishing Reports
Setting Up Personal Gateway
Scheduled Data Refresh
Power BI App Creation
Workspace Management
Access Control & Collaboration


📚 Business Concepts Covered

💵 Gross Price
📉 Pre-Invoice Deductions
🧾 Net Invoice Sales
📈 Post-Invoice Deductions
💲 Net Sales
🏷️ Cost of Goods Sold (COGS)
💰 Gross Margin
💸 Net Profit
📆 Year-To-Date (YTD)
📅 Year-To-Go (YTG)
Sales Channels

🛒 Direct
🏬 Retailer
📦 Distributor
👥 Consumer


🏢 Company Background

AtliQ Hardware is a global manufacturer and distributor of computers and computer accessories.

The company operates through three primary channels:

🏬 Retailers
🛒 Direct Sales
📦 Distributors
Recently, the company faced significant losses after expanding into the American market based primarily on surveys, intuition, and limited Excel analysis. Meanwhile, competitors were leveraging advanced analytics for strategic decisions.

To overcome this challenge, AtliQ Hardware initiated a data analytics transformation to support evidence-based decision-making across all business functions.



❓ Key Business Questions

Before developing the dashboard, the following questions were addressed:

What is the primary objective of the dashboard?
How will project success be measured?
What is the expected timeline?
Who are the key stakeholders?
What insights are stakeholders expecting?
What potential risks could impact the project?
What resources and datasets are required?
Are there any design preferences or reporting expectations?


🗄️ Dataset Overview

Dimension Tables

dim_customer

🌍 27 Markets
👥 75 Customers
🏢 Platforms:
Brick & Mortar
E-Commerce
🛒 Channels:
Retailer
Direct
Distributor
dim_market

🌍 27 Markets
🌎 7 Sub-zones
🌏 4 Regions:
APAC
EU
NAN
LATAM
dim_product

🏷️ Divisions:
P&A (Peripherals & Accessories)
PC (Notebooks & Desktops)
N&S (Networking & Storage)
🛍️ 14 Product Categories
📦 Multiple Product Variants


Fact Tables

fact_forecast_monthly

Customer demand forecasts
Monthly forecast quantities
Supports inventory and warehouse planning
fact_sales_monthly

Monthly sales transactions
Sold quantities and revenue analysis


Additional Financial Tables

freight_cost

Market-wise freight and logistics costs
gross_price

Product-level gross pricing information
manufacturing_cost

Product manufacturing costs
pre_invoice_deductions

Customer-specific discount percentages
post_invoice_deductions

Additional invoice deductions and adjustments


📥 Data Import

Data was imported directly from a MySQL database into Power BI using database credentials provided for the project.



🗂️ Data Model

A Snowflake Schema data model was implemented to ensure:

Better scalability
Efficient query performance
Easier maintenance
Optimized reporting experience
Well-structured data modeling is one of the most critical factors affecting Power BI report performance.



🎨 Dashboard Views

🏠 Home Page

Central navigation hub with buttons to access:

ℹ️ Info View
💵 Finance View
📈 Sales View
📊 Marketing View
🚚 Supply Chain View
👔 Executive View
💬 Support View


📄 Dashboard Pages

 ℹ️ Info View
 
    Project Overview and navigation guide.

💵 Finance View

Revenue, profitability, gross margin, and financial KPIs.

📈 Sales View

Customer performance, product sales, and market analysis.

📊 Marketing View

Marketing effectiveness and product performance insights

🚚 Supply Chain View

Forecast accuracy, inventory planning, and supply chain performance.


👔 Executive View

High-level business KPIs for leadership decision-making.

💬 Support View

Additional information and report support details.


🏆 Project Outcome

This Power BI solution empowers stakeholders with a single source of truth for business performance monitoring.

Key Benefits

✅ Data-driven decision making

✅ Improved visibility across departments

✅ Faster business insights

✅ Enhanced forecasting capabilities

✅ Executive-level KPI monitoring

✅ Ability to answer critical “Why?” questions behind business performance

The dashboard helps AtliQ Hardware move from intuition-based decisions to a data-first culture, enabling smarter strategic planning and sustainable business growth.



📸 Dashboard Preview


Home View 
![Home Dashboard](image/Home.png)

Finance View  
![Finance Dashboard](image/FinanceView.png)

Sales View  
![Sales Dashboard](image/SalesView.png)

Marketing View 
![Marketing Dashboard](image/marketingView.png)

Supply Chain View 
![Supply Chain Dashboard](image/SupplychainView.png)

Executive View 
![Executive Dashboard](image/ExecutiveView.png)

Support 
![Support Dashboard](image/Support.png)

Info 
![Info Dashboard](image/Info.png) 



🔗 Resources

Codebasics Power BI Course: https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project
Live Dashboard: https://app.powerbi.com/view?r=eyJrIjoiOWZhYmJiYWQtYmE1MC00ODRlLWIzZjAtMDJkZDc2YTY1YmMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
Project Report (.pbix): Add Repository File Link


👨‍💻 Author

Your Name

If you found this project helpful, consider giving it a ⭐ o

itHub!
:::

This version is structured to look professional and recruiter-friendly while following common GitHub analytics project standards.
