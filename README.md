Savage Authentication Message Board

About the Project

Savage Authentication Message Board is a full-stack web application that allows users to create an account, log in, and interact with a message board.

This project demonstrates my understanding of user authentication, CRUD operations, backend development, and database integration.

I built this application using JavaScript, Node.js, Express.js, MongoDB, and EJS. I also implemented thumbs-up and thumbs-down functionality, allowing users to increase or decrease a message's score.

Tech Stack

Frontend

HTML5

CSS3

JavaScript

EJS (Embedded JavaScript Templates)

Bootstrap

Font Awesome

Backend

Node.js

Express.js

Passport.js

Database

MongoDB

Mongoose

Development Tools

Visual Studio Code

Git

GitHub

npm

Features

User Authentication

Users can create an account.

Registered users can log in and log out.

Authentication is handled using Passport.js.

Protected routes prevent unauthenticated users from accessing the profile page.

Message Board

Users can create and post messages.

Messages are saved in MongoDB.

Messages remain available after refreshing the page.

Users can view messages on the message board.

Thumbs-Up and Thumbs-Down

Users can click thumbs-up to increase a message's score.

Users can click thumbs-down to decrease a message's score.

Both buttons update one shared number.

Updated scores are saved in MongoDB.

CRUD Operations

This application demonstrates CRUD functionality:

Operation

Description

HTTP Method

Create

Add a new message

POST

Read

Display saved messages

GET

Update

Increase or decrease a message's score

PUT

Delete

Remove a message

DELETE

How It Works

A user signs up or logs into the application.

After authentication, the user is redirected to the message board.

The user can create a message.

Express.js processes the request and saves the message in MongoDB.

EJS displays the saved messages.

JavaScript handles thumbs-up and thumbs-down interactions.

The backend updates the message's score in MongoDB.

Users can delete messages from the board.<img width="1408" height="756" alt="Screenshot 2026-10-26 at 8 35 23 PM" src="https://github.com/user-attachments/assets/ae96524c-d1c7-46ab-8094-96b23bb1400d" />

