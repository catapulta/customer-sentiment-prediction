# customer-sentiment-prediction
Sentiment Prediction of Customer Reviews

With businesses increasingly placing greater emphasis on customer service, feedback from customers becomes an important channel for business owners to assess performance. Thus, businesses frequently need to evaluate and act on the sentiment of an opinion.  We create a model that can classify the sentiment of short reviews into positive or negative. The sentiment prediction model is trained and selected using a Yelp dataset that includes stars assigned by users to business reviews. We first partition these stars into positive and negative sentiment and then predict the sentiment of a user review. We explore two approaches for creating features: uni-gram bag of words model and pre-trained embeddings. Both models extract semantic information from the database based on word co-occurrence. We achieve a test accuracy of 87% in the classification of reviews on a balanced set.

Also, take a look at doc2vec.ipynb for an implementation of doc2vec using the GenSim library. Long story short, doc2vec's performance is better but not drastically so.

![Competition poster](/poster.png)
