# Business-Insights-360

 # 📊 AtliQ Hardware Business Insights 360 – Power BI Project

   🌟 Project Overview

AtliQ Hardware has experienced rapid growth in recent years. To stay competitive and enable data-driven decision-making, the company invested in building an analytics solution using Power BI.

This project delivers a comprehensive Business Insights 360 dashboard that helps stakeholders answer critical questions across Finance, Sales, Marketing, Supply Chain, and Executive functions.

The project was developed as part of the Codebasics Power BI Course and focuses on transforming raw business data into actionable insights.

🔗 Live Report: https://app.powerbi.com/view?r=eyJrIjoiOWZhYmJiYWQtYmE1MC00ODRlLWIzZjAtMDJkZDc2YTY1YmMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9



## 💻Tech Stack

The dashboard was built using the following tools and technologies:

 - 🐬 SQL
   
 - 📊 Power BI Desktop

 - 📈 Microsoft Excel

 - 🧮 DAX (Data Analysis Expressions)

 - ⚡ DAX Studio (Performance Optimization)

 - 📜 Project Charter File

 - 🌐 Power BI Service

 - 🐙 GitHub 



### 🛠️Power BI Skills & Techniques Applied

 - 🧠 Key questions to ask before starting a project

- 🧮 Creating calculated columns

- 🔢 Creating measures using DAX language

- 🗂️ Data modeling

- 📑 Using Bookmarks to switch between visuals

- 🖱️ Page navigation with buttons

- ➗ Using the DIVIDE function to prevent zero division errors

- 📅 Creating a date table using M language

- 🏷️ Dynamic titles based on applied filters

- 📊 Using KPI indicators

- 🎨 Conditional formatting in visuals using icons or background color

- ✔️ Data validation techniques

- 🌐 PowerBI Services

- 🚀 Publishing reports to PowerBI Services

- 🔄 Setting up a personal gateway for automatic data refresh

- 📱PowerBI App creation

- 🤝 Collaboration, workspace management, and access permissions in PowerBI Services

And more




- 📚Business Concepts Covered

   - 💵 Gross Price

   - 📉 Pre-Invoice Deductions

   - 🧾 Net Invoice Sales

   - 📈 Post-Invoice Deductions

   - 💲 Net Sales

   - 🏷️ Cost of Goods Sold (COGS)

   - 💰 Gross Margin

    - 💸 Net Profit

   - 📆 Year-To-Date (YTD)

   - 📅 Year-To-Go (YTG

   - Sales Channels

       - 🛒 Direct

       - 🏬 Retailer

       - 📦 Distributor

       - 👥 Consumer



- 🏢Company Background

AtliQ Hardware is a global manufacturer and distributor of computers and computer accessories.
The company operates through three primary channels:

   - 🏬 Retailers

   - 🛒 Direct Sales

   - 📦 Distributors

Recently, the company faced significant losses after expanding into the American market based primarily on surveys, intuition, and limited Excel analysis. Meanwhile, competitors were leveraging advanced analytics for strategic decisions.

To overcome this challenge, AtliQ Hardware initiated a data analytics transformation to support evidence-based decision-making across all business functions.



- ❓Key Business Questions

Before developing the dashboard, the following questions were addressed:

 - ❔ What is the objective of building this PowerBI dashboard?

 -  📏 How will the success of this project be measured?

-    ⏳ What is the project deadline?

 - 👀 Do stakeholders expect a preview before the actual release?

 - 💡 What are stakeholders' hopes for this project?

 - 😟 What are stakeholders' fears regarding this dashboard?

 - 👥 Who will use this dashboard and for what purpose?

 - 🎯 What are stakeholders' expectations by the end of this project?

 - ⚠️ What can go wrong during this project?

 - 📄 What resources/data are needed to build this dashboard?

 - 🖌️ Are there any stakeholder inputs regarding the dashboard's design and views?

 

 ####### 🗄️Dataset Overview

Understanding available data is crucial before analysis. Familiarize yourself with the data:

- Dimension Table: Contains static data like customer and product details.

- Fact Table: Contains transaction data.

⛓️‍💥gbd041

- dim_customer

  - 🌍 27 distinct markets (e.g., India, USA, Spain)
    
  - 👥 75 distinct customers across markets

  - 🏢 2 types of platforms:

          - Brick & Mortar - Physical/offline store

          - E-commerce - Online store (Amazon, Flipkart etc.)
 
  - 🛒 3 channels:

         - Retailer

         - Direct

         - Distributors
 
- dim_market

    - 🌍 27 distinct markets

    - 🌎 7 sub-zones

    - 🌏 4 regions: APAC, EU, NAN, LATAM

- dim_product

     -🏷️ Divisions:

           - P&A (Peripherals, Accessories)

           -PC (Notebook, Desktop)

           -N&S (Networking, Storage)

- 🛍️ 14 different categories (e.g., Internal HDD, keyboard)
- 📦 Various product variants

- fact_forecast_monthly

     -🔮 Forecasts customer needs to improve satisfaction and reduce warehouse costs
     -🗃️ Denormalized by the data engineering team for analytical use
      -📅 Monthly data with forecast quantities

- fact_sales_monthly
 
   💹 Similar to fact_forecast_monthly but includes sold quantities


⛓️‍💥gdb056

- freight_cost
      🚚 Travel and other costs per market with fiscal year

- gross_price
       💲 Gross prices with product codes

- manufacturing_cost
       🏭 Manufacturing costs with product codes and year

- pre_invoice_deductions
       💸 Pre-invoice deductions percentage per customer with year

- post_invoice_deductions
       💰 Post-invoice deductions details




######## 📥 Data Import

Data was imported directly from a MySQL database into Power BI using database credentials provided for the project.



######### 🗂️ Data Model
Data modeling is crucial for report performance. Poor modeling can negatively impact the report. This project uses the Snowfall data modeling method.
![Data Dashboard](image/DataModelling.png)



########## 🎨 Dashboard Views
Based on the received mock-ups, the team will design visuals and create measures as needed.

- 🏠 Home View
The Home view contains buttons to navigate to specific views:

     - ℹ️ Info View
     - 💵 Finance View
      - 📈 Sales View
     - 📊 Marketing View
     - 🚚 Supply Chain View
     - 👔 Executive View
     - 💬 Support View



########### 📸 Dashboard Preview


- Home View 
![Home Dashboard](image/Home.png)

- Finance View  
![Finance Dashboard](image/FinanceView.png)

- Sales View  
![Sales Dashboard](image/SalesView.png)

- Marketing View 
![Marketing Dashboard](image/marketingView.png)

- Supply Chain View 
![Supply Chain Dashboard](image/SupplychainView.png)

- Executive View 
![Executive Dashboard](image/ExecutiveView.png)

- Support 
![Support Dashboard](image/Support.png)

- Info 
![Info Dashboard](image/Info.png) 



############ 🏆 Project Outcome

This Power BI solution empowers stakeholders with a single source of truth for business performance monitoring.

- Key Benefits

      - ✅ Data-driven decision making

      - ✅ Improved visibility across departments

       - ✅ Faster business insights

        - ✅ Enhanced forecasting capabilities

         - ✅ Executive-level KPI monitoring

         - ✅ Ability to answer critical “Why?” questions behind business performance

The dashboard helps AtliQ Hardware move from intuition-based decisions to a data-first culture, enabling smarter strategic planning and sustainable business growth.


############# 🔗 Resources

Codebasics Power BI Course: https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project

Live Dashboard: https://app.powerbi.com/view?r=eyJrIjoiOWZhYmJiYWQtYmE1MC00ODRlLWIzZjAtMDJkZDc2YTY1YmMyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

Project Report (.pbix): https://github.com/ClinicalToCodeTS/Business-Insights-360


👨‍💻 Author

Your Name
Triveni Sharma

