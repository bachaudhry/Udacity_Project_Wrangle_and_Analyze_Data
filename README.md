# Udacity Data Analyst Nanodegree Project - Wrangle and Analyze Data

## Introduction

This report is part of the seventh project of Udacity’s Data Analyst Nanodegree. The purpose of this project was to demonstrate key principles 
and methodologies related to the data wrangling and cleaning process, which is known to take up a major portion of the Data Analyst’s time.

In this project we dealt the dataset provided by the Twitter account @dog_rates, which is also known as WeRateDogs. In short, the tweets 
in this account contain pictures of people’s dogs, a rating on a scale from 1 – 10 and humorous comments about the dogs in question. 
The project was executed using Jupyter Notebooks and contains the following sections:

1. Gathering Data 
2. Assessing Data 
3. Observations and Course of Action 
4. Cleaning Data 
5. Generating Insights

# Data Gathering

The data used in this project was gathered from three different sources, which in turn made up three data sets. These were:

1. Twitter Data: We were provided the master archive called “twitter_archive_enhanced.csv” by Udacity.
2. Image Prediction Data: This file contains a classification of dog breeds based on the output results of a Convolutional Neural Network, 
which analyzed the images of dogs in each tweet.
3. Twitter API and JSON Data: This data was gathered by querying the Twitter API for each tweet’s JSON data, using Python’s “Tweepy” library. 
The data was then stored in a file valled “tweet_json.txt”. The file was then read, line by line, into a dedicate pandas dataframe. 
It must be noted that since I wasn’t able to gain access to a Twitter developer account, I proceeded to manually download the file from 
Udacity’s project resources section.

Gathering, by itself, can prove to be pretty challenging. This is especially true for scraping website APIs for JSON data. However, 
even in the face of incomplete documentation and support on various websites on how to access their APIs, I took comfort in the fact 
that there was a number of highly detailed blogs and YouTube tutorials which clarified the process.
