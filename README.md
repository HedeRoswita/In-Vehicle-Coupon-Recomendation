# In-Vehicle-Coupon-Recommendation

# 1.	Problem Setting 


Discount oupons are a powerful marketing strategy used by small businesses and manufacturers. While it doesn't guarantee that consumers will profit, it gives a reassuring and satisfying sense of "business." This is because the customer will feel they are getting a good deal. Additionally, customers tend to buy products from companies that offer discounts. Discount coupons are a crucial marketing strategy for businesses to achieve their sales and profit goals. By offering discounts, companies or businesses can attract new customers, encourage existing customers to spend more or try new products, and reduce cart abandonment. 

A group of scientists collected the dataset used in this project from a survey on Amazon Mechanical Turk drivers. The dataset is dedicated to recommending in-vehicle mobility system coupons to users and is used to predict whether customers will accept the voucher. Estimating coupon acceptance will help the company effectively target its marketing strategies and reduce the number of wasted coupons.

Based on the dataset, only 56.84 % of drivers receive the coupon. It might imply that the profit is not optimal since it doesn’t fulfill the company’s target or the KPI of the campaign. To improve the coupon acceptance rate, we are building a predictive model to accurately estimate whether the driver or customer will accept the coupon while reducing marketing costs as much as possible. The models are built by leveraging four machine learning algorithms: Logistic Regression, Decision Tree, Naïve Bayes, and Neural Network. The models will be trained using the survey data, and the final model will be evaluated based on its accuracy in predicting testing data.

# 2.   Conclusion


Discount coupons are a powerful promotion strategy that small businesses and manufacturers use to increase profitability. Based on the dataset, only 56.84% of drivers accept the coupon, and it does not satisfy the KPI of the promotion. Four different algorithms are used to predict whether the customer will accept or reject the voucher. 
Based on the calculation, neural networks is accurately predicting coupon acceptance by 74.26%, which means using this model improves coupon acceptance by 17.42%. Furthermore, we also look at the economic factor and calculate the benefit-cost-ratio of this marketing strategy. Using this data, with the assumption that the benefit per coupon is $10 and the cost is $3, and if the company distributed 12,610 coupons, the total revenue from this marketing strategy is $55,590, and the cost of distributing the coupon is $37,830. benefit-cost ratio for this scenario is 2.48. In this scenario, the company gets a profit of $2.48 for every $1 it spends on distributing coupons, which strongly suggests that the marketing strategy is effective. 

In this model, I use flask to build API that deploy model into local server. Use this link (http://127.0.0.1:5000/) to test the model.
