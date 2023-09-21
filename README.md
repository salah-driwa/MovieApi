# MovieApi
"This is a movie API created with Python web scraping. (Please note that you may encounter unwanted ads.)"

## Getting Started
Making HTTP Requests

You can interact with the CinemaPlus API by making HTTP requests to the following endpoints:

Get Movies
Endpoint: https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies
For Specification: https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?
Query Parameters:

limit (The amount of movies you want)

Example: limit=10
Description: Use this parameter to specify the number of movies you want to retrieve. Adjust the value as needed, e.g., limit=10 to get 10 movies.
title (Name of the movie)

Example: title=The%20Matrix
Description: Use this parameter to search for movies by title. Replace %20 with spaces in the title, e.g., title=The%20Matrix for the movie "The Matrix."
genres (Genres of the movies)

Example: genres=Action,Adventure
Description: Specify genres as a comma-separated list to filter movies by genre. For example, genres=Action,Adventure to get action and adventure movies.
id (Custom ID for a specific movie)

Example: id=123456
Description: Use a custom ID to retrieve a specific movie. Replace 123456 with the desired movie's unique identifier.
Examples:

To retrieve a list of the first 10 movies:

https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?limit=10
To search for a movie by title, e.g., "The Matrix":

https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?title=The%20Matrix
To filter action and adventure movies:

https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?genres=Action,Adventure
To retrieve a specific movie with a custom ID, e.g., "123456":

https://eu-west-2.aws.data.mongodb-api.com/app/application_movies-yupey/endpoint/movies?id=123456 



Movie Data JSON Description

The following JSON data represents essential details about a movie:

Title: "Mr. Car and the Knights Templar (2023)"

Description: This intriguing adventure unfolds when an art historian stumbles upon a significant archaeological discovery—the cross of the Knights Templar's historical temple. What follows is an unexpected journey as they unite with a diverse group of adventurers. Their mission? To unveil the secrets hidden within this historically impactful artifact.
Genres: Drama, Familial, Adventures

Description: This movie embodies a blend of genres, including drama, familial themes, and thrilling adventures. It promises an engaging experience that caters to a diverse audience.
Image URL:

Movie Poster
Description: The movie poster offers a captivating glimpse into the world of "Mr. Car and the Knights Templar (2023)." Its visual allure invites viewers to explore the intriguing narrative that awaits.
Server URLs: Two server URLs are provided for streaming access.

Server 1: Watch Movie
Server 2: Watch Movie
Description: These server URLs provide access to stream the movie. Click on the links to enjoy "Mr. Car and the Knights Templar (2023)" online.

