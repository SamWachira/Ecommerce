# Ecommerce
This project develops a recommendation system using Python with Amazon and Home Depot datasets. It enhances customer experience by offering popular product recommendations for new users, model-based collaborative filtering for personalized suggestions, and search engine-based recommendations for new e-commerce sites without initial data.
### Data Sources:
1. **Amazon Product Ratings** by multiple users: [Kaggle Source](https://www.kaggle.com/skillsmuggler/amazon-ratings)
2. **Home Depot Product Descriptions**: [Kaggle Source](https://www.kaggle.com/c/home-depot-product-search-relevance/data)

### Recommendation System Design:

When a new customer without previous purchase history visits the e-commerce website, they are initially recommended the most popular products. Once a purchase is made, the system updates and recommends other products based on purchase history and user ratings. This is achieved using collaborative filtering techniques.

### Strategies/Techniques Used:

#### 1) Product Popularity-Based Recommendations for New Customers:
Popularity-based recommendations target new customers by suggesting the most popular products on the website. This is effective for initiating a recommendation engine.

#### 2) Model-Based Collaborative Filtering:
This technique recommends items based on purchase history and ratings similarity with other users who bought similar items. It helps predict products for a particular user by identifying patterns from multiple user data.

#### 3) Item-Item Based Collaborative Filtering:
For businesses without user-item purchase history, a search engine-based recommendation system can be designed using textual clustering analysis from product descriptions. Predictions are made based on other products in the same cluster, determined by key search words.
