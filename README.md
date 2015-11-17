# SamsungAnalysis
Marketing analysis for BUS421

How to use:
Follow these directions for making Twitter dev account:
https://docs.aws.amazon.com/gettingstarted/latest/emr/getting-started-emr-sentiment-create-twitter-account.html

Install tweepy:
http://docs.tweepy.org/en/v3.4.0/install.html

In there, it describes how to get your API Key (aka consumer key), API secret (aka consumer secret), access token, and access token secret. Make a file called "auth.py" and just assign these to the variables listed below. DO NOT push these to a repository.

API_KEY = ""

API_SECRET = ""

ACCESS_TOKEN = ""

ACCESS_TOKEN_SECRET = ""

Also note that this may take a long time to complete; this isn't because of processing time, it's because of Twitter's rate limiting. A sample tweets.txt is included in this repo but this is generated every time you run the code.