# Movie App

## Overview
This is a simple Movie App that fetches and displays popular movies using The Movie Database (TMDb) API. Users can search for movies by title and view details such as ratings and overviews.

## Features
- Fetches popular movies from TMDb API
- Displays movie posters, titles, ratings, and overviews
- Implements a search functionality to find movies by title
- Responsive design with CSS styling

## Technologies Used
- **HTML**: Structure of the application
- **CSS**: Styling and layout
- **JavaScript**: Fetching and displaying movie data
- **TMDb API**: Provides movie details

## Project Structure
```
Movie App/
│── index.html      # Main HTML file
│── style.css       # CSS file for styling
│── script.js       # JavaScript file for functionality
```

## Installation & Setup
### Prerequisites
- A web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (to fetch movie data from TMDb API)

### Steps
1. Clone or download this repository.
2. Open `index.html` in your browser.

## How It Works
1. When the page loads, it fetches a list of popular movies from TMDb API.
2. Movies are displayed with their poster, title, rating, and overview.
3. Users can search for specific movies using the search bar.
4. The app dynamically updates the UI to show search results.

## API Usage
This app uses TMDb API endpoints:
- **Fetch popular movies**: `https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1`
- **Search movies**: `https://api.themoviedb.org/3/search/movie?api_key=YOUR_API_KEY&query=SEARCH_TERM`

Replace `YOUR_API_KEY` with a valid TMDb API key.


## Contact Information
For any queries or suggestions, feel free to reach out:
- **Phone:** +254-112-876-340
- **Email:** mureithilewins@gmail.com

## License
This project is open-source and can be modified and distributed as needed.

