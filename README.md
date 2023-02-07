# FLO CUSTOMER SEGMENTATION USING RFM
![Flo_RFM Customer Segmentation](https://user-images.githubusercontent.com/84645968/217378903-90e97a3d-cd4c-41b6-993d-ff424ce7f7f6.png)

# Business Problem 
FLO, an online shoe store, wants to segment its customers and determine marketing strategies according to these segments. To this end, the behaviors of the customers will be defined and groups will be formed according to the clusters in these behaviors.
# Dataset 
The dataset consists of the information obtained from the past shopping behaviors of customers who made their last purchases from Flo as OmniChannel (both online and offline shopping) in the years 2020-2021.
#### 12 Features | 19.945 Observation
| Feature | Definition |
| --- | --- |
| master_id | Unique number for each customer |
| order_channel | Channel of the shopping platform is used (Android, ios, Desktop, Mobile) |
| last_order_channel | The channel where the most recent purchase was made |
| first_order_date | Date of the customer's first purchase |
| last_order_date | Customer's last purchase date |
| last_order_date_online | The date of the last purchase made by the customer on the online platform |
| last_order_date_offline | The date of the last purchase made by the customer on the offline platform |
| order_num_total_ever_online | The total number of purchases made by the customer on the online platform |
| order_num_total_ever_offline | The total number of purchases made by the customer offline platform |
| customer_value_total_ever_offline | The total fee paid by the customer for offline shopping |
| customer_value_total_ever_online | The total fee paid by the customer for their online shopping |
| interested_in_categories_12 | list of categories the customer has shopped in the last 12 months |
# Requirements
```
pandas==1.3.4
```
# Author
[Çağla Deniz Doruk](https://github.com/cagladenizdoruk)
