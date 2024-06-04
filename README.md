# Book Search Engine Starter Code
# GraphQL Book Search Engine

This project is a book search engine refactored to use GraphQL and Apollo Server. The application allows users to search for books using the Google Books API, save their favorite books to their account, and manage their saved books. It is built with the MERN stack (MongoDB, Express.js, React, Node.js) and utilizes Apollo Server for GraphQL queries and mutations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [License](#license)

## Installation

To install and run the application locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MartinVF12/graphql-book-search.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd graphql-book-search
    ```

3. **Install server dependencies**:
    ```bash
    cd server
    npm install
    ```

4. **Install client dependencies**:
    ```bash
    cd ../client
    npm install
    ```

5. **Create a `.env` file in the `server` directory and add your environment variables**:
    ```
    MONGODB_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>
    ```

6. **Build the client**:
    ```bash
    npm run build
    ```

7. **Start the server**:
    ```bash
    cd ../server
    npm start
    ```

8. **Open your browser and navigate to** `http://localhost:3001`.

## Usage

Once the application is running, you can:

- Search for books by entering a search term in the search bar.
- View search results with book details such as title, author, description, and a link to the book on Google Books.
- Save books to your account if you are logged in.
- View your saved books by navigating to the "See Your Books" page.
- Remove books from your saved list.

## Features

- User authentication with JWT.
- Search for books using the Google Books API.
- Save favorite books to your account.
- Manage saved books (view and remove).
- GraphQL API with Apollo Server.

## Technologies

- **MongoDB**: NoSQL database for storing user data and saved books.
- **Express.js**: Web framework for Node.js.
- **React**: Front-end library for building user interfaces.
- **Node.js**: JavaScript runtime for building the back-end server.
- **Apollo Server**: GraphQL server for handling queries and mutations.
- **Google Books API**: External API for fetching book data.

## License

This project is licensed under the MIT License.
