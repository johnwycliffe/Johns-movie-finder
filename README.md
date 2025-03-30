             
react.js appwrite tailwindcss
A Movie finding Application
Build this project step by step with our detailed tutorial on JavaScript Mastery YouTube. Join the JSM family!
📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
⚙️ Tech Stack

🔋 Features
👉 Browse All Movies: Explore a wide range of movies available on the platform.

👉 Search Movies: Easily search for specific movies using a search function.

👉 Trending Movies Algorithm: Displays trending movies based on a dynamic algorithm.

👉 Modern UI/UX: A sleek and user-friendly interface designed for a great experience.

👉 Responsiveness: Fully responsive design that works seamlessly across devices.

and many more, including code architecture and reusability

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/johnwycliffe/Johns-movie-finder
cd Johns-movie-finder
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

VITE_IMDB_API_KEY=

VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
Replace the placeholder values with your actual TheMovieDatabase API and Appwrite credentials. You can obtain these credentials by signing up on the TheMovieDatabase and creating a new project on the Appwrite

Running the Project

npm run dev
Open http://localhost:5173 in your browser to view the project.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
