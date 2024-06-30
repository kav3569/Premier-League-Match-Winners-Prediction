# Premier-League-Match-Winners-Prediction
This project uses a Random Forest Classifier ML model to predict the outcomes of English Premier League football matches.


Project Overview

In this project, we'll predict the winner of football matches in the English Premier League (EPL).

Project Steps

    Scrape match data using requests, BeautifulSoup, and pandas
    Loading and cleaning match data using Pandas
    Creating predictors for machine learning
    Training an initial Random Forest model using Sci-kit learn
    Improving model precision using rolling averages
    Combining home and away predictions

Data

The project uses a CSV file (matches.csv) containing English Premier League match data. Each row represents a single match with various statistics.


Key Concepts


Data Analysis

    Merging prediction results with original data for deeper analysis
    Analyzing model performance for different teams and scenarios

Data Preprocessing

    Converting date strings to datetime objects
    Handling categorical data (e.g., converting 'venue' to numeric codes)
    Creating new features from existing data


Machine Learning

    Using Random Forest Classifier for prediction
    Splitting data into training and test sets, considering the time series nature of the data
    Evaluating model performance using precision score


Feature Engineering

    Generating rolling averages for team performance metrics
    Creating lag features to capture recent team performance

Model Performance
The final model achieves a precision of approximately 67.5%, a significant improvement over the initial model.

Future Improvements

    Incorporate more seasons of data
    Utilize additional features (e.g., referee, team captain)
    Experiment with different machine learning algorithms
    Integrate additional external data sources



To follow this project, please install the following locally:

    JupyerLab
    Python 3.8+
    Python packages
        pandas
        requests
        BeautifulSoup
        scikit-learn
