# 🛒 Customer Sales Trends Analysis

This project aims to predict customer purchasing behavior and uncover trends in sales using a dataset from Kaggle. The analysis identifies key factors influencing purchases like promo code usage, purchase amount, and location.

## 📌 Project Objectives
- Predict whether a customer will make a purchase.
- Identify feature importance in purchasing behavior.
- Provide actionable business recommendations.

## 📊 Dataset
- Source: [Kaggle Dataset - Customer Shopping Trends](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset/data)
- 3,900 rows of anonymized customer transaction data.
- Features include: gender, age, product category, amount spent, location, subscription status, payment method, etc.

## 📈 Key Insights
- Promo code usage is the strongest indicator of purchases.
- Clothing and Accessories dominate sales.
- Majority of users are non-subscribers.
- Credit card is the preferred payment method.

## 🧠 Model
- **Algorithm:** Decision Tree Classifier
- **Accuracy:** 73%
- **AUC:** 0.679
- **Key Features:** Promo Code Used, Purchase Amount, Item Purchased

## 💡 Recommendations
- Use personalized promo codes to improve engagement.
- Focus marketing efforts on high-spending and promo-using customers.
- Build more advanced models to increase prediction performance.

## Findings
-The feature importance chart shows that "Promo Code Used" is the most influential factor in the Decision Tree model, significantly impacting predictions. Other key features include "Purchase Amount (USD)," "Location," and "Item Purchased," which also contribute notably. Less important features, such as "Subscription Status" and "Discount Applied," have minimal influence on the model's decisions. This suggests that promotional activity and purchasing behavior play a crucial role in classification outcomes.


## 👤 Author
**Priyansh Parmar**  
M.S. in Data Science – Pace University  
📧 pp91088n@pace.edu
