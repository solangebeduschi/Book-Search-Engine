# Book-Search-Engine

## Description
This application is a fully functioning Google Books API search engine built using the MERN stack (MongoDB, Express.js, React, Node.js). The app has been refactored to use GraphQL with Apollo Server instead of a RESTful API. Users can search for books, create accounts, save books to their profiles, and view or delete saved books. The app is deployed using Render and MongoDB Atlas.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/solangebeduschi/Book-Search-Engine
   ```

2. Navigate to the project directory:
   ```bash
   cd book-search-engine
   ```

3. Install dependencies for both the client and server:
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory with the following variables:
   ```env
   MONGODB_URI=<your-mongodb-atlas-uri>
   JWT_SECRET=<your-jwt-secret>
   ```

5. Start the development servers:
   ```bash
   npm run develop
   ```

## Usage

1. Open the app in your browser at `http://localhost:3000` if running locally.
2. Use the search bar to look up books by title or keywords.
3. Sign up or log in to save books to your profile.
4. Navigate to the "Saved Books" page to view or manage your saved books.

## Features

- Search for books using the Google Books API.
- View book details including title, author, description, and links.
- User authentication with JWT.
- Save and manage a personalized list of books.
- Refactored back end to use GraphQL API.

## Technologies Used

- **Front End**: React, Apollo Client
- **Back End**: Node.js, Express.js, Apollo Server, MongoDB
- **Database**: MongoDB Atlas
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Render, MongoDB Atlas

## Deployment

The application is deployed and can be accessed at:
[Live Demo]https://book-search-engine-qqhn.onrender.com

## License

This project is licensed under the MIT License. See the LICENSE file for details.
