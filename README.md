# COVID-19 Predictor by Tweet Sentiment
Uses sentiment analysis to predict the number of new COVID-19 cases in English-speaking countries.
Modeled with TensorFlow and Keras, using a GRU RNN. To get started, check out the notebook `main.ipynb` in the notebook directory.

By analyzing the sentiment of Tweets (positive, negative, or neutral), we aim to detect correlations between this data and the time-series COVID-19 case data, allowing us to develop a predictive model. We use GRU units over LSTM for more efficient training, however further experimentation and fine tuning of hyperparameters can help make the model more accurate.

## Data sources
Tweets dataset licensed under CC BY-NC-SA 4.0 sourced from https://github.com/lopezbec/COVID19_Tweets_Dataset.

COVID-19 data licensed under CC BY 4.0 sourced from https://github.com/owid/covid-19-data/tree/master/public/data

### Citations
Christian Lopez, and Caleb Gallemore (2020) An Augmented Multilingual Twitter Dataset for Studying the COVID-19 Infodemic. DOI: 10.21203/rs.3.rs-95721/v1 https://www.researchsquare.com/article/rs-95721/v1
