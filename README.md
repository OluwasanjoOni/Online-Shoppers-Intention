# Online-Shoppers-Intention (Product Categorisation)

## Data Description
- The dataset has the following features: 1. Data Set Characteristics: Multivariate 2. Number of Instances: 50424. 3. Number of classes: 4
## Background and Context:
Product categorization, also referred to as product classification, is a field of study within natural language processing (NLP). It is also one of the biggest challenges for e-commerce companies. With the advancement of AI technology, researchers have been applying machine learning to product categorization problems. Product categorization is the placement and organization of products into their respective categories. In that sense, it sounds simple: choose the correct department for a product. However, this process is complicated by the sheer volume of products on many e-commerce platforms. Furthermore, many products could belong to multiple categories. There are many reasons why product categorization is important for e-commerce and marketing. Through the accurate classification of your products, you can increase conversion rates, strengthen your search engine, and improve your site’s Google ranking. A well-built product taxonomy allows customers to find what they are looking for quickly and easily. Making your site easy to navigate is one of the most important elements of your UX and will lead to higher conversion rates. Correctly categorizing products allows your search engine to fetch products quicker. As a result, you create a quicker and more accurate search engine. Once you have a strong product taxonomy in place, this will allow you to create the relevant landing pages for your products. In turn, Google and other search engines will be able to index your site and your products more easily. In the end, this allows your products to rank higher on search engines, increasing the chance that customers find your site. To help merchants choose the correct category, Amazon and other e-commerce companies have automated product categorization tools available. After simply inputting the title or a few words about the product, the system can automatically choose the correct category for you.
## Component of the Product Categorisation (Online Shoppers' Intention)
This project is about how to build a model that will help the e-commerce and marketing companies to correctly organize or arrange products into their respective categories
## Steps Taking In Building the Machine Learning Model
- I recommend that you create a python3 virtual environment, run the command and activate it
Launch the jupyter notebook
Install and import the required packages
Explore the dataset
- Carry out text pre-processing by taking the following steps
1. Html tag removal
2. Tokenization
3. Remove the numbers
4. Removal of Special Characters and Punctuations
5. Removal of stopwords 
6. Conversion to lowercase
7. Lemmatize or stemming
8. Join the words in the list to convert back to text string in the data frame (So that each row contains the data in text format)
9. Print the first 5 rows of data after pre-processing
- Carry out vectorisation using 1. CountVectorizer (A bag of words) 2. Term Frequency-Inverse Docment Frequency (TF-IDF)
- Train and evaluate the model using both types of vectorization
- Print the top 40 features and plot their word cloud using both types of vectorization.
## Conclusion
I got 95% cross validation score using Random Forest Classifier and 91% cross validation score using Gradient Boosting Classifier.
Random Forest model will be deployed which means 95% of the time, Products will be correctly categorised into the right categories by this model.
