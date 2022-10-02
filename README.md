# Recommendation-systems
Recommendation systems are becoming increasingly important in today’s extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours. Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.

The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies. This is achieved through predictive modeling and heuristics with the data available.

## About this project
This is a streamlit web application that can recommend various kinds of similar movies based on an user interest. here is a demo,


## Dataset

The dataset available for this application is present on [dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## How to run the project
Clone the repository
```bash
https://github.com/saurabhznaikz/Movie-recommendation-system.git
```

Create conda enviornment after creating repository
```bash
conda create -n movie python=3.7.10 -y
conda activate movie
```
install requirements
```bash
pip install -r requirements.txt
```
run streamlit app
```bash
streamlit run app.py
```
