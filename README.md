# MovieApi
"This is a movie API created with Python web scraping. (Please note that you may encounter unwanted ads.)"

## Getting Started

These instructions will help you understand how to use the CinemaPlus API for accessing movie data.
Making HTTP Requests
You can interact with the CinemaPlus API by making HTTP requests to the following endpoints:
Getmovies
https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies 
for specifqueation 
'https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?'
limits ( the amount of movie u want )
`limit=${limit}&`
title (name of the movie)
`title=${encodeURIComponent(title)}&`
genres 
`genres=${encodeURIComponent(genres)}&`
id
`id=${encodeURIComponent(id)}&`
