# facebook_insights
This repository deals with the project of analyzing my FACEBOOK data in **R, python** through their Developers API.

## DIRECTORY INFO:
* **FB_Analysis.html** This is the resulting html file depicting the analysis results, generated through the knit option in R Studio.

* **FacebookToken** It contains the general information associated with the Facebook Developer account.

* **PythonScripts&Data** It has all the python scripts developed to extract the available data from Facebook and utilizing it to create several other datasets to analyse. The important files are described below:

  * **MyFBdata.txt** The file contaning the Facebook data extracted through API in one big JSON file.
  
  * **Facebook_Data.ipynb** The Jupyter Notebook containing the entire code to process the **MyFBdata** and extract information in a meaningful way to create several dimensions of analysis.
  
  * **FBposts.csv** The CSV file containing the significant information about each facebook post namely:
    * **DATE**
    * **TIME**
    * **POST_ID**
    * **LIKES**
    * **COMMENTS**
    * **POST_TYPE**
    * **TOTAL_WORDS**
  
  * **FBposts_Words.csv** The CSV file based on *FBposts.csv* but having the column for **Unique Words** for every post.
  
  * **FBposts_Senti.csv** The CSV file based on *FBposts_Words.csv* but contains the **Sentiment Analysis** for every post.
  
  * **posts.txt** The text file containing the messages of all the Facebook Posts written so far.
  
  * **words.txt** The text file containing each post's message broken down into significant words and their count, in the form of a **list of dictionaries**.
  
  * **bag.txt** The file containing the *root/stem* of all the words used across all my Facebook Posts, accompanied by their frequency of usage both in terms of number of words and number of posts.
  
  * **LikesComments.txt** The file whose contents are represented in the form of a dictionary depicting the mapping of Friends to Likes.

* **R_Scripts** It has all the scripts which perform EDA (Exploratory Data Analysis) on the data.
  * **Monthly_FB_data.csv** The CSV file created in R from the *FBposts.csv* file to look into the monthly data for all the facebook posts.
  
  * **Yearly_FB_data.csv** The CSV file crated in R from the *FBposts.csv* file to look into the yearly data for all the facebook posts.

