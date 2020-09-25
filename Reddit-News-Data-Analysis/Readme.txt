{\rtf1\ansi\ansicpg1252\cocoartf2513
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fswiss\fcharset0 Helvetica-Bold;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs48 \cf0 Reddit-News Data Analyzer\
\

\f1\b\fs36 \ul Description:\

\f0\b0\fs28 \ulnone This project intends to offer some insights into news headlines from 2008-2016 taken from Reddit. Using data science libraries Pandas and Pyspark with Python the data was manipulated and analyzed to get two key insights about what was going on in the world from 2008-2016. The project first looks at the Top 10 most common topics discussed and then does some simple sentiment analysis.\
\
The notebook in this directory is divided into the following sections:\
	1. Library Installations\
	2. Initial insights into data\
	3. Top 10 discussed topics\
	4. Sentiment Analysis\

\f1\b\fs36 \ul \

\f0\b0\fs28 \ulnone For section 4, the sentiment analysis was done in using both Pandas and Pyspark DF with TextBlob for the sentiment analysis. TextBlob is a library that is passed a string that can then be used to do NLP on it. \
\
Reference to TextBlob: {\field{\*\fldinst{HYPERLINK "https://textblob.readthedocs.io/en/dev/quickstart.html"}}{\fldrslt https://textblob.readthedocs.io/en/dev/quickstart.html}}\
\

\f1\b\fs36 \ul Usage:\

\f0\b0\fs28 \ulnone The notebook can be used to analyze any set of news data that you want to extract the Top 10 most discussed topics and to perform sentiment analysis. The notebook below uses the Reddit-News.csv data file that can be found in the project directory.\
\
The notebook goes through section-by-section and describes each operation on the data till we get the end result.\
\

\f1\b\fs36 \ul References:\

\f0\b0\fs28 \ulnone The following references were helpful in creating this project:\
\
{\field{\*\fldinst{HYPERLINK "https://spark.apache.org/docs/latest/api/python/pyspark.sql.html"}}{\fldrslt https://spark.apache.org/docs/latest/api/python/pyspark.sql.html}}\
{\field{\*\fldinst{HYPERLINK "https://textblob.readthedocs.io/en/dev/quickstart.html"}}{\fldrslt https://textblob.readthedocs.io/en/dev/quickstart.html}}\
{\field{\*\fldinst{HYPERLINK "https://medium.com/analytics-vidhya/congressional-tweets-using-sentiment-analysis-to-cluster-members-of-congress-in-pyspark-10afa4d1556e"}}{\fldrslt https://medium.com/analytics-vidhya/congressional-tweets-using-sentiment-analysis-to-cluster-members-of-congress-in-pyspark-10afa4d1556e}}\
}