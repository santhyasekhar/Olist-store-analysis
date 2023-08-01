                                              Analyzing Data from the Olist Store

Olist, founded in 2015, is a thriving Brazilian e-commerce platform that connects small and medium-sized businesses and significant marketplaces,  including Mercado Livre, Amazon, and Americanas.com. Olist equips its sellers with essential tools and infrastructure to excel in the fiercely competitive e-commerce landscape. The goal is to uncover significant patterns, trends, and relationships within the dataset, enabling strategic decision-making and optimization of various aspects of Olist's operations.

The following datasets will be used for analysis:

olist_order_customers_dataset: Contains customer information and their respective locations. It will help identify unique customers in the orders dataset and provide delivery locations.

olist_geolocation_dataset: Contains data on Brazilian zip codes and their latitude/longitude coordinates.

olist_order_items_dataset: Includes information about the items purchased within each order.

olist_order_payments_dataset: Provides data on the payment options used for orders.

olist_order_reviews_dataset: Contains data about customer reviews.

olist_orders_dataset: The core dataset with comprehensive information mapped to each order.

olist_products_dataset: Includes data about the products sold by Olist.

olist_sellers_dataset: Provides data about the sellers fulfilling orders made at Olist.

These datasets will serve as the foundation for conducting in-depth analysis and drawing meaningful insights for various aspects of the business.

KPIs

-> Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics

![Payment Stats Weekday Weekend](https://github.com/santhyasekhar/Olist-store-analysis/assets/130912737/13bc8179-3ccf-4f06-b654-67f01e48d763)



-> Number of Orders with review score 5 and payment type as credit card.

![creditcard-kpi2](https://github.com/santhyasekhar/Olist-store-analysis/assets/130912737/729dd1e7-5691-4f27-894f-b9ac4ef96db1)


-> Average number of days taken for order_delivered_customer_date for pet_shop

![petshop-kpi3](https://github.com/santhyasekhar/Olist-store-analysis/assets/130912737/b3f31c07-4352-48c3-8a9f-da9967995c82)


-> Average price and payment values from customers of sao paulo city

![avgpayprice-kpi4](https://github.com/santhyasekhar/Olist-store-analysis/assets/130912737/29fd1312-d2d7-42ec-b6aa-cdbe25988c20)


-> Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.

![avgshipping-kpi5](https://github.com/santhyasekhar/Olist-store-analysis/assets/130912737/467402d9-a728-40ec-99ab-447fb076cfe3)

Conclusion

1. Analyzing payment statistics for weekdays and weekends reveals consumer spending behaviours, enabling businesses to customize payment options and marketing strategies accordingly. By understanding payment type distribution and average transaction values, businesses can enhance customer satisfaction, improve conversion rates, and drive growth. 

2. Analyzing orders with a review score of 5 and credit card payments uncovers insights into customer satisfaction and preferences, enabling businesses to tailor payment options and customer service strategies.
   
3. Analyzing average delivery days taken by a pet shop helps identify areas for improvement, optimise delivery processes and enhance customer satisfaction.

4. Analyzing average payment value and price in Sao Paulo City provides insights into pricing strategies, market positioning, and resource allocation.

5. Analyzing the relationship between average shipping days and review scores emphasizes efficient shipping operations, improving customer satisfaction and brand perception.






