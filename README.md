<div align="right">
  <img src="https://img.shields.io/badge/Completion-100%25-blue.svg" />
  <a href="#" alt="License"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a>
</div>

<h1 align="center">Welcome to YelpCamp 👋</h1>

This is a hands-on project from the Udemy course - [The Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/) by Colt Steele.

### 🏠 [Click here to see the project in production](https://yelpcamp2020.glitch.me/)

## What I Learnt
-	Introduction to [Express.js](https://expressjs.com/)
-	Introduction to [MongoDB](https://www.mongodb.com/) database design
-	Deploying the app to [Glitch](https://glitch.com/) and Database to [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/)
- Introduction to Model-View-Controller and Monolithic architectures
- Authentication and authorization using [Passport.js](https://www.passportjs.org/)
- Directory structure good practices
- Responsive web design using [Bootstrap](https://getbootstrap.com/)
- Configuring [Flash messages](https://www.npmjs.com/package/connect-flash) following user interactions
- Experimented with [Paper.js](http://paperjs.org/) to implement a custom 404 page.
- RESTful routing (all endpoints listed below)

```
-------------------------------------------------------------------------
App Routes
-------------------------------------------------------------------------
[Method]  [Route]
GET       /                       Landing page
GET       /login                  User login page
POST      /login                  Authenticate existing user
GET       /signup                 User sign up page
POST      /signup                 Register new user
GET       /logout                 Logout and redirect to /posts
GET       /*                      404 page

-------------------------------------------------------------------------
Post Routes
-------------------------------------------------------------------------
[Method]  [Route]
GET       /posts                  Show all posts
POST      /posts                  Submit new post
GET       /posts/new              Add new post form
GET       /posts/:id              Show a single post
PUT       /posts/:id              Update a post
DELETE    /posts/:id              Delete a post
GET       /posts/:id/edit         Edit post page

-------------------------------------------------------------------------
Comment Routes
-------------------------------------------------------------------------
[Method]  [Route]
POST      /posts/:id/comments               Create a new comment
PATCH     /posts/:id/comments/:comment_id   Update a comment
DELETE    /posts/:id/comments/:comment_id   Delete a comment
```

## Getting Started

Follow the steps below to run this project locally. Remember to create a `.env` file in the root directory.

1. Clone this repository.

```bash
# Clone repository
$ git clone https://github.com/mitulagrofficial/YelpCamp2020.git && cd YelpCamp2020
```

2. Install dependencies via NPM or Yarn

```bash
# Install dependencies via npm
$ npm install

# Install dependencies via yarn
$ yarn install
```

3. Run the server and open a browser to visit [http://localhost:3000/](http://localhost:3000/).

```bash
# Run server
$ npm start
```

# Thank you very much!

If you have any suggestions that would make this better, feel free to fork the repo and create a pull request. Much appreciated!
