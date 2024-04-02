# Customer-Analytics
# Business Problem
The importance of understanding customers cannot be overstated in running a successful business, with KYC (Know Your Customer) being crucial for many companies. KYC facilitates tailoring offerings to customer needs, enhancing communication and delivery. Customer analytics, especially segmentation, is vital for effective marketing, encompassing various customer characteristics and behaviours. The STP (Segmentation, Targeting, Positioning) framework is fundamental for exploring and understanding potential customers.
The dataset used here pertains to a B2C (Business to Consumer) model, offering ample data points for analysis. FMCG (Fast Moving Consumer Goods) companies, like supermarkets, provide abundant data, making them ideal for customer analytics courses. Segmentation involves dividing customers into groups with similar characteristics, aiding in predicting purchase behaviours and marketing responses. Marketers utilize demographic, geographic, and psychographic data for segmentation when consumer behavior data is limited or available. Targeting evaluates segment profitability, determining which segments to focus on and how to promote products. Positioning entails aligning product characteristics with customer needs, considering presentation and distribution channels. The Marketing Mix framework further guides positioning by addressing product presentation and distribution strategies.
The concept of the marketing mix is to develop the best product or service and offer it at the right price through the right channels. In this case study, we'll perform customer analytics that answers three fundamental questions about positioning and the marketing mix.

1.Will the customer buy a product from a particular product category when they enter the shop?

2.Which brand is the customer going to choose?

3.How many units is the customer going to purchase?


# Approach:
1.	Purchase Incidence Modeling: We employed logistic regression to predict purchase probabilities based on average price, followed by calculating price elasticities to understand the relationship between price and purchase probability.

2.	Brand Choice Modeling: Utilizing multinomial logistic regression, we predicted brand choices and calculated own and cross-price elasticities to identify brand preferences and competitor effects.

3.	Purchase Quantity Modeling: Using linear regression, we estimated purchase quantity based on price and promotion incidents, then calculated price elasticities of purchase quantity to understand the impact of price changes on purchase behavior.
# Insights:
•	Purchase incidence analysis revealed an inverse relationship between price and purchase probability, with different customer segments exhibiting varying levels of price sensitivity.

•	Brand choice modeling highlighted brand preferences and identified potential substitutes, informing targeted marketing strategies.

•	Purchase quantity modeling showed overall inelastic behavior towards price changes, suggesting limited influence of price on purchase quantity.

# Conclusion and Recommendations:
Our analysis provides valuable insights into customer behavior and market dynamics. To refine our models further, we recommend:
•	Incorporating additional features such as customer demographics and purchase history for more accurate predictions.

•	Conducting more granular segmentation analysis to tailor marketing strategies to specific customer groups.

•	Exploring alternative modeling techniques and data sources to capture complex interactions and improve model performance.

By leveraging these recommendations, businesses can optimize their marketing strategies, enhance customer satisfaction, and ultimately increase profitability in the competitive marketplace.


