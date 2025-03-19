Description

The Movie & TV Show App is a full-stack web application that allows users to discover, search, and watch trailers of their favorite movies and TV shows. Built using modern technologies, this platform provides a seamless experience with a visually appealing user interface, secure authentication, and robust backend support. Users can also explore similar recommendations, track their search history, and enjoy an optimized viewing experience. Whether you are a movie enthusiast or just looking for something new to watch, this app has got you covered!

Tech Stack

Frontend: React.js, Tailwind CSS
Backend: Node.js, Express.js, MongoDB
Authentication: JSON Web Token (JWT)

Features

Secure authentication with JWT
Fully responsive UI
Fetch Movies and TV Shows from TMDB API
Search for actors and movies
Watch trailers of movies & shows
Fetch and display search history
Get similar movies & TV show recommendations
Stunning landing page design
Easy deployment
And many more exciting features!

Setup & Installation

1. Environment Variables

Create a .env file in the root directory and add the following:

MONGO_URI= mongodb+srv://<username>:<password>@cluster0.qjw1x.mongodb.net/netflix_db?retryWrites=true&w=majority&appName=Cluster0
PORT=5000
JWT_SECRET=my_really_hard_to_decode_secret
NODE_ENV=development
TMDB_API_KEY=eyJhbGciOiJIUzI1NiJ9.eyJhdWQiOiJmMjYyMjBjYTg3MzMzNmMzY2EzZmFkNTA3ZGMzOTI2ZiIsIm5iZiI6MTc0MjI5MDg5OC45NTYsInN1YiI6IjY3ZDkzZmQyNmE3Yjk4MDQzNmM2YWVlMiIsInNjb3BlcyI6WyJhcGlfcmVhZCJdLCJ2ZXJzaW9uIjoxfQ.hY0vPu7BxejuArLMyvPxfbGxce8zP2Tcy1FrxGHtCEk

2. Run the App Locally

Install dependencies:
npm install

Build the project:
npm run build

Start the application:
npm run dev

Thank You
