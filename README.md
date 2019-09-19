# r-twitter-
Twitter Sentiment Analysis R Tutorials

SYSTEM REQUIREMENTS: 
Rstudio needed version 3.6.1
install the packages following below
{
  ("twitteR")
  ("stringr")
  ("ROAuth")
  ("RCurl")
  ("ggplot2")
  ("reshape")
  ("tm")
  ("RJSONIO")
  ("wordcloud")
  ("gridExtra")
  ("plyr")
  ("e1071")
}
PROCESS.

Step1: create a Twitter Account And access the consumer and sceret key (4 keys)
Step2: extract all the keys(4 keys) and run autentication.r file to extract tweets of your prefered number
step3: now clean the tweets using Cleaning.R And run Word_database.R(which includes the Positive and negative words). 
download all the postive words and negative words from google and save it as pos.words & neg.words in the current R documents.file. 
step4:now run the score_sentiment and Fun_on_tweet.R
step5: run all the percentage.R,graphs.R, top_10_hashtags.R,top_trends.R,wordcloud.R
step6: now runapp in Front end in Ui.R or Server.R 
step7: so that you can give prescribed term to search and see te postive and negative analysis of the tweets in twitter. 


Installation of R
Twitter Authentication to access API

authentication.R
cleaning_tweet.R, word_database.R (including positive-words.txt, negative-words.txt)
score_sentiment.R, func_on_tweet.R
percentage.R, graphs.R, top_10_hashtags.R, top_trends.R, wordcloud.R
Front end folder(Ui.R , Server.R)
