# textured-hair-care
product recommendation algorithm powered by influencers

Play around with the current app on [glide](https://textured-hair.glideapp.io/)

Follow our instagram account to find influencers with textured hair. @texturedhair_

### What problem this project aims to solve
The natural hair movement is on the rise but ecommerce websites like amazon do not have learning algorithms which recommend appropriate products for textured hair types. The new Amazon textured-hair search has the potential to provide accurate product recommendations but the user experience is not ideal and the training data being used in the recommendation engine does not take in appropriate metadata which would enable users to determine is a particular product would fit their needs.

### The promise of influencers
Social media influencers are an important player in the natural hair space because they create user reviews which customrs rely on when making decisions. The legacy beauty -> hair data from priot purchases does not accurately represent the purchasing trends of the textured-hair clients because most customers still do their product shopping in stores specifically pharmacy super stores like Target and Walmart. If the Amazon recommendation engine were to take in product reviews from influencers from youtube, instagram and twitter and use that data when displaying product recommendations for the textured-hair shopping experience sales would go up in this category.

### Algorithmic Improvements
With a curated list of influencers with category and subcategory specific hair types and skin colors, this data could be used to find new influencers using computer vision to determine if a certain number of images in a given profile contain textured-hair and what type of hair said user has.

Given a list of textured hair products sentiment analysis could be used to parse the twitter and video feeds of the selected influencers to determine whether they like or dislike a product. For each product which a particular influcener recommends, a listserve could email the ptoduct owner connecting them with the influcencer and confirm whether they would recommend the product. If both the influencer and the product owner were in agreement about the recommendation a hair type recommendation could be generated enabling user of the textured hair sub-category to understand what influencers with their hair type would recommend in terms of products. This recommendation engine would allow the large Amazon user base to purchase textured-hair products well suited to their hair type.

### Feature List (In Progress)
- Textured product list
- Top influencer product recommendations - video scrapping. Video -> Audio -> Text -> NLP to match products from product list to influencers
- Inluencer nationality tracker - NLU to parse twitter data and figure out where influencers are from in the world


### Current Product - Amazon Textured Hair Product Search

#### Select hair type (wavy, curly, coily, permed)
![alt text](https://github.com/amblount/textured-hair-care/blob/master//images/textured-hair-amazon-view/select-hair-type.png "select hair type")

Problems with this view

- No images with models featuring this hair type
- Difficult to understand what your hair type is without images, many to choose from
- I want to look at a picture and understand that I have this type of hair by looing at a model with hair like mine


#### View all products for selected hair type
![alt text](https://github.com/amblount/textured-hair-care/blob/master/images/textured-hair-amazon-view/all-products.png "coily hair type products")

Problems with this view

- Three of the views contain similar product recommendations for different hair types, this indicates the lack of differentiation of the different hair types and how particular products fit a certain hair type and why
- Feels like this is an ads generated platform and not a user data generated platform
- I have a coily hair type and the first page of products did not contain recommendations for products which I would actually use
- With the stay in place measures many people are going to be shopping online for hair products when they would customarily go into stores

#### Specific product view
![alt text](https://github.com/amblount/textured-hair-care/blob/master/images/textured-hair-amazon-view/specific-product-view.png "product feature list")

Problems with this view

- When I look at a product I am not sure why this product would work on my hair and why it is being recommended to me
- I am not sure how to use this product with my current hair routine
- This view does not have any information specific to my hair type relative to the product recommendation so it does not feel personalized
- I don't know how to use the product
