# Gathering Data Twitter Weratedogs Archive
Udacity's Data Analyst Nanodegree - Project 4

Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Asnwered questions can be find quickly in the act report. 

### Repository content guidance 

* wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data
* wrangle_report.pdf or wrangle_report.html: documentation for data wrangling steps: gather, assess, and clean
* act_report.pdf or act_report.html: documentation of analysis and insights into final data
* twitter_archive_enhanced.csv: file as given
* image_predictions.tsv: file downloaded programmatically
* tweet_json.txt: file constructed via API
* twitter_archive_master.csv: combined and cleaned data any additional files (e.g. files for additional pieces of gathered data or a database file for your stored clean data)

### Prediction Data
So for the last row in that table:

* tweet_id is the last part of the tweet URL after "status/" → https://twitter.com/dog_rates/status/889531135344209921
* p1 is the algorithm's #1 prediction for the image in the tweet → golden retriever
* p1_conf is how confident the algorithm is in its #1 prediction → 95%
* p1_dog is whether or not the #1 prediction is a breed of dog → TRUE
* p2 is the algorithm's second most likely prediction → Labrador retriever
* p2_conf is how confident the algorithm is in its #2 prediction → 1%
* p2_dog is whether or not the #2 prediction is a breed of dog → TRUE
