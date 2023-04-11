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
![Screenshot (334)](https://user-images.githubusercontent.com/111419512/231152576-2a8fa27f-1809-473c-a741-c6c2ea0520d0.png)
![Screenshot (335)](https://user-images.githubusercontent.com/111419512/231152588-d0ef656e-f925-4114-a51f-c1e45d8b97d4.png)
![Screenshot (336)](https://user-images.githubusercontent.com/111419512/231152594-dfa85194-92be-49e7-aee1-083f007a7b58.png)
![Screenshot (337)](https://user-images.githubusercontent.com/111419512/231152600-432be329-69a8-4d65-ba2b-a8eddea7b199.png)
![Screenshot (338)](https://user-images.githubusercontent.com/111419512/231152666-e7385948-28fd-49bd-be71-c8fe483b4d21.png)
![Screenshot (339)](https://user-images.githubusercontent.com/111419512/231152703-58c6e831-ef93-4818-ba23-278dec0a8e55.png)
![Screenshot (340)](https://user-images.githubusercontent.com/111419512/231152723-53e88b1f-d4a8-48a1-8c6f-488f6affb217.png)

