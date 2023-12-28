# ML-Projects

This repo contains different ML projects, an overview of various different ML algorithms such as Shallow Learning Algos, Deep Learning, NLP, etc. I have updated and will keep updating this readme doc for your reference. This repo is sstructured in folder formats. In each folder I have completed one project. The list of projects done in this repo are as follow:

* Boston_House_Price_Prediction - loaded dataset from sklearn.dataset and used Linear Regression over important features to predict prices of properties.
* ImageClassification - loaded mnist data from keras datasets and created a sequential neural network using keras and tesnorflow to classify accurate digits from datasource of handwritten digits
* MovieRecommendation - data is collected from public source (Kaggle), used cosine_similarity over genres of movie to provide recommendation. To explain in one line, the code translates selected movie genres and transform it into a vector and then vectors from different movies are compared using cosine similarity to find relation between the movies, and using threshold value its decided if the movie should be recommended or not.
* StockMarketPrediction - downloaded WMT historical data from yfinance library (yes Python has a library to download stock price data as well), used ARIMA model and grid search to optimise (p,d,q) values.
* iMDB_Movie_Review - collected data from public source (Kaggle), the project overview can be stated as classifying the review in binary format, i.e, either positive or negative, used BERT (bert-base-uncased, bcz its a lighter version) to tokenise review sentences and trained using BERTForSequenceClassification over trained data and checked the model performance on test data.
