# Big data project

## Steps

This project was part of the Big Data course of the M2 Statistics and Econometrics, at Toulouse School of Economics. The general goal was  to wrangle data and train a model using libraries of our choice. There was be no "walkthrough", we were free to do your own machine learning as long as we followed these guidelines:

1. Choose **any** dataset from http://archive.ics.uci.edu/ml/index.php or [kaggle datasets](https://www.kaggle.com/datasets) or [data.gouv](https://www.data.gouv.fr/fr/)
2. Download the dataset file and upload to Databricks. If you want to use another dataset, it's okay as long as it's public.
3. Explore it using DataFrames, including **at least** the following steps:
    1. Reading the file into a DataFrame
    2. Running some aggregations and explorations using DataFrame functions
4. Your solution notebook must have a part using MLlib, including **at least** the following steps:
    1. Converting into MLlib matrix
    2. Applying some statistics with the  MLlib's API
    3. Learning a classification or regression model
    4. Applying the model to the test data and computing the errors
5. You'll also train another model using Pipelines:
    1. Creating a pipeline with **at least** one feature extraction/manipulation and one model estimator
    2. Fitting the pipeline to the training data
    3. Applying the model to the test data and computing the errors
6. Finally you should try to apply a third party ML library for instance [tune scikit-learn meta-parameters using spark](https://docs.databricks.com/spark/latest/mllib/third-party-libraries.html#scikit-learn).
7. No report needed !! Just add some comment as part of the Notebook. The notebook should be self-sufficient. I'm expecting a short written analysis (and you should know that "We found nothing after testing *this* and *that* is already a valuable result), but also some plots. You can use any library (matplotlib, bokeh...). Just be sure to [watch this video first](https://www.youtube.com/watch?v=xAoljeRJ3lU)
  
## Resources:
  - [Spark MLlib guide](https://spark.apache.org/docs/latest/ml-guide.html)
  - [Databricks MLlib guide](https://docs.databricks.com/spark/latest/mllib/index.html#)
  - [pyspark MLlib RDD API docs](https://spark.apache.org/docs/latest/api/python/pyspark.mllib.html)
  - [pyspark MLlib DataFrame API docs](https://spark.apache.org/docs/latest/api/python/pyspark.ml.html)
  - [pyspark complete docs](https://spark.apache.org/docs/latest/api/python/)
  - [Course Homepage](https://waterponey.github.io/SparkCourse/)
