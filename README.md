# Project| Wrangle and Analyze WeRateDogs Data
#### By: Muhammed Abdul-Fattah Salem

## **Introduction**

The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## **Pre-Installation Software Needed**:

To be familiar working in a Jupyter Notebook(python3.0)
The following packages to be installed via conda or pip, Anaconda tutorial 
++ pandas
++ NumPy
++ requests
++ matplotlib
++ tweepy
++ json

## **Project Motivation**

our goal: wrangle WeRateDogs Twitter data to create interesting and trustworthy analysis and visualizations.The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required.

## **Key Points**

 Original ratings (no retweets) that have images only what we need. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.

Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.

Cleaning includes merging individual pieces of data according to the rules of tidy data.
The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.

Storing and Acting on Wrangled Data
The master dataset is analyzed using pandas in the Jupyter Notebook and at least three (3) separate insights are produced. And at least one (1) labeled visualization is produced in the Jupyter Notebook using Python’s plotting libraries.

## **References**

++ https://nfpdiscussions.udacity.com/t/weratedogs-data-wrangling-gathering-data-part/67534/2
++ https://nfpdiscussions.udacity.com/t/cleaning-quality-issues/67893
++ https://www.kite.com/python/answers/how-to-check-if-a-character-is-uppercase-in-python
++ https://nfpdiscussions.udacity.com/t/concerning-name-column/42212/5
++ https://stackoverflow.com/questions/7353968/checking-if-first-letter-of-string-is-in-uppercase/7354011#7354011
++ https://nfpdiscussions.udacity.com/t/project-2-assessing-data/44649/6
++ https://nfpdiscussions.udacity.com/t/insights-and-visualization-weratedogs/40725