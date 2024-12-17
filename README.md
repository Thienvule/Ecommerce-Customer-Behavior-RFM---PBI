# The Customer Conundrum: Why a Surge in Customers Isn't Translating to Sales Growth - Design Thinking Based Project

## Project Overview: 
As a data analyst, I was tasked with investigating why Adventure Works, a bicycle manufacturer, was experiencing stagnant sales despite a significant increase in customers. In this project, I'll walk you through my analysis applying a human centric concept called Design Thinking, from data preparation to insights, and reveal the surprising reasons behind this paradox.

### Background
During a monthly review at Adventure Works, the sales team was filled with optimism as they celebrated a significant increase in new customers. However, the mood shifted when the sales manager posed a critical question: “Why aren’t our sales figures reflecting this growth?”

Determined to uncover the truth behind this paradox, I initiated an analysis to explore customer behavior, purchasing patterns, and sales trends. My goal was to determine why Adventure Works, despite its expanding customer base, was experiencing stagnant sales and to provide actionable insights to turn the tide.

### Insights and recommendations are provided on the following key areas:
- Design Thinking Process: Implement a comprehensive Design Thinking approach that begins with empathetic engagement with stakeholders to understand their needs and perspectives. Clearly define the core problem, brainstorm innovative solutions, and ultimately develop an interactive dashboard that effectively highlights critical insights and actionable items for stakeholders.
- Sales Trend Analysis: Conduct an in-depth evaluation of historical sales trends, focusing on key performance metrics including total sales volume, total number of orders, and average order value (AOV). This analysis should aim to identify patterns, anomalies - potential symptoms, and opportunities for growth based on historical data.
- Segment Analysis: Employ RFM (Recency, Frequency, Monetary) segmentation to gain deeper insights into customer behaviors. This approach will enable the formulation of targeted strategies to prioritize high-value customer segments while developing plans to engage and convert lower-value segments. Additionally, this analysis will address the paradox of increased customer acquisition alongside stagnant sales figures.
- Product Analysis: Execute a detailed analysis of Adventure Work's diverse product lines to assess their individual contributions to overall sales performance. This examination will help identify which products resonate most with specific customer segments, facilitating better-targeted marketing and inventory decisions.

Note: To ensure clarity and prevent information overload, the technical details including tools and data structures of the project will be provided in the final section of this README file.

## Design Thinking Process

### Stage 1: Empathizing
When the sales manager approached me with her question, I realized that to address her concerns effectively, I needed to see things from her perspective. Therefore, I focused on the empathy stage.

Understand the needs of Adventure Works' sales manager by asking key questions:
- Who are my stakeholders or who are the people viewing my dashboard?
  => Sales manager, sales team, marketing team => Use their language in my dashboard
- What are the goals of the stakeholders?
  => Gain insights into customer behaviors => Need something that helps identify which factors affect the buying decision
  => Analyze the disparity between customer growth and sales figures
  => Review the current sales performance landscape
- What challenges do they face in converting customers to sales?
  => Need a way to analyze the customer base.
- When do the stakeholders need my dashboard?
  => During meetings and discussions focused on analyzing insights, an interactive dashboard with preview insights could provide valuable assistance.
- Where do they see potential improvements in the sales process?
  => The sales trend, CLV, customer location, factors affecting buying decision, what products bring the highest revenue might reveal insights.
- Why is understanding customer behavior important to them?
  => The surge in customers without a corresponding increase in sales raises numerous questions. Stakeholders need to understand this disconnect in order to adjust their sales and marketing strategies effectively.
- How can I support their efforts to boost sales?
  => An interactive dashboard utilizing RFM analysis, along with my insights, can be invaluable. This tool will enable stakeholders to engage in informed discussions and explore further investigations based on the data presented.

#### Empathy map
- Thinking:
  - Why isn’t the surge in customer numbers reflected in sales?
  - Where have we gone wrong in our strategy?
- Feeling: Frustration and concern about performance as the reason has yet to be revealed.
- Seeing: What does the stakeholder see?
  - Indicators of stagnation in sales.
  - Evidence of customer attrition.
- Saying:
  - "Should we invest more in acquiring new customers?"
  - "Is my team underperforming?"
- Pain Points: Increased efforts in marketing and competitive pricing have not resulted in expected sales growth.
- Gains from Solving This Problem: Ability to engage customers more effectively, leading to improved sales performance. 


### 2. Stage 2: Define Problem
Define Northstar metric, relevant dimensions, and metrics.
- Northstar Metric: Focus on Sales as the key measure of success to directly address why increasing customer numbers aren’t driving revenue.
  - Relevant metrics: Total orders, AOV, Total customers, Customer Lifetime value 
- Point of View: Use RFM dimensions (Recency, Frequency, Monetary) to segment customers and identify their unique characteristics.
  - Dimensions to be used: Date, RFM segments, geography, product, customer profile
From these metrics and dimensions, I will try to formulate a strategy to enhance engagement with high-value customer segments to drive sales growth.

### Stage 3: Ideate
Develop a customer-centric approach to uncover the underlying reasons for stagnating sales.
- Start with a Sales Overview, analyzing products, segments, and locations to identify initial indicators of the issue.
- Conduct a year-over-year sales analysis to pinpoint which metrics clearly reveal the root cause of the problem.
- Deep dive into customer segments to gain insights into their behaviors and preferences.
- Examine product performance to determine the most effective strategies for engaging each segment.
### Stage 4: Prototype
Develop an Interactive Dashboard to visualize RFM segments alongside sales data, helping stakeholders explore customer contributions to sales. Refine it based on user feedback for clarity and impact.



## Interactive Dashboard and Pre-Insights
### Overview of findings
Sales Trend Analysis
![image](https://github.com/user-attachments/assets/aa6ba055-b30d-4cad-8fac-85039188f875)
This tab can help stakeholders understand what is going on with the Northstar metrics and relevant metrics using different dimensions, immediately granting insights of the how different customer segments or product categories are performing.

![image](https://github.com/user-attachments/assets/57faece2-02f9-4038-bc8d-e228d8bc67dc)

This sheet can help stakeholders know how different territories are doing.


#### Symptom

- Overall Sales Decrease in 2014 (24%): Indicates a need for a detailed investigation to determine underlying causes.
- Increased Customer Base, Lower Average Order Value (AOV): Despite having more customers, the decline in AOV suggests possible pricing issues or changes in product mix.

Segment Analysis
Increased Sales:
- About to Sleep: Identify strategies that effectively re-engage these customers; analyze successful touchpoints.
- Champions / Loyal: Review and reinforce successful engagement and retention strategies that are keeping these segments engaged.
- Need Attention: Evaluate current strategies' effectiveness in engaging these customers and plan adjustments if necessary.

Sales Decrease:
- At Risk: Assess churn risks and develop targeted retention strategies.
- Cannot Lose Them / Potential Loyalist: Identify what makes these customers leave us and design specialized retention and loyalty programs.

- No Change:
- Hibernating / Lost Customer: Analyze the reasons for stagnation or decline; create reactivation campaigns tailored to these segments.
- New Customers / Promising: Continue successful onboarding and engagement strategies to encourage progression along the customer lifecycle.

Product Analysis
- Components & Clothing: Conduct an in-depth analysis to identify trends or issues affecting sales; explore areas like market demand, competition, or internal product issues.

Geo Analysis
- Decreasing sales: Why do sales in these regions decreased significantly (South West, Canada, Central, South East, North East)

But first, let's deep dive into other dimensions. 

#### YOY Analysis 
These 3 tabs allow stakeholders to dive deeper to the metrics, signaling issues in AOV.
YOY_Sales
![image](https://github.com/user-attachments/assets/0e698113-4948-48dd-a509-3b96dea5be5b)

YOY_Order
![image](https://github.com/user-attachments/assets/dbf3f77c-fe37-4031-8ef0-c103c958f2d8)

YOY AOV
![image](https://github.com/user-attachments/assets/006672bd-e0e1-487a-a640-b85b4136d386)

YOY Insights
Overall sales are on the rise, with a remarkable 300% increase in total orders, indicating positive momentum. However, there is a concerning significant decline in Average Order Value (AOV) across all segments.
A large share of the order increase is driven by new and promising customers, while orders from our top segments are decreasing.
Now, let's examine the profile of our customers.


#### Segment Analysis
Map_Segment: Allow stakeholders to intepret where our customers are and what is happening to them
![image](https://github.com/user-attachments/assets/c9309f5b-acd7-4865-bb41-faadb8c9cfd6)

Existing vs New
This tab reveals why sales is not reflected by the surge in customers.
![image](https://github.com/user-attachments/assets/bc4faf42-df66-4d78-b1f7-1408465f2b81)

Segment Detail
This tab helps stakeholders to analyze segments in a much deeper granularity to decide the coming approaches to each critical segments.
![image](https://github.com/user-attachments/assets/516f46d4-b64c-4179-8ace-f1f667762bb7)

Segment Insights
1. Customer Lifetime Value: Customer Lifetime Value: To enhance sales, it’s optimal to allocate our resources towards the Champions, Potential Loyalists, Can't Lose Them, At Risk, and Loyal segments.
2. At Risk
Observation: An increasing number of customers are becoming at risk, as reflected by declining sales, which signals potential disengagement.
3. Cannot Lose Them
Observation: This segment is experiencing a significant decrease.
Action Needed: Determine whether these customers have transitioned to higher segments or if we have lost them entirely.
4. Potential Loyalist: There are more customers and an increase in orders, but the Average Order Value (AOV) is significantly lower.
5. Concern for Manufacturers
Observation: Customers in the At Risk and Cannot Lose Them segments are particularly attentive to issues related to manufacturers.
Action Needed: Investigate any potential problems with our manufacturers that could be affecting customer loyalty.
6. Price Sensitivity in Other Segments
Observation: Other segments are influenced by pricing and promotions.
Action Needed: For each segment experiencing a sales decline, analyze the reasons behind their decreased purchasing behavior.

#### Product Analysis
Product Details: This helps to understand why each type of customer buy our product, leading to better product improvements.
![image](https://github.com/user-attachments/assets/73874738-5d0e-4eca-a57c-3e128299f1bd)

Product Insights
- At Risk: Investigate the quality and manufacturer of top products to identify any potential issues.
- Potential Loyalists: Develop better upselling strategies for the products frequently purchased by this segment.
- Cannot Lose Them: In addition to assessing pricing, evaluate promotions, manufacturer reputation, product quality, and customer reviews to pinpoint any underlying issues.


#### Recommendation Summary
- Address Lower Average Order Value (AOV): A declining AOV despite increased customer numbers indicates potential pricing issues that need correction to maximize revenue.
- Implement Targeted Re-Engagement Campaigns for “About to Sleep” Customers: Re-engaging customers who are showing signs of activity can convert them back into regular purchasers, driving sales.
- Enhance and Personalize Loyalty Programs for Champions: Retaining loyal customers is often more cost-effective than acquiring new ones. Personalized rewards improve customer stickiness.
- Develop Targeted Retention Initiatives for At Risk Customers: Proactively addressing the needs of at-risk customers can reduce churn and maintain revenue streams, starting from investigating the manufacturers and product quality.
- Conduct Exit Surveys for Cannot Lose Them Customers: Understanding why these valued customers haven't come back in 2014 is crucial for creating targeted strategies to win them back.
- Launch Reactivation Campaigns for Hibernating/Lost Customers: Reactivating disengaged customers can yield quick revenue gains by re-establishing previous relationships.
- Continue Onboarding New Customers: Smooth and engaging onboarding increases the likelihood that new customers will become repeat buyers, enhancing long-term value. It seems like we are doing a great job (a great surge in total order coming from New and Promising customers)
- Conduct Market Analysis for Components & Clothing: Identifying trends or shifts in consumer preferences can help adapt product offerings to better meet market demand.
- Investigate Causes of Decreased Sales in Specific Regions: Localized issues may require tailored strategies, ensuring marketing efforts align with regional customer needs.
- Assess Product Quality and Manufacturer Reliability: Poor product quality or unreliable suppliers can lead to customer dissatisfaction, impacting loyalty and sales.
- Enhance Pricing and Promotion Strategies: Understanding price sensitivity in various segments allows for more effective pricing strategies that can boost sales.
- Develop Upselling Tactics for Potential Loyalists: Improving upselling effectiveness helps increase AOV, contributing to greater overall profitability.

Note: As AOV is the problem, the coming strategies should facilitate boosting AOV, such as better upselling tactics. 
After utilizing this interactive dashboard, stakeholders will gain insights into why the surge in customers isn’t reflected in sales, allowing them to adjust their current approach and achieve better results.

## Technical preparation
### Data Preparation with Power Query (ETL)
- Extract: Import data from various sources, such as sales records, customer databases, and product data. 
- Transform: Clean and preprocess the data by removing duplicates, handling missing values, and applying necessary transformations to ensure data accuracy. 
- Load: Load the clean data into Power BI for analysis.

### Crafting Table Relationship and Data Models
![image](https://github.com/user-attachments/assets/0a937b83-1330-4da7-b199-a0c2032e3b4d)

In this projects, I will utilize data from these sets of the database on BigQuery:
Person: This dataset contains crucial information about customers that is essential for the segmentation process.

![image](https://github.com/user-attachments/assets/9d93b342-f236-42fa-94f6-13f54beb4733)

Production: This dataset offers valuable insights into the products, supporting our initial analysis of product performance.
![image](https://github.com/user-attachments/assets/3bee82c5-3684-43da-9b6d-17b3f92aa991)

Sales: This dataset is highly relevant, as it allows us to analyze sales trends alongside customer performance.
![image](https://github.com/user-attachments/assets/bac6a325-6ff9-4aaf-b7db-7b5ef6102f80)


![image](https://github.com/user-attachments/assets/4cd81c71-cc1a-4736-b2c7-f268643d35b3)

- Create Relationships: Establish relationships between different tables to enable comprehensive analysis. In this stage, the tables corresponding to the insights generated during the Ideate phase will be selected, in which the fact table should be the SalesTable table.
- Snowflake Schema: Given the complexity of this dataset, where dimensions contain their own relevant sub-dimensions, we cannot link the Subcategory table directly to the Sales fact table to explore product subcategories in depth. For example:
  ![image](https://github.com/user-attachments/assets/a7ef8b00-b61c-4357-af58-2c46e7c1aa3d)

### Calendar table
A Calendar table is essential for conducting time series analysis. In this scenario, I would create the table using DAX with the following formula:
Calendar = CALENDAR(MIN(SalesTable[OrderDate]), MAX(SalesTable[OrderDate]))
This Calendar table is generated based on the OrderDate from the SalesTable. In addition, other columns such as Year, Week, Start of year, etc. are also added to prepare for a deeper granularity of the Date dimension. 

![image](https://github.com/user-attachments/assets/c7032af2-4df4-49fe-a364-a5284cbaba3b)

Lastly, I group all Date-related aspects to form a hierarchy of Date, including Year, Quarter, Month, and Day.

![image](https://github.com/user-attachments/assets/37b2c579-2297-48f4-83c1-8e0c056ee2a7)

### DAX and Measures
To generate actionable insights from dimensions, advanced DAX calculations must be created and stored in a Measure table for relevant business metrics, such as
- Average Order Value (AOV): AOV = DIVIDE([Total Sales],[Number of Orders])
- Customer Lifetime Value (CLV): AVG CLV = 
  VAR CustomerLifetime = DATEDIFF(MIN(SalesTable[OrderDate]), MAX(SalesTable[OrderDate]), YEAR)
  VAR TotalRevenue = SUM(SalesTable[LineTotal])
  VAR AveragePurchaseAmount = DIVIDE([Total Sales], COUNT(SalesTable[SalesOrderID]))
  RETURN AveragePurchaseAmount * CustomerLifetime
- Total Customer: Total Customer = DISTINCTCOUNT(Customerinfo[CustomerID])
- Total Customer prior year: Total Customer Prior Year = CALCULATE([Total Customer], SAMEPERIODLASTYEAR('Calendar'[Date].[Date]))
- Total Sales: Total Sales = CALCULATE(SUM(SalesTable[LineTotal]))
- Sales Prior Year (For YOY): Salesprioryear = CALCULATE([Total Sales],SAMEPERIODLASTYEAR('Calendar'[Date]))
- YOY calculations of some of the above measures.
  - AOV YoY% = DIVIDE(([AOV] - [AOV last year]), [AOV last year])
  - Total Order YoY% = DIVIDE(([Total Order] - [Total Order prioryear]), [Total Order prioryear])
  - SalesYoY = DIVIDE([Total Sales]-[Salesprioryear],[Salesprioryear])
Storing these DAXs in a new table called Measures allow easier later access.

### Preparation relating to customers
Existing and New customer condition - This needs to be done as the question revolves around the performance of customers, specifically the existing and the new customers. To facilitate this, I create a column called "Customer Fresh" to better mark them.

Customer Fresh = IF(CALCULATE(DISTINCTCOUNT(SalesTable[SalesOrderID]), ALLEXCEPT(SalesTable, SalesTable[CustomerID])) = 1, "New", "Existing")
This DAX formula determines whether a customer is “New” or “Existing” based on their purchasing behavior:
- New Customer: The customer has only placed one order.
- Existing Customer: The customer has placed more than one order.

For RFM analysis, here are the DAXs created:
- Recency value: Recency value = DATEDIFF([Last Transaction Date],DATE(2014,7,1),DAY)
=> Meaning: The recency value calculates the number of days since the customer’s last transaction until July 1, 2014. A smaller value indicates that a customer’s last purchase was more recent, which often correlates with a greater likelihood to engage again.
- Frequency value: Frequency value = DISTINCTCOUNT(SalesOrder[SalesOrderID])
  => Meaning: The frequency value represents the total number of unique sales orders placed by a customer. A higher frequency indicates that the customer regularly engages in transactions with the business.
- Monetary value: Monetary value = 
VAR TotalQuantity = SUM(SalesTable[OrderQty])
RETURN
DIVIDE([Total Sales],TotalQuantity,0)
=> Meaning: The monetary value calculates the average sales revenue per item sold. A higher average indicates that customers are spending more on their purchases, which is a key metric for understanding customer value.

- R Score: R Score = 
SWITCH(
    TRUE(),
        [Recency value] <= PERCENTILE.INC('RFM table'[R Value],0.20),"5",
        [Recency value] <= PERCENTILE.INC('RFM table'[R Value],0.40),"4",
        [Recency value] <= PERCENTILE.INC('RFM table'[R Value],0.60),"3",
        [Recency value] <= PERCENTILE.INC('RFM table'[R Value],0.80),"2",
        "1"
)
=> Logic:
  - A lower recency value (meaning a more recent purchase) will score higher.
  - If a customer’s recency value is less than or equal to the 20th percentile of recency values, they receive a score of 5 (most recent).
  - If it falls within the 40th percentile, they get a score of 4, and so on, until a score of 1 for those in the highest recency percentile (least recent).
Meaning: The R Score ranks customers based on how recently they made their last purchase, with a higher score indicating more recent activity.
- F Score: F Score = 
SWITCH(
    TRUE(),
        [Frequency value] <= PERCENTILE.INC('RFM table'[F Value],0.20),"1",
        [Frequency value] <= PERCENTILE.INC('RFM table'[F Value],0.40),"2",
        [Frequency value] <= PERCENTILE.INC('RFM table'[F Value],0.60),"3",
        [Frequency value] <= PERCENTILE.INC('RFM table'[F Value],0.80),"4",
        "5"
)
=> Logic:
  - If a customer’s frequency value is less than or equal to the 20th percentile of frequency values, they receive a score of 1 (least frequent).
  - If it’s within the 40th percentile, they get a score of 2, and so on, until a score of 5 for those in the highest frequency percentile (most frequent).
Meaning: The F Score ranks customers based on how frequently they purchase, with a lower score indicating lower frequency and a higher score indicating that the customer purchases regularly.
- M Score: M Score = 
SWITCH(
    TRUE(),
        [Monetary value] <= PERCENTILE.INC('RFM table'[M Value],0.20),"1",
        [Monetary value] <= PERCENTILE.INC('RFM table'[M Value],0.40),"2",
        [Monetary value] <= PERCENTILE.INC('RFM table'[M Value],0.60),"3",
        [Monetary value] <= PERCENTILE.INC('RFM table'[M Value],0.80),"4",
        "5"
)
=> Logic:
  - A monetary value less than or equal to the 20th percentile will receive a score of 1 (lowest spend).
  - The score increases to 5 for customers in the highest monetary percentile (highest spend).
Meaning: The M Score ranks customers based on the total amount of money they have spent, with a lower score indicating lower spending and a higher score indicating that the customer is a significant contributor to revenue.
- A table of Segment Score would be used to segment the customers after granting them scores. ([View Here](https://docs.google.com/spreadsheets/d/1TRsMIuSPd2Dcx_N3dCAYWvxq3g_fNu9ND5z18cWUDt8/edit?gid=288914035#gid=288914035))

This step allows us to conduct segmenting customers with ease.
