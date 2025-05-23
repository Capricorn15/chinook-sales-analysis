# CHINOOK SALES ANALYSIS

![](icon.PNG)
---

## About 
Using Chinook database which is a sample dataset representing a digital music store, this project explores sales performance and customer purchase behavior. With detailed analysis, it uncovers key trends in sales, customer segmentation, and genre popularity, revealing actionable insights. 

Disclaimer: All Datasets and reports do not represent any company, country, or institution, but just dummy Datasets to demonstrate the capabilities of Power BI

## Objectives
**Data Exploration**: Understand the structure and content of the chosen database.

**Data Analysis**: Perform specific analyses to derive insights from the data.

**Visualization**: Create visual reports to present findings.

**Presentation**: Compile findings into a comprehensive report or dashboard.

## Problem Statements
**Top-Selling Artists**: Identify artists with the highest sales and analyze their sales trends over time.

**Customer Purchase Patterns**: Segment customers based on purchase behavior and identify key characteristics of high-value customers.

**Genre Popularity**: Determine the most popular music genres and analyze the change in genre popularity over different time periods.

**Sales Over Time**: Analyze monthly and yearly sales trends, including seasonal effects and significant sales events.

**Customer Lifetime Value (CLV)**: Calculate the lifetime value of customers based on their purchase history and provide recommendations for improving customer retention.

**Market Basket Analysis**: Perform association rule mining to find common combinations of tracks or albums purchased together.

### Tools used 

**Python** - Used for exploratory data analysis (EDA) and market basket analysis.

**Power BI** – Utilized for interactive data visualization and dashboard creation, making insights easily interpretable.

**Jupyter Notebook** – Served as the primary environment for scripting and documenting Python-based analysis.

## Data Overview
Chinook database is structured as a relational database containing information about customers, invoices, tracks, artists, albums,genres and employees.

![](DM.PNG)
---
**Key Tables Used in This Analysis**

Artists - Contains details about artists names, including artis Id.

Customers – Contains details about customers, including their names, locations, and contact information.

Invoices – Stores sales transactions, including invoice dates, total amounts, and customer IDs.

InvoiceLine – Provides detailed records of individual track purchases within each invoice.

Tracks – Includes metadata about each track, such as genre, album, and artist information.

Albums – Contains details about music albums and their respective artists.

Genres – Categorizes tracks into different music genres.

Employees – Includes information about employees, primarily used for analyzing sales representatives.

## Methodology
1. Data Extraction & Transformation 

  Imported data from chinook database into power Bi via ODMI connection

  Cleaned and transformed  data using Power query to handle missing values,data inconsistencies & correct data types 
  
  Formatted date columns for time-based analysis.
  
  Created calculated columns and measures using DAX for deeper insights.

2. Data Modeling 

  Established relationships between tables for optimized performance and accurate data aggregation. 

3. Key Performance Metrics & DAX Measures 

  Using DAX, Developed important KPI such as; Total Sales, Total No of Purchases, Average Purchase Value and Customer Lifetime Value estimation 
  
  Created rankings and segmentations using DAX measures 
  
  Implemented Market Basket Analysis to find frequently purchased track combinations 

4. Data Visualization & Reporting

  Built interactive dashboards in Power BI to present key insights dynamically.
  
  Designed charts  to showcase customer segments, genre popularity, and sales trends.
  
  Created a final report summarizing findings and actionable recommendations.

  ![Sales Dashboard](Overview-1.PNG)

## Insights

- **_Top selling Artists_**

The top 10 artists collectively generates the highest sales, amounting to $721.38 and indicating strong customer preference for their music. Meanwhile, sales for lesser-known artists are significantly lower.

- **_Customer Purchase pattern_**

The customer purchases indicate high value customers have highest average purchase value and contribute to approximately 23% of total sales, as shown in the image below.

![Customer Purchase Segmentation](customer-segmentation-1.PNG)

- **_Genre popularity_**

The top 4 most popular genres include; Rock, Latin, Metal and Alternative & Punk where Rock has consistently remained the best selling genre and Alternative & punk experience seasonal spike in sales during holiday season.

- **_Sales Trend_**

Peak sales month occured in January with the highest sales recorded in 2010 at approximately $481 and lowest sales month occured in November of 2011. The analysis shows short term fluctuations but long term trend remains down downward indicating potential market challenges.

- **_Customer Lifetime Value_**

A large percentage of customers have a low CLV of approximately $5.37, indicating that many customers have an average purchase value lower than the overall average of $5.62

## Recommendations

- Leverage top selling artists for special collaborations to sustain high sales while gradually expanding audience for other artists . And promote lesser known artists through targeted marketing campaigns such as offering discounts & exclusive promotions. 

- Implement a loyalty or rewards program to encourage repeat purchases among high-value customers.

- Leverage trending genres by bundling them with low performing genres for promotional campaigns to drive sales.

- Maximize peak seasons through marketing. Analyze external factors that may influence seasonal spikes/drops and align market efforts accordingly.

- Improve retention of low CLV customers by offering promotions & discounts to encourage repeat purchases.

## Conclusion

Through the integration of these strategic recommendations, Chinook music store can optimize sales,leverage on promotional campaigns, enhance customer engagement and retention. These actions will aid success and sustained growth in the digital media industry.
