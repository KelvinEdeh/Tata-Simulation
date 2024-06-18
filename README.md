# Tata IQ Forage Job Simulation Project
This project explores the Tata IQ job simulation on Forage, answering the basic questions of month-over-month sales performance, country-wise sales and revenue volume, customer spending pattern, and regional contributions to revenue. We explore key business performance indicators to enable the CEO and CMO to make strategic decisions.

## About Tata
Tata is a global enterprise, headquartered in India, comprising over 100 independent operating companies. It operates in more than 100 countries across six continents. Tata IQ is one of the Tata Group companies focused on providing intelligent data solutions and insights.

## Project Overview
In this project, I will review the sales data of an online retail business and provide insights that would be valuable to the CEO and CMO of the company using Tableau. The business has been performing well, and the management wants to analyze the major contributing factors to revenue to plan strategically for next year. They also intend to expand the business and seek guidance on areas that are performing well to maintain focus on successful strategies.

## Purpose of the Project
The purpose of this project is to:
- Analyze retail data to identify trends and patterns.
- Provide visual insights into revenue, customer behavior, and market demand.
- Assist the CEO and CMO in strategic decision-making and expansion planning.

## Business Questions
1. **Time Series of Revenue Data for 2011**:
   - The CEO wants to view the monthly revenue for 2011 to identify seasonal trends and make forecasts.
2. **Top 10 Revenue-Generating Countries**:
   - The CMO wants to identify the top 10 countries generating high revenue for the business. He also wants to see the quantity of sales for these countries. This should exclude the UK as the business has fully established its UK market.
3. **Top 10 Customers by Revenue**:
   - The CMO is interested in identifying the top 10 customers by revenue to see if revenue is concentrated with few customers and the spending pattern. He also wants to ensure their satisfaction.
4. **Demand by Region (Excluding UK)**:
   - The CEO wants to identify regions with high demand for products to inform expansion strategies, excluding the United Kingdom.

## Data Source
The data used in this project was provided by Tata and is available on the Forage job simulation portal.
## Data Exploration and Cleaning Process
1. **Data Loading**:
   - Imported the dataset into Tableau.
2. **Initial Exploration**:
   - Performed an initial analysis to understand the structure and content of the data.
   - the dataset is a single table requiring no complicated modeling technique.
   - the dataset contains over 540,000 records and 9 columns: Country, customer ID, description, invoice No., stock code, invoice date, description, quantity, and unit price.
3. **Data Cleaning**:
   - Checked for any duplicate entries but found none.
   - Missing data were found in the customer ID column which has little impact on the analysis except the customer distributions. I used filter to exclude null values in the top customer visuals
   - Records with negative values of Unit Price were removed. Same as records with Quantity less than or equal to 0. 

## Visualizations and Discussion
### Question 1: Time Series of Revenue Data for 2011
- **Visualization**: Monthly revenue trend line chart for 2011.
- **Discussion**: The chart reveals gradual growth with a peak in November, showing seasonality towards the end of the year. We do not have the complete sales data for the month of December, thus the seeming sharp decline.
![Monthly Revenue Trend](path_to_image)

### Question 2: Top 10 Revenue-Generating Countries (Excluding UK)
- **Visualization**: Bar chart showing the top 10 countries by revenue and the quantity sold for those countries.
- **Discussion**: The top performing customers in the decreasing order are: the Netherlands, EIRE, Germany, France, Australia, Spain, Switzerland, Belgium, Sweden, and Japan. these key markets contribute significantly to revenue. The online retail store can increase marketing efforts in these high-performing regions.

![Top 10 Countries by Revenue](path_to_image)

### Question 3: Top 10 Customers by Revenue
- **Visualization**: Bar chart showing the top 10 customers by revenue in descending order.
- **Discussion**: These customers contribute significantly to the revenue, with analysis showing a huge 15% of total revenue coming from these 10 individuals. The top-performing customers should be given special product offers, their feedback is necessary to see what gives they view as attracts them to the brand and also see their purchase patterns. It is also necessary to improve the relationship with other customers to increase sales and improve revenue distribution. This will ensure that few customers don't have a high influence on the company's revenue.

![Top 10 Customers by Revenue](path_to_image)

### Question 4: Demand by Region (Excluding UK)
- **Visualization**: A map showing demand by region with color concentration to show the revenue size.
- **Discussion**: The European countries and Australia are leading in sales performance. These markets can be given top priority in marketing and operational decisions to improve sales for the coming year. Further analysis could also reveal their product-wise purchase pattern and seasonality to identify what products, months, and days attract the highest sales in these regions. 

![Demand by Region](path_to_image)

## Summary
This project provided insights into revenue trends, key markets, top customers, and regional demand using Tableau visualizations. These insights support strategic decisions aimed at driving growth and improving customer satisfaction.

## Further Analysis
To gain deeper insights, consider:
- **Customer Segmentation**: Analyze customer segments to tailor marketing strategies.
- **Product Performance**: Assess the performance of individual products to optimize inventory and sales.
- **Competitor Analysis**: Benchmark against competitors to identify opportunities and threats.
- **Sentiment Analysis**: Analyze customer feedback and reviews to improve product offerings and service quality.

