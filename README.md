# **Analysis of Popular YouTube Videos** #

**Project Description**

The purpose of this project is to analyze the topics and sentiment of YouTube videos and the comments viewers have left on those videos. YouTube has become a worldwide popular source for information about a variety of topics, for better or for worse. With the following data, I intend to analyze what topics are popular with users. Within the data, all videos are assigned a keyword and that keyword will serve as the main topic of every video. Additionally, I will look at the comments left under these videos and analyze the sentiment behind them. After all, there isn't a corner of the internet where users aren't willing to share their opinion on the content they're consuming. I will use this project to determine if that sentiment is more often positive or negative.

The data used for this project is from [Kaggle](https://www.kaggle.com/datasets/advaypatil/youtube-statistics).

**Set-up**

* Clone my git repository and into its directory
    * git clone https://github.com/alishacopley/youtube_data_analysis.git

* To run this, you will need to:
    * pip install pandas
    * pip install matplotlib
    * pip instal numpy
    * Install Jupyter Notebook
    * **OR** simply install Anaconda Navigator

* Finally, run the Jupyter Notebook: youtube_data_analysis.ipynb

**Features**

1. I read in two CSV data files using pd.read_csv

2. I cleaned my data by removing unneeded columns of data within the dataframe, renaming columns to make the data more easily understood, and then dropped any null values from the data. I also merged the two CSV files into a single dataframe using pandas merge and then did an outer join on the data.

3. I used matplotlib to present my analysis of the data. Here I created a pie chart to show how frequently comments of different sentiments were left under the videos. Then I created a bar chart to show how often those different types of comments received likes. After that I created two different bar charts regarding topics of videos. One was to see what video topics were most popular and another was to see what video topics received the most comments.

4. I utilized a virtual enviroment for this project and install the packages I needed in the environment. After I exported that information into an environment.yml file and put that in my repository.

5. Finally, I annotated my code within my Jupyter Notebook using markdown cells and created this README file.