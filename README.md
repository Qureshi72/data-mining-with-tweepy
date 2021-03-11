# Data Mining With Tweepy

[Tweepy](https://www.tweepy.org/) is an easy-to-use Python library for accessing the Twitter API. To install Tweepy, follow the instructions outlined [here](https://docs.tweepy.org/en/latest/install.html). In order to use Twitter's API, you must have register your client application with Twitter. Create a new application and once you are done you should have your consumer key and secret. More information can be found [here](https://developer.twitter.com/en/apply-for-access). Once you have the app setup, copy the keys to the corresponding variables in generate_tweets.ipynb. In order to use the notebooks (the .ipynb files), you will need Jupyter Notebook, which can be installed through [Anaconda](https://docs.anaconda.com/anaconda/install/)

### [generate_tweets.ipynb](https://github.com/aennisjr/data-mining-with-tweepy/blob/main/generate_tweets.ipynb)
This file is used to collect the tweets from Twitter. It uses a for loop to search for a collection of phrases and saves the resutls in CSV files with the same name. If the file already exists when you execute the notebook, it will append the new tweets to the end of the CSV file.

### [generate_charts.ipynb](https://github.com/aennisjr/data-mining-with-tweepy/blob/main/generate_charts.ipynb)
Used for exploring the CSV files and for generating the charts (which will be saved in the **charts** directory). Set the value of the **dataset_title** variable to the title of your CSV file then execute the code.
