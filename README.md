# NLP

Retrieving Test Data

There is no dataset available with labelling tweet/post as per mental health index.After lot of research we identified this method for collecting dataset:-
1.Collect data from Twitter based on keywords like Anxiety , Depression , mentalillness, mentalhealth, endthestigma, bellletstalk, alcoholism, alcoholic, insomnia,stressed,alcohol,gun,drug. And for positive sentiments we have collected Twitter data from Kaggle

2.After that  we were able to scrape information from the r/Depression, r/SuicideWatch, r/CasualConversation, and r/All subreddits.from Reddits as well

After merging Twitter,Reddit data we train our model to predict person's mental health condition into 4 category
NOT_SUICIDAL,Early sign,Mid risk,High risk category

We have trained our classification model on NB which unexpectedly did good job.After that we tried LSTM model which gave us decent score.


Next Step:-

We are planning to do more research on getting labelled data from other platform .Also we will enhance our model by constructing useful ngram to understand context in more better way which in turn will make our model more accurate.


