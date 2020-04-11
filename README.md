# Udacity-Data-Wrangling
Udacity Data Analyst Nanodegree April 11 2020
Project 4 : Wrangle and Analyse Twitter archive data

# Project Overview
The dataset I will be analysing will be from the twitter archive data of WeRateDogs account where people post their photos of their pet dogs and rate them using the humorous comments about the dog
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

# Software Requirements
* You will need jupyter notebook install in your computer
* The following packages needs to be installed via conda or pip
  1. numpy
  2. pandas
  3. requests
  4. tweepy
  5. json
* You can create a pdf files via jupyter notebook containing only the report and its following pictures

# Project Specifications
# Code functionality and Readability
* All code cell in the notebook wrangle_act.ipynb is error prone and its well written comments and notes with only clean written code and logically understandable

# Gathering Data
Three dataset is used to analyse the WeRateDogs account
1. twiiter_archive_enhanced.csv contains the tweet id and its url of the photo and its caption
2. image_prediction.csv has the prediction for which breed of dog is in the photo and its confidence level
These 2 dataset above can be manually downloaded from the udacity project page
3. twitter_additional_data.csv is to be downloaded via Twitter dev console using the python tweepy library 

# Assessing Data
Assessing is done in 2 parts. First using Visual Assessing using the Excel Spreadsheet
Second is using python numpy and pandas libraries
I have written the quality issues and tidiness issues in the notebook clearly
Each issues is written in each sentence with theirl corresponding column name and its dataset name so we can clearlly visualize these errors

# Cleaning Data
This is most crucial part of data wrangling 
We will clear the issues using the notes we made from assessing phase
* The define,code,test steps of the cleaning process is clearly documented with comment
* Copies of the original dataset is made for cleaning phase whenever we encounter with errors so that we can recreate the dataframe
* All issues are cleaned using python numpy and pandas libraries

# Storing the clean data
After cleaning the data ww will upload it in the master dataframe and save it

# Analysing the data
Only after the prior 4 steps we can go to the analysing phase
I have did four insights and its visualization in the jupyter notebook with clear labels and titles in the graph

# Report
Two reports
* wrangle_act.pdf shows the steps i have used in the wrangling of the data
* act_report.pdf shows the insights i have found in the data after wrangling phase

# Contribute
For the sake of this project I have cleaned only 8 quality issues and tidiness issues.
You can fork this project and can contribute
