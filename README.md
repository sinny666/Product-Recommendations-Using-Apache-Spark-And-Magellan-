# Product Recommendations Using Apache Spark + Magellan
## What is Magellan ?

Magellan is a flexible, AI-powered Analytics platform that combines open source ML with advanced analytics, enterprise-grade BI, and capabilities to acquire, merge, manage and analyze Big Data and Big Content stored in your Enterprise Information Management (EIM) systems. Magellan enables machine-assisted decision making, automation, and business optimization.

## What is Spark Machine Learning ?

Apache Spark’s machine learning library makes practical machine learning scalable and easy. The library consists of common machine learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, lower-level optimization primitives, and higher-level pipeline APIs.

## What is this Notebook about?

In this magellan notebook, you will use Apache Spark and the Spark machine learning library to build a Product Recommendation System for Innovate Bank

## How Does a Recommendation Engine Work?

There are different methods for building a recommender system, such as, user-based, content-based, or collaborative filtering. Collaborative filtering calculates recommendations based on similarities between users and products. For example, collaborative filtering assumes that customers that purchase similar financial products will also have similar opinions on financial products that they haven't purchased. The alternating least squares (ALS) algorithm provides collaborative filtering between users and products to find products that the customers might like, based on their previous purchase history.

## Notebook Requirements:

- customer_accounts (Historical Data on Products Purchased By Customers)
- customer_offers (Sample Data To Score - list of products customers do not currently have)
- Magellan - Pyspark Kernel
- Magellan Version 16.6
