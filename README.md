# Day 01 – Intro & Environment Setup

## Overview

This project is a basic backend setup created using **Node.js**, **npm**, and **Express.js**. The purpose of this task was to understand how to initialize a Node.js project, install Express, create a simple server, and set up a **Supabase project** for future database integration.

## What I Did

* Initialized a new Node.js project using npm
* Installed **Express.js**
* Created a basic Express server in `index.js`
* Configured the server to run on **localhost:3000**
* Displayed **"Hello World"** in the browser
* Created a **Supabase project** from the Supabase Dashboard for future database and backend integration

## Technologies Used

* **Node.js**
* **npm**
* **Express.js**
* **Supabase**

## Project Structure

```bash
project-folder/
│── node_modules/
│── package.json
│── package-lock.json
│── index.js
```

## Express Server Code

```javascript
const express = require("express");
const app = express();
const PORT = 3000;

app.get("/", (req, res) => {
  res.send("Hello World");
});

app.listen(PORT, () => {
  console.log(`Server running at http://localhost:${PORT}`);
});
```

## Supabase Setup

As part of this task, a **Supabase project** was also created using the **Supabase Dashboard**. The setup included:

* Logging in to Supabase
* Creating a new project
* Setting a project name
* Choosing a database password
* Selecting a region

This Supabase project will be used later for database-related tasks and backend integration.

## How to Run the Project

1. Open the project folder in VS Code
2. Open the terminal
3. Install dependencies:

```bash
npm install
```

4. Run the server:

```bash
node index.js
```

5. Open the browser and visit:

```bash
http://localhost:3000
```

## Output

When the server runs successfully, the browser displays:

```bash
Hello World
```

## Learning Outcome

This task helped me understand:

* how to set up a Node.js project
* how to install and use Express.js
* how to create and run a simple server
* how to create a Supabase project for future database integration
