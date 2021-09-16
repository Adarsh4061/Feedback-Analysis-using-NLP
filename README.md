# Feedback-Analysis-using-NLP
Performed Exploratory Data Analysis on dataset to come up with insights such as rating, review trends over the years, range of ratings every year, helpfullness of the reviews, price range of products.

Feature Extraction using TF-IDF vectorization for both the problems.

Sentiment Analysis : Given a product and its reviews and ratings along with helpfullness score, predict the sentiment of review, whether the reveiw is 'positive' or 'negative'.

Logistic Regression is comes out to be the best model to classify the sentiment of reviews.

Recommender System : Given a product and its reviews and ratings along with helpfullness score, recommended the next best product based on the review summary and the overall rating.

For recommendations, Analysing most reveiewed user help us to understand user behaviour. Applied K-Nearest Neighbours with k=2 is used to get 2 nearest products based on review summary and overall review score, recomemnd the products to the user.
