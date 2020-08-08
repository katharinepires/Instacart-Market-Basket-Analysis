# Instacart-Market-Basket-Analysis
Creation of association rules for studies of consumption habits and about products in market baskets, such as the order in which products are added to the cart and if it has already been purchased more than once.

These data are available at [Kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis?rvi=1), where this competition was held on market baskets.

![market basket](https://user-images.githubusercontent.com/67076633/89716028-441cc980-d980-11ea-83c3-e6230cc6ddaa.png)

As you can see, the **objective** is precisely to make a study on the products that are consumed and forecast which will be purchased next. Here in this Jupyter Notebbok I bring my conclusions of the results obtained from the codes and the rules of association created!

## Data Description:
The dataset for this competition is a relational set of files describing customers' orders over time. The goal of the competition is to predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, we provide between 4 and 100 of their orders, with the sequence of products purchased in each order. We also provide the week and hour of day the order was placed, and a relative measure of time between orders. For more information, see the [blog post](https://tech.instacart.com/3-million-instacart-orders-open-sourced-d40d29ead6f2) accompanying its public release.

## File descriptions:
Each entity (customer, product, order, aisle, etc.) has an associated unique id. Most of the files and variable names should be self-explanatory.

## Datas:
- ``aisles.csv``
- ``departments.csv``
- ``order_products__*.csv``
- ``orders.csv``
- ``products.csv``

## Conclusions:
Due to limitations in the computer's memory, it was not possible to run more examples. However, it was possible to perceive certain patterns of purchases such as organic products accompanied by bananas, in addition to cold products such as yorgut which are often bought together. There is a pattern of products from the same department, such as organic food products, mostly fruits, always bought together with other food products. Just like flavored waters always bought together. Looking at the latest rules, the Banana appears, as seen previously, the Banana is frequent in the carts and still tends to be the first product to be added to the cart. This suggests that the market has a great demand for organic and healthy food products, as seen in the examples, these orders are protagonists in the market basket.
