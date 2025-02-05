# Movie Search App

## Overview

This is a simple React application that allows users to search for movies using the OMDB API. The app fetches movie details based on a user-provided search term and displays relevant information such as the movie title, genre, poster, and release year.

## Features

Search for movies by title.

Display movie details including title, genre, year, and poster.

Utilizes the OMDB API for fetching movie data.

User-friendly interface with a responsive design.

## Technologies Used

> React.js

> JavaScript (ES6+)

> CSS

> OMDB API

> Netlify (for deployment)

## Installation & Setup

### Prerequisites:

Node.js and npm installed on your local machine.

Steps:

Clone the repository:

git clone https://github.com/your-username/movie-search-app.git
cd movie-search-app

Install dependencies:

npm install

Run the development server:

npm start

Open http://localhost:3000 in your browser.

Deployment

The app is deployed on Netlify.

Ensure API requests use https://www.omdbapi.com/ instead of http:// to avoid mixed content errors.

API Usage

This app uses the OMDB API for fetching movie data. You need an API key to access the service. Replace the placeholder in the code with your own API key:

const apiKey = "YOUR_OMDB_API_KEY";

Troubleshooting

If movies do not display, check the browser console for errors.

Ensure the API key is valid and the request URL uses HTTPS.

If deploying on Netlify, update CORS settings if necessary.

License

This project is open-source and available for use under the MIT License.

Author

Fatou
