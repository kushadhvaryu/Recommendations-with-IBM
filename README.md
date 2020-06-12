# Recommendations-with-IBM-Watson

Helps to provide recommendations to IBM Watson users on the next articles the users can read on their platform. 
I analyzed the interactions that users had with articles on the IBM Watson Studio platform, and made recommendations to them about new articles I think they would like. 

Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![ibm-watson-article-recommendation](ibm-watson-article-recommendation.png)

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user,I performed a study of the data available on the IBM Watson Studio platform. You can create your own account to become a part of their community, and get a better understanding of their data by creating an account on the platform [here](https://dataplatform.cloud.ibm.com/).

Github link: https://github.com/kushadhvaryu/Recommendations-with-IBM

## Table of Contents 

1. [Project Motivation](#project)
2. [Installations](#installations)
3. [File Descriptions](#file)
4. [Process](#process)
5. [Acknowledgements](#acknowledgements)

## Project Motivation

This project is being done as a part of the Udacity Data Scientist Nanodegree. It involves Rank based filtering, Collaborative filtering, and SVD models for recommendations.

## Installations:

1. [numpy](https://www.numpy.org/)
2. [pandas](https://pandas.pydata.org/)
3. [matplotlib](https://matplotlib.org/)
4. [pickle](https://docs.python.org/3/library/pickle.html)
5. [re](https://docs.python.org/3/library/re.html)
6. [nltk](https://www.nltk.org/)
7. [scikit-learn](https://scikit-learn.org/stable/)
8. [jupyter](https://jupyter.org/)

## File Descriptions:

* **Recommendations_with_IBM.ipynb:** Jupyter notebook containing main implementation and analysis.
* **Recommendations_with_IBM.html:** A copy of Recommendations_with_IBM.ipynb in html format.
* **user-item-interactions.csv:** Csv file with user-item interactions.
* **articles_community.csv:** Csv file with indexed items.

## The Process:

The process had 5 steps:

1. Exploratory Data Analysis
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Matrix Factorization
5. Extras & Concluding

## Acknowledgements:

1. [IBM Watson](https://www.ibm.com/watson) for providing us the data.
2. Udacity for giving the direction and scope of the project
