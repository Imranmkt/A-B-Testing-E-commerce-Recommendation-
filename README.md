# A/B Testing on Recommendation Algorithm 

Context:
The dataset originates from an e-commerce platform that implemented a recommendation algorithm to suggest additional products to customers based on their browsing and purchase history. Specifically, the platform aimed to test whether suggesting a phone or a cover (an accessory) along with other products would influence the customer's likelihood to make a purchase.

Dataset Description:

The dataset includes records of customer interactions with the recommendation system, capturing whether the customer purchased the suggested product. The columns in the dataset are as follows:

1.customer_id: A unique identifier for each customer

2.Recommendation_name: The specific recommendation made to the customer (e.g., "Recommend_screenguard")

3.Recommendation_date: The date on which the recommendation was made to the customer

4.suggestion_type: The type of product suggested to the customer, either "With phone" (suggesting a phone) or "With cover" (suggesting a cover)

5.purchase_flag: A binary indicator showing whether the customer made a purchase (1 for bought, 0 for not bought)


Objective:

The primary objective of the analysis was to conduct A/B testing to evaluate the effectiveness of the recommendation algorithm. Specifically, I aimed to determine whether the type of suggestion (phone or cover) had a significant impact on the purchase decisions of customers.
