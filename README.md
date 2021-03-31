# Binge-Watcher
A Movie Recommendation and review system. Data taken from IMDB. Used collaborative filtering for Recommendation system. Sentiment analysis using NLP. Deployed on Heroku. Developed using Flask.

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

# Link to the application
Check out the live demo: https://the-movie-cinema.herokuapp.com/



