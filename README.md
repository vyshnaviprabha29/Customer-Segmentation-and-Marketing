# Customer-Segmentation-and-Marketing

PROBLEM STATEMENT:

The bank is looking to market various products to the right audience to increase the sales of each product based on the customer transactions, demographics and digital activity. In the process the bank would like to understand which is the right group of customers to be marketed. 

Data Sets Used:

1.Product_lookup - The different products available in the bank along with the product code
2.Customer_product - The products each customers hold
3.Customer transaction history - The transactions made by  the customers over a period of time.
4.Customer channel activity - the channel activities of the customers like login to mobile banking app or online banking
5.Customer demographics - Demographic details

In this project, I focused on data cleaning and analysis to support the bank's marketing and product strategy. The key tasks included:

Data Cleaning with PySpark:

Date Format Modification: Standardized date formats across various sheets to ensure consistency and ease of analysis.
Column Management: Removed unnecessary columns to streamline the dataset and focus on relevant information.
Normalization of Gender Data: In the customer_demographic_modified sheet, gender representations were unified by converting 'FEMALE' and 'F' to 'FEMALE', 'MALE' and 'M' to 'MALE', and '?' to 'NA'.

Data Analysis Using Tableau:

Right Combination of Attributes: Identified key attributes across transactions, channel activity, and demographics to determine the most effective way for the bank to market and sell products to the right customers, avoiding irrelevant or over-marketing.
Visualization of Insights: Created visualizations to present insights from the data, which included:
Spend Trend Analysis vs. Demographics: Analyzed and visualized how spending trends vary among different demographic groups, providing a basis for targeted marketing.
Channel Analysis: Examined customer interactions with various banking channels, providing insights into channel preferences and usage patterns.
