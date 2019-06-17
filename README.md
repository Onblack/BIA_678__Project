Project Topic: H-1B issuance prediction on Spark and Cluster

Main Goal: discovered if the performance of accuracy and speed would be better when running spark in cluster rather than local.

Project Procedure:
  1. Get the data from Kaggle: (https://www.kaggle.com/nsharan/h-1b-visa).
  2. Data cleaning and EDA analysis to deal with missing values and outliers.
  3. Transfomred the features by applying clustering and text clustering.
      a. clustering the features of longitute and latitude into location clusters
      b. text clustering the job title, the idea that if any of the job titles are similar in terms of the cosine similarity, they will be          considered to have similar h1b issuance possibilities.
  4. Used different models to test if the model with parallel computing would have a faster performance in spark cluster.
