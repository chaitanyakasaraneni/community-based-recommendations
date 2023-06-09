# Community-based Product Recommender System

### Introduction
This repository contains sample code for community-based product recommender system. This is a slight implementation of the paper referred below

### Datasets Used
- [Amazon Customer Reviews Dataset](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)
  ```
    DATA COLUMNS:
    marketplace       - 2 letter country code of the marketplace where the review was written.
    customer_id       - Random identifier that can be used to aggregate reviews written by a single author.
    review_id         - The unique ID of the review.
    product_id        - The unique Product ID the review pertains to. In the multilingual dataset the reviews
                        for the same product in different countries can be grouped by the same product_id.
    product_parent    - Random identifier that can be used to aggregate reviews for the same product.
    product_title     - Title of the product.
    product_category  - Broad product category that can be used to group reviews 
                        (also used to group the dataset into coherent parts).
    star_rating       - The 1-5 star rating of the review.
    helpful_votes     - Number of helpful votes.
    total_votes       - Number of total votes the review received.
    vine              - Review was written as part of the Vine program.
    verified_purchase - The review is on a verified purchase.
    review_headline   - The title of the review.
    review_body       - The review text.
    review_date       - The date the review was written.
  ```

### Reference Paper
- https://ieeexplore.ieee.org/document/9030822
