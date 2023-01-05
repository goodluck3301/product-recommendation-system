# Product Recommendation System

### Product Recommendation System for e-commerce businesses

The recommendation system is designed in 3 parts based on the business context:

- Recommendation system part I: Product pupularity based system targetted at new customers

- Recommendation system part II: Model-based collaborative filtering system based on customer's purchase history and ratings provided by other users who bought items similar items

- Recommendation system part III: When a business is setting up its e-commerce website for the first time withou any product rating
___
### Small piece from code

```python
Recommend = list(X.index[correlation_product_ID > 0.90])
Recommend[0:9]
```
```
Output: 

['0205616461',
 '0558925278',
 '0737104473',
 '1304146537',
 '1304168522',
 '1304196070',
 '1304351475',
 '1304482596',
 '1304482634']
```
___
### Datasets
- [Amazon product review dataset](https://www.kaggle.com/skillsmuggler/amazon-ratings)
- [Dataset: Home Depot's dataset with product dataset](https://www.kaggle.com/c/home-depot-product-search-relevance/data?select=product_descriptions.csv.zip)
