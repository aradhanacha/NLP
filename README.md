# NLP

Retrieving Test Data

The test data described below is extremely biased as it's scrapped with the keyword depression.
The first big challenge we ran into was how to find an appropriate dataset in order to train our machine learning model. After a lot of researching and learning how to web scrape effectively, we were able to scrape information from the r/Depression, r/SuicideWatch, r/CasualConversation, and r/All subreddits. Furthermore, the reddit API only allowed a maximum of 100 posts, so we had to learn how to use a wrapper tool called praw in order to scrape 1000 posts from each subreddit. Another challenge was creating the chat feature in realtime. We learned how to use socket.io to create the forum and chat feature so that people can messages each other in realtime.
