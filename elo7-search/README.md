# Elo7 Search Dataset

A dataset from Elo7 based on the search engine usage by users.

Download: 
- You can download a _csv_ file [here](s3://elo7-datasets/elo7-search-dataset/elo7_search_dataset.tar.gz)
- or a _parquet_ [here](s3://elo7-datasets/elo7-search-dataset/elo7-search-dataset-parquet)

Data description: 

- product_id - product number identification  
- seller_id - seller number identification  
- query - the text inserted by users  
- search_page - the page number the product appeared (min 1 and max 5)  
- position - the position the product appeared in the search page (min 0 and max 38)
- classification - a measure of relevance. 1 means the product is relevant for the given query and 0 it is not  
- title - product title  
- category - product category  
- subcategory - product subcategory  
- tags - product tags inserted by the seller  
- collection_names - a list of collection names (created by the seller) for which the product is in  
- creation_date - the date of product registration in Elo7 platform  
- price - the product price (R$)  
- minimum_quantity - the minimum quantity the seller sells the product  
- weight - the weight (grams) of a product unit  
- volume - the volume (cubic meters) of a product unit  
- express_delivery - indicates if the product has already been made (1) or not (0)
- order_counts - the number of times the product was purchased in the last three months  
- view_counts - the number of times the product was clicked in the last three months  