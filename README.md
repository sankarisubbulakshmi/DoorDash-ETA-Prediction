# DoorDash ETA Prediction
## Overview
This repository contains a dataset aimed at predicting the Estimated Time of Arrival (ETA) for DoorDash deliveries. 
The dataset includes various attributes related to the order, delivery process, and store details, providing comprehensive data for building predictive models.

## Data Description
The dataset includes the following columns:

1. market_id: Unique identifier for the market
2. created_at: Timestamp when the order was created
3. actual_delivery_time: Actual timestamp when the delivery was completed
4. store_id: Unique identifier for the store
5. store_primary_category: Primary category of the store (e.g., American, Mexican)
6. order_protocol: Protocol used for placing the order
7. total_items: Total number of items in the order
8. subtotal: Subtotal amount of the order
9. num_distinct_items: Number of distinct items in the order
10. min_item_price: Minimum price of items in the order
11. max_item_price: Maximum price of items in the order
12. total_onshift_dashers: Number of available dashers who are within 10 miles of the store at the time of order creation
13. total_busy_dashers: Subset of above total_onshift_dashers who are currently working on an order
14. total_outstanding_orders: Number of orders within 10 miles of this order that are currently being processed.
15. estimated_order_place_duration: Estimated time for the restaurant to receive the order from DoorDash (in seconds)
16. estimated_store_to_consumer_driving_duration: Estimated travel time between store and consumer (in seconds)

## Learning Outcomes
This dataset is primarily suited for supervised learning tasks where the objective is to predict a specific target variable.

Target Column for Supervised Learning: 
The target column for supervised learning in this dataset is actual_delivery_time, as the goal is to predict the actual delivery time based on the other features in the dataset.
