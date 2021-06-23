# Real Time Sentiment Detection of Tweets

This is the course project for Big Data Analysis class

Advisor: [Prof. Vikram Goyal](http://faculty.iiitd.ac.in/~vikram/)

We streamed tweets by using [Apache Kafka](https://kafka.apache.org/) to process, filter out and classify tweets into positive and negative sentiments. We trained 5 linear classifiers:  support vector machines, gradient boosting machines, random forests, decision trees andlogistic regression on [Sentiment140](https://www.kaggle.com/kazanova/sentiment140) dataset after data processing using [Apache Spark's MLlib (pyspark)](https://spark.apache.org/docs/latest/ml-guide.html). For the final sentient we applied the bagging method using the models to detect sentiment of a tweet.

Team: [ShreyaSharma](https://github.com/lshreyasharmal) & [AbhishekChauhan](https://github.com/Abhi744)
