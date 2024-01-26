# MAVEN ROASTERS SALES ANALYSIS

An Excel project that aims to provide Maven Roasters, a fictitious coffee shop operating across three locations in New York City, with actionable insights. These insights are intended to inform strategic decisions and optimize Maven Roasters' overall operational effectiveness

## Project Overview

Maven Roasters, a fictitious coffee shop operating across three locations in New York City, has accumulated transaction records containing valuable information about their sales. This project aims to analyze these transaction records to gain insights into Maven Roasters' sales trends, busiest days, product popularity, and revenue contributions. 

## Project Scope

This project involves an in-depth analysis of Maven Roasters' sales data, encompassing key elements such as transaction date, timestamp, location, and detailed product-level information. The analytical scope spans historical data from January 1, 2023, to June 30, 2023, providing a comprehensive view of Maven Roasters' operational performance during this period. The analysis was conducted across all three Maven Roasters locations situated within New York City, aiming to capture a holistic understanding of the coffee shop's sales dynamics and trends across diverse locations within the specified timeframe.

## Business Objective

The overarching goals of this analysis are multifaceted, aiming to provide a nuanced understanding of Maven Roasters' sales performance. These objectives encompass unraveling the trends in Maven Roasters' sales over a specified period, discerning the busiest days of the week while delving into the factors that influence these patterns, scrutinizing product-level data to identify both the best-selling and least-selling items, and ultimately quantifying the unique revenue contributions of each product to the broader success of the business. Through a comprehensive exploration of these aspects, the analysis aspires to furnish actionable insights that can inform strategic decisions and optimize Maven Roasters' overall operational effectiveness.

## Document Purpose

This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and any other relevant information

## Use Case

Several stakeholders within and outside the organization can benefit from the Maven Roasters Sales Analysis. These stakeholders include:

**1. Management Team**

- **Key Decision Makers:** Executives and top-level managers can leverage the analysis to make informed decisions regarding sales strategies, resource allocation, and overall business direction.
- **Operational Managers:** Managers overseeing day-to-day operations can use insights to optimize staffing, inventory management, and promotional activities.

**2. Marketing Team**

- **Marketing Managers:** By understanding sales trends and product popularity, the marketing team can tailor campaigns to boost sales, promote popular products, and maximize revenue.
- **Promotions Team:** Insights into busiest days and customer preferences can inform the timing and content of promotional activities.

**3. Sales Team**
- **Sales Representatives:** Front-line sales staff can benefit from understanding which products are most popular, enabling them to make informed recommendations to customers.
Customer Service Team
- **Customer Support Representatives:** Awareness of busy days and popular products allows customer service teams to anticipate and address customer inquiries or concerns more effectively.

## Data Source

This project employs dataset, sourced from the Maven Analytics website, designed specifically for practice purposes. The dataset, presented in the form of an Excel file, is a singular table boasting an expansive 149,116 rows and 11 columns. Within this structured framework, a wealth of information characterizes Maven Roasters' sales data, providing a nuanced understanding of various facets of their business operations.

The dataset encompasses key attributes essential for a comprehensive analysis, including Transaction ID, Transaction Date, Transaction Time, Transaction Qty, Store ID, Store Location, Product ID, Unit Price, Product Category, Product Type, and Product Detail. Each of these variables contributes crucial insights, collectively painting a vivid portrayal of Maven Roasters' transactional scenario.

## Data Cleaning and Processing

Having clean data for analysis is crucial because it ensures that the insights derived from the analysis are accurate, reliable, and free from biases introduced by data issues. Clean data facilitates a smoother analytical process, enabling researchers, analysts, and decision-makers to draw meaningful conclusions and make informed decisions based on trustworthy information.

After conducting a thorough assessment and examination of the data to ascertain its quality and suitability for this analysis, and meticulously evaluating the overall data quality by checking for errors, inconsistencies, missing values, and duplicate entries, it has been observed that the dataset for this analysis is well-structured, consistent, and devoid of significant issues that could impede analysis or interpretation. The data adheres to a standardized format and consistent naming conventions. All necessary data fields are present and also diligently populated. The data values are accurate, and appropriate data types have been assigned to each column. Importantly, the dataset contains no duplicate records. Therefore, based on this comprehensive evaluation, it is conclusively determined that no cleaning is required, as the dataset is inherently well-prepared and ready for meaningful analysis, ensuring accuracy, reliability, and trustworthiness in the insights derived from the data.

The following process was also carried out on Maven Roasters’ Sales data during data processing.

- Added New Columns 

New columns, namely Year, Month, and Week, were incorporated into the Maven Roasters’ Sales data. These additional columns play a pivotal role in the analysis by facilitating an exploration of how Maven Roasters' sales have trended over time. Furthermore, they contribute significantly to understanding which days of the week tend to be the busiest, with the aim of unraveling the factors that influence these patterns. The inclusion of these temporal indicators enhances the analytical capabilities of the dataset, allowing for a more comprehensive assessment of sales dynamics and patterns over different timeframes.

Then, the dataset was imported into Excel Power Pivot for further analysis.

## Data Analysis and Insight

The primary aim of this analysis is to derive valuable insights from Maven Roasters' sales data by conducting a comprehensive examination of key factors. This multifaceted exploration involves several pivotal objectives. Firstly, it seeks to comprehend the temporal trends in Maven Roasters' sales over time, entailing the identification of patterns within the sales data. Secondly, the analysis aims to identify the days of the week consistently experiencing peak activity for Maven Roasters, probing into the underlying factors influencing transaction volumes on specific days. Thirdly, a detailed investigation into the dynamics at the product level is undertaken, discerning the most and least frequently sold products, and determining the individual revenue contribution of each product to the overall business.

As a result, this analysis provides insights addressing the following questions.

**1. How have Maven Roasters sales trended over time?**

The question inquiries into the historical patterns and changes in the sales performance of Maven Roasters, a coffee shop. It seeks to understand the overall trajectory of Maven Roasters' sales, uncovering whether sales have been consistently increasing, decreasing, or exhibiting fluctuations. This analysis helps in identifying periods of growth, potential seasonality, or any patterns that might impact future decision-making and strategic planning for the coffee shop.

To address this question, in Microsoft Excel Power Pivot, a comprehensive measure was developed to calculate the total revenue made by Maven Roasters for each month using DAX (Data Analytics Expression) Code. This measure was designed to analyze the sales data, 
aggregate it on a monthly basis, and provide a clear and detailed summary of the total revenue achieved by Maven Roasters in each respective month. The insights derived from this calculation serve to identify patterns, changes, and trends in the sales performance over time.


















































































