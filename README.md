# Market Basket Analysis using Apriori Method

This project demonstrates how to perform **Market Basket Analysis** using the **Apriori** algorithm on a dataset from Kaggle. The goal is to uncover **association rules** that indicate which items are frequently bought together by customers in a retail environment.

## Dataset

The dataset used in this analysis is the [Market Basket Analysis Dataset](https://www.kaggle.com/datasets/vivekgarg06/market-basket-analysis-dataset?resource=download) from Kaggle. This dataset contains transactions of items purchased in a retail store, including product details and transaction data.

### Dataset Link:
[Market Basket Analysis Dataset on Kaggle](https://www.kaggle.com/datasets/vivekgarg06/market-basket-analysis-dataset?resource=download)

## Key Steps in the Analysis

1. **Data Preprocessing**:  
   The dataset is cleaned and transformed to prepare it for the Apriori algorithm, which requires transaction data in the form of a list of items bought in each transaction.

2. **Applying the Apriori Algorithm**:  
   The Apriori algorithm is applied to find frequent itemsets, and then we generate association rules from these frequent itemsets. The association rules represent relationships between different products bought together.

3. **Evaluating Association Rules**:  
   The rules are evaluated using **support**, **confidence**, and **lift** metrics to identify the most meaningful and strong association rules.

## Results

The best association rules identified using the Apriori method are:

1. **IF buy (egg, ground beef) THEN buy mineral water**  
   - This means if a customer buys **egg** and **ground beef**, they are likely to also buy **mineral water**.

2. **IF buy (milk, ground beef) THEN buy mineral water**  
   - Similarly, if a customer buys **milk** and **ground beef**, they are likely to also purchase **mineral water**.

These association rules suggest a strong relationship between **ground beef** and **mineral water**, with **egg** and **milk** frequently appearing in transactions alongside ground beef.
