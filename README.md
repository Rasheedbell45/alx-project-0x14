# alx-project-0x14

## API Overview

The MoviesDatabase API provides a comprehensive interface to access information related to movies, TV shows, actors, genres, and more. It allows developers to retrieve trending media, search for specific titles or people, and access detailed metadata including trailers, ratings, and release information. The API supports rich filtering options and is frequently used in applications involving entertainment content curation or discovery.

## Version

v3

## Available Endpoints

| Endpoint | Description |
|----------|-------------|
| `/movie/popular` | Returns a list of the current popular movies. |
| `/movie/{movie_id}` | Provides detailed information about a specific movie. |
| `/search/movie` | Search for movies by title. |
| `/person/{person_id}` | Get details about a particular actor or crew member. |
| `/genre/movie/list` | Fetch a list of all movie genres. |
| `/trending/{media_type}/{time_window}` | Get trending movies, shows, or people. |
| `/authentication/token/new` | Generate a new request token for user authentication. |

## Request and Response Format

### Example Request

**GET** `/movie/popular?api_key=YOUR_API_KEY&page=1`

**Headers:**
```http
Content-Type: application/json
