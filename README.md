# Data-wrangle
# Introduction 
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness,
then clean it. This is called data wrangling.
You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) pands, numpy, and matplotlib.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs.
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10.
The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project.
This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. 


# Project Steps Overview
- Step 1: Gathering data
  Additional data from the Twitter API
  Gather each tweet's retweet count and favorite ("like") count at the minimum and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter        archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file.

  Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite     count. Note: do not include your Twitter API keys, secrets, and tokens in your project submission.)

- Step 2: Assessing data
    I need to use two types of assessment:
    Visual assessment: each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an       external application (e.g. Excel).
    Programmatic assessment: pandas' functions and/or methods are used to assess the data.

- Step 3: Cleaning data
  I have made of original data before cleaning
  I have used The Define - Code - Test framework
  I have documented The Define - Code - Test framework
  I have documented each issues in few sentences 
  I have successfully cleaned all issues

- Step 4: Storing data
  store the cleaned master DataFrame in a CSV file with the main one named twitter_archive_master.csv. If additional files exist because multiple tables are required for           tidiness, name these files appropriately. Additionally, you may store the cleaned data in a SQLite database 

- Step 5: Analyzing, and visualizing data
   I produce three (3) insights and one (1) visualization.
   I clearly document the piece of assessed and cleaned (if necessary) data used to make each analysis and visualization.

- Step 6: Reporting
  act_report.pdf that communicates all the insights and displays the visualization(s) produced from your wrangled data. This is to be framed as an external document, like a   blog post or magazine article.
