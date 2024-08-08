# Power BI Report - Business Insights 360



## Overview:
AtliQ Hardwares, a leading hardware company specializing in PCs, printers, mousce, and other computer equipment  globally. Their aims to optimize sales strategies and increase net gross margins to drive business growth and profitability.

## Table of Contents:

- [Project Presentation](#project-presentation)
- [Live Dashboard](#live-dashboard)
- [Tools & Technique used](#tools--technique)
- [Problem Statement](#problem-statement)
- [Goal & Purpose](#goal--purpose)
- [Business Model](#business-model)
- [Feature Requests](#feature-requests)
- [Data Source](#data-source)
- [Data Modeling](#data-modeling)
- [Key Metrics](#key-metrics)
- [Dashboard Overview](#dashboard-overview)
- [Insights & Recommendations](#insights-and-recommendations)


## Project Presentation:

<p align="center">
<a href="https://youtu.be/YsVGcfzoxJg" target="_blank">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/presentation%20preview.png" alt="Presentation Preview" style="width: 70%; max-width: 360px;">
  
</a>
</p>

## Live Dashboard:

Checkout the live dashboard here 👉🏻 [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzQ4NTQ4NmItZmFhMi00MzNkLTg1NjktNjUxNTcxNzU5OTY3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


## Tools & Technique:
- Data Analysis
   - Microsoft Excel (v 2021)
   - Microsoft Power BI Desktop (v July2024)
   - Power BI Service
   - Power Query
   - Data Modeling
   - DAX (Data Analysis Expression)
   - ETL (Extract, Transformation & Load)
   - Dax Studio

- Database
   - SQL
   - MySQL & MySQL Workbench

- Project Documentation
   - Git & Github
   - VS Code Editor

- Video Recording & Presentation
   - OBS Studio
   - Microsoft Clipchamp - Video Editor
   - Microsoft Power Point

## Problem Statement:
AtliQ Hardware is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America.

Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.

## Goal & Purpose:
This Project is expected to improve the transparency and enable data driven decision-making across markets & functions.And therefore deliver a quantitative benefit of 10% incremental profit 

## Business Model:

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/BM1.png" alt="Business model Preview" >
</p>

&rarr; AtliQ is a manufacturer for Computer Hardwares and manufacture different products. These products are then sent from factory to their warehouse.

&rarr; From warehouse, AtliQ send the products to different Stores like croma, flipkart etc. to sell their products. From these stores people can buy AtliQ products. AtliQ don't sell their products directly to the end user.

&rarr; The stores whom AtliQ sell their product, are called **_Customer_** and People who consume AtliQ's products, are called **_Consumer_**. (Refer to above picture for better understanding)

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/BM2.png" alt="Business model for Customer Preview" >
</p>

&rarr; Stores (Platform) are mainly 2 types:

- **Brick & Mortar** - Physical Store where people can visit and purchase the products according their choice. Ex.- Croma.

- **E-Commerce** - Online Store where people buy their products through internet, can't visit in person. Ex.- Amazon, Flipkart etc.

&rarr; AtliQ sell their products through 3 different Channel:

- **Retail** - Third Party owned store like Croma, Amazon etc.

- **Direct** - Owm store like AtliQ e-store, AtliQ exclusive.

- **Distrributor** - Agency who distribute AtliQ's product in different countries like china, South Africa etc where AtliQ can't sell their products directly in that countries due to govt. policies and other restriction. Ex.- Neptune. (Refer to above picture for better understanding) 
  
## Feature Requests:

Product Owner provided the features which should be implemented into the Power BI Report.

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/FR.png" alt="Feature Request Preview" >
</p>

## Data Source:

There are mainly 2 types of Data Source are used for this project.

- AtliQ Internal Database:
<br>&rarr; Look at the below images for the database structure. There are 2 different Database which contains all _Fact_ & _Dimension_ tables.

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/database-structure/database1.png" alt="Database 1 Preview" >
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/database-structure/database2.png" alt="Database 2 Preview" > </p>

- External .xlsx/.csv file:
<br>&rarr; For target data (Benchmark) and Market Share data, I have used external excel files.

> [!NOTE]
> At AtliQ Fiscal Year starts from September. For this project, I have taken dataset available from Fiscal Year 2018 to Fiscal Year 2022. Last Sales data is available till Dec 2021 (Calendar Year). Target data is only available for Fiscal Year 2022.

> [!IMPORTANT]
> Fiscal Year is referred to as Financial Year.



## Data Modeling
Here you can check the Data Model which is used for this project. In center you can see there are _Fact_ tables which are connected with different _Dimension_ tables. Few _Dimension_ tables are also connected with another _Dimension_ tables.

That's why this Data Model is mixed of **STAR** and **Snowflake** schema.

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/data-modeling/data-modeling.gif" alt="Data Model Preview" >
</p>

## Key Metrics:

- Gross Sales
- Pre & Post Invoice Deduction
- Net Sales
- COGS (Cost of Goods Sold)
- Gross Margin (GM)
- Gross Margin % (GM%)
- Operational Expenses 
- Net Profit (NP)
- Net Profit % (NP%)
- Forecast Accuracy % (FCA%)
- Net Error
- Absolute Error
- Revenue Contribution % (RC%)

## Dashboard Overview:

<p align="center"> Home Page </p>
<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/home.png" alt="Home Page">
</p>

<p align="center"> <strong>Finance Page </strong></p>
<p align="center"> Get P & L statement for any customer / product / country or aggregation of the above over any time period and More. </p>

<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/finance.png" alt="Finance Page">
</p>

<p align="center"><strong> Sales Page </strong></p>
<p align="center"> Analyze the performance of customer(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix. </p>

<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/sales.png" alt="Sales Page">
</p>

<p align="center"><strong> Marketing </strong></p>
<p align="center"> Analyze the performance of product(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix. </p>

<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/marketing.png" alt="Marketing Page">
</p>

<p align="center"><strong> Supply Chain Page </strong></p>
<p align="center"> Get Forecast Accuracy, Net Error and risk profile for product, segment, category, customer etc
A top level dashboard for executives consolidating top insights from all dimensions of business </p>

<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/supply-chain.png" alt="Supply Chain Page">
</p>

<p align="center"><strong> Executive Page </strong></p>
<p align="center"> A top level dashboard for executives consolidating top insights from all dimensions of business.
 </p>

<p align="center">
  <img src="https://raw.githubusercontent.com/PuranjoyPatra/Business-Insights-360/master/images/executive.png" alt="Executive Page">
</p>


## Insights and Recommendations: 

### Finance View

1. **Enhance Business Laptop Profitability:**
   - **Observation:** Business Laptops have the highest net sales at $765.25M but show a significant decline in net profit.
   - **Recommendation:** Focus on cost reduction strategies for Business Laptops, such as optimizing manufacturing and freight costs. Additionally, consider revising pricing strategies to improve profit margins.

2. **Target High-Growth Categories for Marketing:**
   - **Observation:** Gaming Laptops and Personal Laptops show substantial growth in net sales (688.58% and 377.41%, respectively).
   - **Recommendation:** Invest in targeted marketing campaigns to further boost sales in these high-growth categories. Highlight unique features and benefits to attract more customers and capitalize on the growing demand.

3. **Optimize Costs to Improve Gross Margin:**
   - **Observation:** The gross margin percentage has improved slightly to 38.08%, but operational expenses are significantly high.
   - **Recommendation:** Implement cost-saving measures across the supply chain, focusing on reducing manufacturing, freight, and other operational costs. Streamline processes to enhance efficiency and improve the overall gross margin.

4. **Focus on Underperforming Products:**
   - **Observation:** Personal Desktops and Processors have lower net sales compared to other categories but show potential for growth.
   - **Recommendation:** Analyze the reasons behind the underperformance of these products. Consider product enhancements, better marketing strategies, or bundling with other high-performing products to boost sales and improve their market position.

5. **Leverage Seasonal Sales Trends:**
   - **Observation:** There are noticeable peaks in net sales performance during specific months (e.g., December 21 with 508M net sales).
   - **Recommendation:** Plan and execute seasonal marketing campaigns to take advantage of these peak sales periods. Offer promotions, discounts, and special deals during these times to maximize sales and improve overall revenue.

### Sales View

1. **Focus on Top-Performing Products:**
   - **Observation:** The AQ Smash 1 and AQ 5000 Series Ultron 8 are the top-performing products with the highest net sales ($142.46M and $91.66M, respectively) and strong gross margins.
   - **Recommendation:** Allocate more marketing and sales resources to these products to further boost their sales and profitability. Consider offering bundle deals or promotions to increase their market penetration.

2. **Address Declining Gross Margins:**
   - **Observation:** Several products, such as AQ Clx3, AQ Dracula HDD, and AQ 5000 Series Ultron 8, are experiencing declines in gross margin percentage.
   - **Recommendation:** Conduct a thorough cost analysis to identify areas where costs can be reduced. This might include renegotiating supplier contracts, improving manufacturing efficiency, or reducing overhead costs.

3. **Improve Sales Strategies for Underperforming Products:**
   - **Observation:** Products like AQ Clx3 ($13.35M) and AQ Dracula HDD ($8.53M) have lower sales and declining gross margins.
   - **Recommendation:** Reevaluate the sales strategies for these products. Consider whether price adjustments, enhanced marketing efforts, or product improvements could help improve their market performance.

4. **Reduce Pre and Post-Invoice Deductions:**
   - **Observation:** Pre-invoice and post-invoice deductions are significantly impacting the net sales, with deductions totaling 49.3% of gross sales.
   - **Recommendation:** Implement stricter policies and monitoring to minimize deductions. This could include better contract management with customers and suppliers, as well as improved internal controls and verification processes.

5. **Leverage Successful Customer Segments:**
   - **Observation:** Amazon and AtliQ Exclusive are high-performing customer segments, contributing significantly to net sales.
   - **Recommendation:** Strengthen relationships with these key customers by offering exclusive deals, tailored marketing campaigns, and priority support. Explore opportunities for collaboration and joint marketing efforts to maximize sales potential.


### Marketing View

1. **Focus on Improving Net Profitability for High Revenue Categories:**
   - **Observation:** Business Laptops and Personal Laptops have high net sales ($765.25M and $202.52M, respectively) but significant negative net profit percentages (-13.79% and -14.91%).
   - **Recommendation:** Implement cost reduction strategies for these high-revenue categories, such as optimizing supply chain costs, renegotiating supplier contracts, and improving operational efficiencies. Additionally, consider price adjustments or product mix optimizations to enhance profitability.

2. **Address Underperforming Categories with High Net Profit Declines:**
   - **Observation:** Motherboards, External Solid State Drives, and Personal Desktops show substantial negative net profits and high percentage declines in net profit.
   - **Recommendation:** Conduct a detailed analysis to identify the root causes of the declines in these categories. Consider strategic actions such as discontinuing underperforming products, revising pricing strategies, and investing in marketing efforts to boost sales. Also, explore ways to reduce production and distribution costs.

3. **Leverage High Gross Margin Categories:**
   - **Observation:** Categories like Wi-Fi Extenders and Internal HDDs have gross margins of 38.25% and 38.45%, respectively, but still show negative net profits.
   - **Recommendation:** Focus on increasing sales volumes and reducing operational expenses for these high gross margin categories. Invest in targeted marketing campaigns to drive demand and consider bundling these products with complementary items to boost overall sales and profitability.

4. **Enhance Marketing for Gaming Laptops and Graphic Cards:**
   - **Observation:** Gaming Laptops and Graphic Cards have significant net sales ($619.25M and $233.69M) and relatively lower negative net profits (-13.14% and -14.52%).
   - **Recommendation:** Allocate more marketing resources to these categories to capitalize on their strong market presence. Promote new features, performance benefits, and competitive pricing to attract more customers. Additionally, explore partnerships with gaming influencers and esports events to increase brand visibility and demand.

5. **Optimize Inventory and Supply Chain Management:**
   - **Observation:** The overall gross margin is 38.1%, but the net profit is significantly negative (-13.97%), indicating high operational expenses.
   - **Recommendation:** Implement robust inventory and supply chain management practices to reduce operational expenses. This can include better demand forecasting, just-in-time inventory management, and enhancing supplier relationships. Streamlining operations will help reduce costs and improve net profitability across all categories.

### Supply Chain View

1. **Improve Forecast Accuracy for Key Customers:**
   - **Observation:** The Forecast Accuracy (FCA%) is 81.17% overall, but there are significant variances among customers. Notably, Expert and Acclaimed Stores have FCA% below 63%.
   - **Recommendation:** Enhance forecasting techniques and collaboration with key customers like Expert and Acclaimed Stores to improve accuracy. Implement advanced demand forecasting tools and better communication channels to reduce forecast errors.

2. **Address Excess Inventory (EI) Risks:**
   - **Observation:** Multiple customers and segments are flagged with Excess Inventory (EI) risks, including Acclaimed Stores and Staples, as well as the Accessories and Desktop segments.
   - **Recommendation:** Implement inventory optimization strategies such as better inventory management practices, regular stock reviews, and promotions to clear excess stock. Consider offering bundle deals or discounts on slow-moving inventory to reduce excess stock levels.

3. **Reduce Out of Stock (OOS) Incidents:**
   - **Observation:** Several key customers and product segments are facing Out of Stock (OOS) risks, such as Amazon, AtliQ Exclusive, and the Networking segment.
   - **Recommendation:** Strengthen supply chain resilience by improving supplier relationships, increasing safety stock levels for high-demand products, and using real-time inventory tracking systems. Enhance supply chain visibility to anticipate and mitigate potential stockouts.

4. **Optimize Supply Chain for High Net Error Segments:**
   - **Observation:** The Net Error for the overall supply chain is -$3M, with significant contributions from customers like Amazon (-$456K) and product segments like Peripherals (-$320K).
   - **Recommendation:** Conduct a root cause analysis for the high net errors and address underlying issues such as inaccurate demand forecasting, inefficient supply chain processes, or inadequate stock management. Implement corrective actions to minimize these errors and improve overall efficiency.

5. **Focus on High-Risk Customers and Segments:**
   - **Observation:** Key customers like Amazon and AtliQ Exclusive, and segments like Accessories and Peripherals, are highlighted as high risk (OOS or EI).
   - **Recommendation:** Prioritize these high-risk areas by developing targeted action plans to address specific risks. For example, for Amazon, reduce forecast errors and improve stock availability. For Accessories, implement strategies to clear excess inventory and avoid stockouts.


### Executive View

1. **Boost Net Sales and Reduce Excess Inventory:**
   - **Observation:** Net Sales (NS) is at $3.74bn, below the benchmark of $3.83bn. The LATAM and NA sub-regions are showing excess inventory (EI).
   - **Recommendation:** Implement targeted marketing campaigns in the LATAM and NA sub-regions to boost sales and reduce excess inventory. This can include promotions, discounts, and localized marketing strategies to increase demand.

2. **Improve Gross Margin (GM%) in Key Sub-Regions:**
   - **Observation:** The overall GM% is 38.1%, with significant variations across sub-regions. India has a high GM% of 45.74%, while NE and ROA are much lower at 23.90% and 21.13%, respectively.
   - **Recommendation:** Focus on strategies to improve GM% in NE and ROA, such as negotiating better terms with suppliers, optimizing the product mix, and improving operational efficiencies.

3. **Enhance Profitability with Key Customers:**
   - **Observation:** Amazon is the top customer, contributing 13.18% to revenue but with a GM% of only 36.81%. AtliQ Exclusive has a high GM% of 40.67%.
   - **Recommendation:** Work on improving profitability with Amazon by reducing deductions and operational costs. Additionally, leverage the high GM% from AtliQ Exclusive by offering exclusive products and promotions through this channel to drive higher-margin sales.

4. **Expand Successful Product Lines:**
   - **Observation:** The top products, such as AQ HOME Allin1 Gen 2, show high revenue contribution (RC%) and gross margin (GM%). AQ BZ Allin1 Gen 2 has a GM% of 39.45%.
   - **Recommendation:** Expand the successful product lines by increasing their availability and visibility in key markets. Consider introducing new variants or complementary products to capitalize on their success.

5. **Targeted Sales Growth in High Potential Sub-Regions:**
   - **Observation:** The Networking and Storage division shows favorable margins and net profits despite low sales.
   - **Recommendation:** Focus on driving sales growth in the Networking and Storage division by increasing marketing efforts and sales incentives in sub-regions with high potential. Highlight the profitability of this division to attract more customers.


