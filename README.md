# 🧠 Node Quiz App

A basic Quiz Application built using **Node.js**, **Express**, and **EJS Template Engine**.

This project allows users to take a quiz and see their results. It uses server-side rendering with EJS and handles routing using Express.

---

## ✅ Prerequisites

Before you run the project, make sure you have:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm (Node Package Manager)

---

## 🚀 How to Run This Project

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/expertdeveloperit/node-quiz-app.git
cd node-quiz-app

2. Install Dependencies
Install all the required Node.js packages using:

npm install

3. Start the Server
Run the server using the following command:
npm start

By default, the app will be available at:
👉 http://localhost:3000

4. Project Structure

node-quiz-app/
├── public/             # Static files (CSS, images, etc.)
├── routes/             # Express routes
│   └── index.js        # Main application route
├── views/              # EJS templates for rendering HTML pages
│   ├── index.ejs       # Home page
│   ├── quiz.ejs        # Quiz page
│   └── result.ejs      # Result page
├── app.js              # Main application entry point
├── package.json        # Project metadata and dependencies
└── README.md           # This file

5. What Happens in Each File
app.js: Initializes Express, sets view engine, serves static files, and uses routes.

routes/index.js: Handles routing logic for showing the quiz and processing results.

views/: Contains EJS templates to render pages.

public/: Holds static assets like CSS and images.

6. Notes
This app uses EJS for templating. Make sure you are familiar with EJS syntax.

All quiz questions and logic are handled server-side using Express.

You can modify the quiz questions inside the routes/index.js file.
