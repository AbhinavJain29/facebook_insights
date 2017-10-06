# facebook_insights
This repository deals with the project of analyzing my FACEBOOK data in **R, python** extracted through Facebook Graph API.

## DIRECTORY INFO:
* **FB_Analysis.html** This is the resulting html file depicting the analysis results, generated through the knit option in R Studio.

* **PythonScripts&Data** It has all the python scripts developed to extract the available data from Facebook and utilizing it to create several other datasets to analyse. The important files are described below:
  
  * **Facebook_Data.ipynb** The Jupyter Notebook containing the entire code to process the **MyFBdata** and extract information in a meaningful way to create several dimensions of analysis.
  
  * **FBposts.csv** The CSV file containing the significant information about each facebook post namely:
    * **DATE**
    * **TIME**
    * **POST_ID**
    * **LIKES**
    * **COMMENTS**
    * **POST_TYPE**
    * **TOTAL_WORDS**
    * **POSITIVE_PROB**
    * **NEGATIVE_PROB**
    * **COMBINED_PROB**
  
  * **words.txt** The text file containing each post's message broken down into significant words and their count, in the form of a **list of dictionaries**.
  
  * **bag.txt** The file containing the *root/stem* of all the words used across all my Facebook Posts, accompanied by their frequency of usage both in terms of number of words and number of posts.

* **R_Scripts** It has all the scripts which perform EDA (Exploratory Data Analysis) on the data.

