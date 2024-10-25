# Customer-Segmentation_Analysis-MileStone--
# overview 
The goal of this project is to utilize Power BI to segment customers, enabling businesses to gain a deeper understanding of their customer base through the analysis of purchasing behavior, demographics, and preferences. This segmentation will be derived from customer, transaction, and product data, providing businesses with the opportunity to enhance their marketing, sales, and customer service strategies in various regions.
# Datasets taken into Actions 
1. The customers.csv file includes information such as customer age, gender, location, total spend, loyalty points, and preferred payment method.
2. In the transactions.csv file, you can find the transaction history, purchase frequency, total spend, shipping addresses, and delivery address.
3. Details about product categories and purchase information are stored in the products.csv file.
4. The regions.csv file holds sales details across different regions.
# CUSTOMER SEGMENTATION ANALYSIS CREATION
Data Cleaning Steps 
1. Loading Datasets
Utilize the "Get Data" function in Power BI to import the necessary datasets such as customers, transactions, and products.
In the Power Query Editor, ensure data cleanliness by:
- Removing any duplicate entries.
- Addressing any missing values.
- Verifying the appropriate data types for all columns.
2. Establishing Connections
Create associations between the datasets:
Connect the Customer Dataset and Transaction Dataset using the CustomerID column.
If utilizing a Product Dataset, establish a link to the Transaction Dataset through the ProductID column.

