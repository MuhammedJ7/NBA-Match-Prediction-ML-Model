# NBA-Match-Prediction-ML-Model

NBA Match Prediction Code
This project aims to create a code that can predict the results of NBA games using various data sources and machine learning models.
This is a very interesting and challenging task that involves using data analytics and machine learning techniques to forecast the outcomes of NBA games.


Data Sources
The code uses the following data source to collect and process the relevant information for each game:

basketball-reference.com: This website provides comprehensive statistics and data for NBA teams and players, such as game logs, box scores, standings, advanced metrics, and more. The code will use the nba-prediction GitHub topic to scrape the data from this website using Python and BeautifulSoup.
The code uses the [requests] library to get the predictions from this website and parse them with Python.
[nba-prediction · GitHub Topics · GitHub]: This GitHub topic contains various repositories and projects that are related to NBA prediction using different methods and models. The code will use the [git] command to clone and run some of the projects that are relevant and useful for this task.

Machine Learning Models
The code will use the following machine learning models to train and test the prediction accuracy for each game:

[Logistic Regression]: This is a supervised learning model that can be used for binary classification problems, such as predicting the winner of a game. The code uses the [scikit-learn] library to implement this model with Python.

Evaluation Metrics
The code uses the following evaluation metrics to measure the performance and accuracy of the prediction models for each game however i plan on running a few others such as the MSE MAE at a later time:

[Accuracy]: This is the ratio of correctly predicted outcomes to the total number of predictions. It is a simple and intuitive metric that can be used for binary classification problems, such as predicting the winner of a game.
