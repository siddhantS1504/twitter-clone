# Twitter Clone - MERN Stack

![Twitter Clone](twitter-clone.png)

This is a simple Twitter clone built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to post tweets, follow other users, and view a timeline of tweets from the users they follow.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication.
- Post tweets and view tweets from users you follow.
- Follow/unfollow other users.
- Like and retweet tweets.
- User profiles with tweet history.
- Real-time updates using WebSockets (Socket.io).

## Technologies Used

- **MongoDB**: A NoSQL database for storing user data, tweets, and user relationships.
- **Express.js**: A Node.js web application framework for building the server.
- **React**: A JavaScript library for building the user interface.
- **Node.js**: A JavaScript runtime environment for building the server-side application.
- **Socket.io**: A library for enabling real-time, bidirectional communication between clients and the server.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.
- **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
- **Redux**: For managing application state.
- **Material-UI**: A popular React UI framework for designing responsive and attractive user interfaces.

API Endpoints
POST /api/auth/register: Register a new user.
POST /api/auth/login: Login and generate a JWT token.
GET /api/tweets: Get all tweets.
POST /api/tweets: Create a new tweet.
GET /api/tweets/:id: Get a specific tweet by ID.
PUT /api/tweets/:id: Update a tweet by ID.
DELETE /api/tweets/:id: Delete a tweet by ID.
POST /api/users/follow/:id: Follow a user.
POST /api/users/unfollow/:id: Unfollow a user.
GET /api/users/:username: Get a user's profile.
