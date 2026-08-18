Quora Posts

A simple Quora-like post management web application built as part of the Sigma Course by Apna College.

This project demonstrates the basics of building a web application using Node.js, Express.js, EJS, and CSS, along with CRUD operations for posts.

Features

View all posts

Create a new post

View a post in detail

Edit an existing post

Delete a post

Generate a unique ID for every post using UUID

Use EJS templates for dynamic HTML

Use HTTP method override for PATCH and DELETE requests

Basic CSS styling

Technologies Used

Node.js

Express.js

EJS

HTML

CSS

JavaScript

UUID

Method Override

Project Structure

Quora-Posts/
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
│   └── edit.ejs
│
├── public/
│   └── style.css
│
├── index.js
├── package.json
├── package-lock.json
└── README.md

CRUD Operations

Operation

Method

Route

Purpose

Create

POST

/posts

Create a new post

Read

GET

/posts

Display all posts

Read

GET

/posts/:id

Display a post in detail

Update

PATCH

/posts/:id

Edit a post

Delete

DELETE

/posts/:id

Delete a post

How It Works

The Express server uses EJS as the view engine and serves static CSS files from the public folder.

Posts are currently stored in an in-memory JavaScript array, so the data will reset whenever the server restarts.

Each post contains:

id

username

content

A unique ID is generated using the UUID package.

Installation & Setup

1. Clone the repository

git clone <your-github-repository-url>
cd Quora-Posts

2. Install dependencies

npm install

3. Start the server

node index.js

The application runs on:

http://localhost:8080/posts

Learning Outcomes

This project helped me practice:

Creating an Express.js server

Defining GET, POST, PATCH, and DELETE routes

Working with route parameters

Handling form data using express.urlencoded()

Rendering dynamic pages with EJS

Using method-override

Generating unique IDs with UUID

Organizing views and static files

Implementing basic CRUD functionality

Future Improvements

Add MongoDB for permanent data storage

Add user authentication

Add likes and comments

Improve UI/UX

Add validation and error handling

Deploy the application online

Course

Built while learning web development through the Sigma Course by Apna College.