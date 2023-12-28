# ML-Projects

This repo contains different ML projects, an overview of various different ML algorithms such as Shallow Learning Algos, Deep Learning, NLP, etc. I have updated and will keep updating this readme doc for your reference. This repo is structured in folder formats. In each folder I have completed one project. You won't find any issues while using the sourcecode or even finding data as well. Related data are either used from Python library itself or if any external data has been used, then data is also uploaded in the folder(s). 

The list of projects done in this repo are as follow:

* Boston_House_Price_Prediction - loaded dataset from sklearn.dataset and used Linear Regression over important features to predict prices of properties.
* ImageClassification - loaded mnist data from keras datasets and created a sequential neural network using keras and tesnorflow to classify accurate digits from datasource of handwritten digits
* MovieRecommendation - data is collected from public source (Kaggle), used cosine_similarity over genres of movie to provide recommendation. To explain in one line, the code translates selected movie genres and transform it into a vector and then vectors from different movies are compared using cosine similarity to find relation between the movies, and using threshold value its decided if the movie should be recommended or not.
* StockMarketPrediction - downloaded WMT historical data from yfinance library (yes Python has a library to download stock price data as well), used ARIMA model and grid search to optimise (p,d,q) values.
* iMDB_Movie_Review - collected data from public source (Kaggle), the project overview can be stated as classifying the review in binary format, i.e, either positive or negative, used BERT (bert-base-uncased, bcz its a lighter version) to tokenise review sentences and trained using BERTForSequenceClassification over trained data and checked the model performance on test data.


#### Before running any project, run the requirements.txt file first to have seamless experience.

I hope this repo meets what you are looking for, and helps you understand ML concepts easily bcz I tried to keep my code as simple as possible. Still if there is any doubts or any suggestions, please feel free to connect and communicate and we can discuss it openly (How to connect - find it in my bio). Till then, Happy Learning!
