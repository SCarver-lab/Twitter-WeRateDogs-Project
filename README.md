
## Twitter Archive Wrangling and Analysis of "WeRateDogs"

## by Secil Carver

<a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Udacity Data Analyst Nanodegree</a><br>
<em>Project 5: Data Visualization</em>

<a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Udacity - Data Analyst Nanodegree</a><br>
<em>Project 4: Data Wrangling</em>

### Table of Contents

1. [Project Overview](#overview)
2. [Project Flow](#projectflow)
3. [Requirements](#requirements)
4. [Key Files](#keyfiles)
5. [Summary of Findings](#findings)
6. [Acknowledgements](#acknowledgements)

<p style = "font-family:georgia,garamond,serif;font-size:16px;font-style:italic;">
    
### 1. Project Overview <a name="overview"></a>

WeRateDogs is a twitter group that rates people's dogs on an unusual and humorous way. For this project I used three datasets, one in a .csv format, the second one in .tsv format, the third was a Jason extract from twitter API. The csv dataset included over 2,000 instances and 18 variables including datetime of tweets, text, rating numerator, rating denominator, dog age classifications as 'duggo','floofer','pupper','puppo'. The second dataset had images as well as probablity of machine image predictions. The API dataset had tweet id, retweet count and favorite count. 
After meging all three datasets, I was able to find out most tweeted dog breed from image predictions, most common dog life stage, most common dog names.


### 2. Project Flow <a name="projectflow"></a>
    
- Step 1: Gathering data
- Step 2: Assessing data
- Step 3: Cleaning data
- Step 4: Storing data
- Step 5: Analyzing, and visualizing data
- Step 6: Reporting wrangling efforts, data analyses, and visualizations


### 2. Requirements <a name="requirements"></a>

This project was created using Anaconda's Jupyter Notebook using the language python. The following language and packages were used:

- python 3.7.11
- pandas 
- numpy 
- matplotlib 
- json
- requests
- pil
- io


### 3. Key Files <a name="keyfiles"></a>

The project consist of three main files: 
- `wrangle_act.ipynb`: 
    This is the file I used to gather, assess, clean, store, and analyze the data.

- `wrangle_report.md` : 
    This is a markdown file explaining the gathering, assessing, and cleaning efforts for the project.

- `act_report.ipynb`: 
    This file is dedicated only to the findings and visuals.
    
-- Datasets used: `twitter-archive-enhanced.csv`, `image_predictions.tsv`

    
### 4. Summary of Findings <a name="findings"></a>

- The most tweeted dog breed is Golden Retriever
- The most commmon dog name is Charlie
- There is a high correlation between retweet count and favorite count. The more a tweet is retweeted the higher the favorite count.
- The most favored and retweeted tweet is a clip of a Golden Retriever in a pool
- The most common dog life stage is 'pupper'
    
    
### 5. Acknowledgements <a name="acknowledgements"></a>
This project was completed as a requirement for Udacity's <a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Data Analyst Nanodegree</a>. The dataset was provided by Udacity.
