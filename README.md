# Real-Time Retail Insights Dashboard
This dashboard is created on Grafana with a Kaggle dataset streamed via InfluxDB.

---

**Created by:  SDA 1 - Group 13**
>
> Himanshi Saxena (045019)
>
> Jasleen Kaur Chadha (045023)
>
> Phalit Gupta (045040)

##**Dataset Description**


---



The **Retail Transactional** dataset represents retail transactional data, offering a comprehensive view of
* Customer demographics
* Purchase behavior
* Product details
* Transaction specifics

This dataset serves as a valuable resource for understanding customer behavior and improving retail operations.  


The dataset includes details such as `customer ID`, `name`, `email`, `phone`, `address`, `city`, `state`, `zipcode`, `country`, `age`, and `gender`.

Customers are `segmented` into three categories: *Premium*, *Regular*, and *New*. These details enable a better understanding of customer demographics and segmentation.

It captures transaction-specific information, including `transaction ID`, last purchase `date`, `total purchases`, `amount` spent, `feedback`, `shipping method`, `payment method`, and `order status`. This facilitates the analysis of customer behavior, satisfaction, and transaction patterns.  



> ***NOTE:*** *The dataset contains some null values and duplicate entries, which have been handled during the preprocessing stage.*

## **Tags & Fields**


---


The following are the Tag keys:
* `City`
* `State`
* `Country`
* `Gender`
* `Income`
* `Customer_Segment`
* `Month`
* `Product_Category`
* `Product_Brand`
* `Product_Type`
* `Feedback`
* `Shipping_Method`
* `Payment_Method`
* `Order_Status`
* `Ratings`



The following are the Field keys:
* `Transaction_ID`
* `Customer_ID`
* `Zipcode`
* `Total_Purchases`
* `Amount`
* `Total_Amount`
* `Age`

##**Objectives**


---




1. Track overall business performance by monitoring key metrics like total purchases, revenue, and active customers in real-time to assess business health.

2. Identify sales trend to analyze time-based sales data to understand seasonal or daily purchase patterns and adjust strategies accordingly.

3. Improve order fulfillment efficiency by tracking pending orders to identify bottlenecks in the supply chain and optimize fulfillment processes.

4. Optimize inventory management by identifying top-performing and underperforming products to ensure stock availability and avoid overstocking.

5. Boost revenue generation to focus marketing efforts on high-revenue product categories and shipping methods to maximize returns.

6. Improve marketing campaign effectivenes by aligning promotional efforts with sales trends and peak customer engagement times for better ROI.

7. Identify opportunities for product development by using product-wise and category-wise revenue data to prioritize investment in new or existing product lines.

8. Evaluate Logistics and Delivery Strategies by assesing the popularity and effectiveness of various shipping methods to optimize logistics operations and meet customer expectations.

## **Dashboard**


---



https://github.com/user-attachments/assets/46f36175-a1f1-4cdb-bbbe-55a937073250

