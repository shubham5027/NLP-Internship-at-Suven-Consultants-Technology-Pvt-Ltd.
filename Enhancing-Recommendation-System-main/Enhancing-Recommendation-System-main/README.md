# Enhancing E-commerce Using an Advanced Search Engine and Recommendation System

A few decades ago, no one would have ever imagined that we could buy a 55-inch TV at midnight while sitting at home watching a 22-inch TV. Thanks to the Internet and e-commerce, we can buy any item at any time from anywhere, and it is delivered quickly. Flexibility has made e-commerce businesses expand exponentially. You don't have to visit the store, products have unlimited options, prices are lower, no standing in line to pay, and so forth.

Given the traction e-commerce is getting, many big names are taking part in it. Companies keep technology in check aldag with operations, supply chains, and marketing. To survive competition, the right use of digital marketing and social media presence is also required. Also, most importantly, businesses must leverage data and technology to personalize the customer experience.

## Problem Statement

One of the most talked-about problems of this era is recommendation systems. Personalization is the next big data science problem. It's almost everywhere-movies, music, e-commerce sites, and more.

Since the applications are wide, let's pick an e-commerce product recommendation as one of the problem statements. There are multiple types of recommender systems. But the one that deals with text is content-based recommender systems. For example, if you see the diagram shown in Below Figure, similar products have been recommended based on the product description of the clicked product. Let's explore building this kind of recommender system in this project.

On the same lines, search engines in e-commerce websites also play a major role in user experience and increasing revenue. The search bar should give the relevant matches for a search query, and wrong results eventually result in the churn of the customers. This is another problem that we plan to solve.

To summarize, in this project, we aim to build a search and recommenders that can search and recommend products based on an e-commerce data set.

## Approach

Our main aim is to recommend the products or items based on users' historical interests.
A recommendation engine uses different algorithms and recommends the most relevant items to the users. It initially products based on that. the past behavior of the users. It recommends products based on that

Let's discuss the various types of recommendation engines in brief before we move further.

Below Figure shows the types of recommendation engines.

![11_90](https://github.com/sohansai/Enhancing-Recommendation-System/assets/76840110/8098cbbd-08d4-4ba9-944d-fde819563551)

The following are various types of recommendation engines.

* Market basket analysis (association rule mining)

* Content based

* Collaborative filtering

* Hybrid systems

* ML clustering based

* ML classification based

* Deep learning and NLP based

## Content Based Filtering

Content Filtering algorithm suggests or predicts the items similar to the ones that a customer has liked or shown any form of interest. 

Below Figure shows the example of content-based filtering.
![11_91](https://github.com/sohansai/Enhancing-Recommendation-System/assets/76840110/dc13e3c7-b3d1-4310-ad2b-d9aaca099397)

The project aims to use deep learning techniques for information retrieval rather than the traditional word comparison approach to get better results. Also, it focuses on recommender systems that are everywhere and creates personalized recommendations to increase the user experience.

The methodology involves the following steps.

1. Data understanding

2. Preprocessing

3. Feature selection

4. Model building

5. Returning search queries

6. Recommending product 905

Below Figure shows the Term Frequency-Inverse Document Frequency (TF-IDF) vectors-based approach to building a content-based recommendation engine that gives a matrix where every word is a column.

![11_92](https://github.com/sohansai/Enhancing-Recommendation-System/assets/76840110/4ffb2c81-514e-4c7a-bb28-5a98f6a5582e)

Below Figure shows the architecture for a product search bar. Here, word embeddings are used. Word embedding is a language modeling technique where it converts text into real numbers. These embeddings can be built using various methods, mainly neural networks.

![11_93](https://github.com/sohansai/Enhancing-Recommendation-System/assets/76840110/1cf5d121-7e55-4a8c-8710-54348a374cee)

## Understanding the Data

The e-commerce product recommendation data set has 20,000 observations and 15 attributes.

Download data from - [here](https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products)





  
