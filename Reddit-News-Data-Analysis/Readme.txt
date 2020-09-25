Reddit-News Data Analyzer

Description:
This project intends to offer some insights into news headlines from 2008-2016 taken from Reddit. Using data science libraries Pandas and Pyspark with Python the data was manipulated and analyzed to get two key insights about what was going on in the world from 2008-2016. The project first looks at the Top 10 most common topics discussed and then does some simple sentiment analysis.

The notebook in this directory is divided into the following sections:
	1. Library Installations
	2. Initial insights into data
	3. Top 10 discussed topics
	4. Sentiment Analysis

For section 4, the sentiment analysis was done in using both Pandas and Pyspark DF with TextBlob for the sentiment analysis. TextBlob is a library that is passed a string that can then be used to do NLP on it.

Reference to TextBlob: https://textblob.readthedocs.io/en/dev/quickstart.html

Usage:
The notebook can be used to analyze any set of news data that you want to extract the Top 10 most discussed topics and to perform sentiment analysis. The notebook below uses the Reddit-News.csv data file that can be found in the project directory.

The notebook goes through section-by-section and describes each operation on the data till we get the end result.

References:
The following references were helpful in creating this project:

https://spark.apache.org/docs/latest/api/python/pyspark.sql.html
https://textblob.readthedocs.io/en/dev/quickstart.html
https://medium.com/analytics-vidhya/congressional-tweets-using-sentiment-analysis-to-cluster-members-of-congress-in-pyspark-10afa4d1556e
