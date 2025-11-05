# Amazon-Best-Sellers-Analysis
Created by Mallika Kulkarni, Monisha Krothapalli, Arushi Agarwal

Our goal is to analyze different features of Amazon products and figure out which have the most importance when labelling the product as a Best Seller. What exactly does "best seller" mean when it comes to customers and the business as a whole? All the product attributes that we consider are visible to the user on the Amazon website. The objective is to create a comprehensive model that will interpret product success and determine the features that contribute to best seller status at Amazon.

The most important real world use for our project directly relates to e-commerce platforms. We hope to determine which visible features will entice users to turn a product into a best seller. This project could help businesses that own these platforms understand core consumer behavior and improve their website. This data, while specifically detailing features of Amazon products, limited to only the year 2023, could be useful to various other corporations and business owners that are interested in studying consumer habits to better sell their products. Perhaps a company may realize from our study that displaying the category of the product is more highly correlated with best seller status.

Implementation Introduction: We use multiple datasets to maximize the information that we can analyze about each product. The first dataset, amazon_products.csv, is merged with another, amazon_categories.csv, to create products_df which will also hold the product information as well as its general category. The specific columns of this dataframe are detailed below.

We will also use product reviews in order to supplement our original model,conducting sentiment and emotion analysis. These additional two columns will be added as inputs to our best performing model to determine if the qualitative features of reviews are correlated with best seller status.

We hope that you find the project insightful!
