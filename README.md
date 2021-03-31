# Binge-Watcher
A Movie Recommendation and review system. Data taken from IMDB. Used collaborative filtering for Recommendation system. Sentiment analysis using NLP. Deployed on Heroku. Developed using Flask.

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

# Link to the application
Check out the live demo: https://bingewatcherdamodharsai.herokuapp.com/

# Functionalities
1) Multilingual Movies are available in almost all the languages.
2) Autocomplete Option suggests movie names.

![image](https://user-images.githubusercontent.com/78199382/113113823-50fc6f00-9228-11eb-8d25-d76e8d0d16ce.png)

![image](https://user-images.githubusercontent.com/78199382/113113909-6b364d00-9228-11eb-81d9-037b9859b73c.png)

Details about the cast and information about the cast

![image](https://user-images.githubusercontent.com/78199382/113113977-83a66780-9228-11eb-9cd1-b6738038beda.png)

![image](https://user-images.githubusercontent.com/78199382/113114151-b05a7f00-9228-11eb-971c-a4634cc8b1ca.png)

![image](https://user-images.githubusercontent.com/78199382/113114291-d08a3e00-9228-11eb-8baf-5ea4081e8776.png)

Reviews regarding the particular movie, classification as positive or negative review

![image](https://user-images.githubusercontent.com/78199382/113114401-edbf0c80-9228-11eb-8015-6f62bf2cda05.png)

Recommends movies,the movies similar to the particular movie.

![image](https://user-images.githubusercontent.com/78199382/113114525-0deecb80-9229-11eb-9b6b-4c2fe0c1dcc7.png)





