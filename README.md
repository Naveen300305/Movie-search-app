🎬 Movie Search App

A simple and clean movie searching app built with React. It allows users to look up any movie using TMDB API and also displays a Trending Movies section powered by a small backend built with Appwrite.

This project was mainly created to practice APIs, React hooks, debouncing, and using Appwrite as a backend service.

🚀 Features
🔍 Movie Search

-Search for any movie in real time.

-Results load smoothly using a debounced search (prevents extra API calls).

-Each movie card shows title, poster, rating, and release info.

🔥 Trending Movies

-Displays the currently trending movies on the home page.

-Trending list is fetched from an Appwrite database where the movie details are stored.

-Appwrite acts as a mini backend to manage and update trending data.

🎨 Clean UI

-Simple, minimal UI for a distraction-free experience.

-Responsive design that works on desktop and mobile.

🛠️ Tech Stack

Frontend:

React (Vite)

Tailwind CSS

Backend / Storage:

Appwrite (Database + project functions)

API:

The Movie Database (TMDB)