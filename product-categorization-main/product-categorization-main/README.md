# Creating an E-commerce Product Categorization Model Using Deep Learning

Here, we build a predictive model to categorize products in an e-commerce data set. Product categorization is a supervised classification problem where the product categories are the target classes, and the features are the words extracted from the product description or an image.
The aim is to successfully classify product categories with high precision using state machine learning and deep learning techniques.

## Methodology and Approach

Product classification is one of the classic problem statements in the e-commerce industry, and there are multiple approaches to solve it. Let's use the following approaches.

* Image classification

* Text classification

The problem can be solved in two ways. There are images for every item mapped to a particular category. We need to train deep learning algorithms and use that machine to predict the category whenever there is a new image of the product. But the challenge is, not every time seller provides the image which becomes a problem.

The other approach is multiclass text classification. Instead of images, we need to consider the product description as features and product category as a label to build the classifier. The idea is that a product description has detailed information about a particular product, and with some confidence, the text present in the description can predict the category.

This model can be built using traditional machine learning algorithms (naive Bayes classifier, logistics regression, support vector machine classifier, random forest classifier) and deep neural networks.

We implement the multiclass text classification using different deep neural networks algorithms.
