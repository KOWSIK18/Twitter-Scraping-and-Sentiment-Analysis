Twitter Data Analysis with Sentiment Analysis
This project is a Python script that allows you to perform a search query on Twitter using snscrape library and analyze the tweets data by performing sentiment analysis, and generating a word cloud.

#Prerequisites
Python 3.x installed on your system.
Libraries needed: snscrape, pandas, matplotlib, wordcloud, nltk, docx.
You can install the required libraries by running:


pip install snscrape pandas matplotlib wordcloud nltk python-docx
#How to Use
1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. Run the command python twitter_data_analysis.py to execute the script.
4. Enter the search query, start date, end date and the number of tweets you want to retrieve.
5. After the script finishes executing, a Word document will be generated in the same directory with the name of the search query.
6. The Word document will contain the following analysis:
  . Dataframe of the retrieved tweets.
  . Word cloud of the frequently used words.
  . Word cloud of frequently used positive words.
  . Word cloud of frequently used negative words.
#Note

. The start date and end date should be in the format 'yyyy-mm-dd'.
. If start date or end date is not provided, the default values will be used ('2019-01-01' for start date and '2019-06-30' for end date).
. The word cloud will be saved as a PNG file in the same directory with the name of the search query and the type of the word cloud (e.g., search_query_positive.png).
. If there are no positive or negative words, the script will generate a message saying so.
