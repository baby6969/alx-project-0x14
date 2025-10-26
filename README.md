# ALX Project 0x14

## API Overview
The MoviesDatabase API provides access to a vast collection of movies, TV shows, and related metadata. You can search, retrieve details about movies or series, get information on actors, and explore trending or popular content. The API allows developers to integrate movie data into their applications seamlessly.

## Version
The current version of the API is v1.0 (replace with the exact version from the documentation).

## Available Endpoints
- `/movies`: Retrieve a list of movies with optional filters (e.g., genre, year).
- `/movies/{id}`: Get detailed information about a specific movie.
- `/actors`: Retrieve a list of actors or search by name.
- `/actors/{id}`: Get detailed information about a specific actor.
- `/trending`: Get trending movies or shows for a specific period.
- `/search`: Perform a keyword-based search across movies, TV shows, and actors.

## Request and Response Format
### Request
- Method: `GET` or `POST` (depending on the endpoint)
- Headers: `Authorization: Bearer <API_KEY>` (if required)
- Query Parameters: e.g., `?page=1&genre=action`

Example:

```http
GET https://api.moviesdatabase.com/movies?page=1&genre=action
Authorization: Bearer YOUR_API_KEY

