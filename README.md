# We-Rate-Dogs-Twitter-Archive

### Introduction

>Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it; i.e. data wrangling. I then documented my wrangling efforts in a Jupyter Notebook, plus showcased them through analyses and visualizations using Python (and its libraries) and/or SQL.

>The dataset that I wrangled (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.


### Project Steps Overview

>Step 1: Gathering data

>Step 2: Assessing data

>Step 3: Cleaning data

>Step 4: Storing data

>Step 5: Analyzing, and visualizing data

>Step 6: Reporting

   - data wrangling efforts
   - data analyses and visualizations

### Software Needed

> You need to be able to work in a Jupyter Notebook on your computer. 

> The following packages (libraries) need to be installed. 
- pandas
- NumPy
- requests
- tweepy
- json

### Project Motivation

>Context

>The Goal: wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

>The Data

>In this project, I worked on the following three datasets.

- Enhanced Twitter Archive

>The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

- Additional Data via the Twitter API

>Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API. Well, "anyone" who has access to data for the 3000 most recent tweets, at least. But you, because you have the WeRateDogs Twitter archive and specifically the tweet IDs within it, can gather this data for all 5000+. 

- Image Predictions File

> The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
