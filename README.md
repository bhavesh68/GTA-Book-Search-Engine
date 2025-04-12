# GTA-Book-Search-Engine

## Description

This is refactored Google Books API search engine built with a RESTful API, that is now a GraphQL API built with Apollo Server.

## Table of Contents

- [Features](#Features)
- [Usage](#usage)
- [Deloyment](#deployment)
- [License](#license)

## Features

🔍 Book Search
Search for books using the Google Books API based on a keyword or phrase.

📖 View Book Details
See detailed information for each book, including title, authors, description, cover image, and a link to view the book on Google Books.

🧾 User Authentication
Sign up or log in to access personalized features using JWT-based authentication.

💾 Save Favorite Books
Logged-in users can save books to their personal list with a single click.

📚 View Saved Books
Logged-in users can view all books they’ve saved on a dedicated "My Saved Books" page.

❌ Remove Saved Books
Users can remove books from their saved list with one click.

🔄 Apollo Client Integration
Front-end communicates with the back-end using GraphQL queries and mutations through Apollo Client.

🧠 Apollo Server with GraphQL
Backend is powered by Apollo Server with full GraphQL implementation, replacing traditional REST APIs.

🔐 GraphQL Authentication Middleware
Middleware checks for valid JWT tokens in GraphQL context to protect secure routes and data.

🌐 Deployed on Render
Full-stack application deployed and live using Render and MongoDB Atlas.

🧩 MERN Stack
Built using MongoDB, Express.js, React, and Node.js.
  
## Usage

- Visit the Deployed App
  Navigate to the live application deployed on Render:
  👉 Deployed Application Link (Replace with your actual URL)

- Search for Books

  On the homepage, enter a keyword or book title in the search bar and click Submit.

  View a list of books with their title, author(s), description, cover image, and a link to the Google Books page.

- Create an Account or Log In

  Click on Login/Signup in the navigation menu.

  Use the modal to either sign up (username, email, password) or log in (email, password).

  Once logged in, the navigation menu will show additional options.

- Save Books

  Logged-in users will see a Save This Book! button under each search result.

  Click it to add that book to your personal saved list.

  Already saved books will be marked as Book Already Saved.

- View Saved Books

  Click on Saved Books in the navigation menu to view your saved list.

  Each saved book includes the same details as search results, plus a Delete button.

- Remove Books from Your List

  On the Saved Books page, click the Delete button on any book you'd like to remove from your saved list.

- Log Out

  Click Logout in the navigation menu to end your session.

## Deloyment

https://gta-book-search-engine.onrender.com

## License

MIT

  
