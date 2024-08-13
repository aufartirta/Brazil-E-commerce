# Data Cleaning and Preparation for Brazilian E-commerce Dataset
## Objective
The primary goal of this project is to clean and prepare the Brazilian Olist E-commerce dataset for further analysis in SQL. An exploratory data analysis (EDA) was also conducted to familiarize with the dataset and gain a general understanding of its structure and contents. The dataset consists of nine interconnected tables, each providing different aspects of the e-commerce platform's operations.

## Key Findings from Data Cleaning and Preparation

1. Missing Date Data and Delivery Status:
   Missing date values are directly related to the delivery status of orders. For example, incomplete or canceled orders often lack full date data, such as delivery dates.

2. Order Delivery Rate:
   Approximately 97% of the orders in the dataset were successfully delivered. This high delivery rate indicates the reliability of the delivery process.
   
3. Data Formatting Issues:
   Some data were not in the correct format, particularly date columns that were initially stored as object types. These have been corrected to appropriate datetime formats for accurate analysis.

4. Geographical Distribution:
   The majority of both customers and sellers are based in São Paulo, highlighting the city’s dominance in the e-commerce landscape within Brazil.

5. Purchase Trends Over Time:
   There is a noticeable trend of increasing online purchases from September 2016 to August 2018. However, a significant drop in orders is observed in September 2018, which is likely due to incomplete or missing data for that period.
   The peak of online orders was recorded in November 2017, possibly linked to promotional events such as Black Friday.

6. Weekly Order Patterns:
   The data indicates that more orders are placed on weekdays compared to weekends, reflecting typical consumer behavior in online shopping.

7. Payment Methods:
   The most common payment methods used by customers are credit cards, followed by boleto (a popular Brazilian payment method), vouchers, and debit cards.

## Next Steps
With the dataset now cleaned and prepped, the next steps involve conducting detailed analyses in SQL to uncover deeper insights into customer behavior, sales performance, and operational efficiency. The prepared dataset will facilitate various analytical tasks, including segmentation, trend analysis, and performance evaluation across different dimensions.

**Related links**:
1. [Product Analysis & Trends - Brazil E-commerce](https://github.com/aufartirta/Brazil-E-Commerce-Product)
