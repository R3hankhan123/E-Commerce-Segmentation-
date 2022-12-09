##  E-Commerce Segmentation using K Means Clustering and RFM Analysis

The project would involve using K-means clustering and RFM (recency, frequency, and monetary) analysis to segment customers in an e-commerce environment. K-means clustering is a machine learning algorithm that can be used to group data points into clusters based on their similarity. In the context of e-commerce, this could be used to group customers together based on their purchasing behavior. RFM analysis, on the other hand, is a method for analyzing customer value based on three metrics: recency (how recently a customer made a purchase), frequency (how often they make purchases), and monetary value (how much they spend). By combining these two techniques, this project could potentially provide valuable insights into customer behavior and help inform marketing and sales strategies.

###  Dataset
Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

### Features of the dataset
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.