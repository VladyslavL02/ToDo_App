# ToDo App

A task manager for creating and organizing todos. Built with React and TypeScript, the app lets you add, edit, complete, filter, and delete tasks, with changes saved through the designated API.

## Live Preview

[ToDo App Demo](https://vladyslavl02.github.io/ToDo_App/)

## Technologies Used

**Core**

- React 18 – Component-based interface and interactive task management
- TypeScript – Typed application logic and todo data
- Vite – Development server and production bundling
- SCSS – Stylesheet preprocessing and application styling

**UI & Services**

- Bulma – Base styles and UI utilities
- Font Awesome – Icon font

**Tooling**

- ESLint, Stylelint, and Prettier – Code quality and formatting

**Deployment & Hosting**

- GitHub Pages – Public hosting and live preview deployment

## Getting Started

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/VladyslavL02/ToDo_App.git
   cd ToDo_App
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set your API user ID in `src/api/todos.ts` by updating `USER_ID`.

4. Start the development server:

   ```bash
   npm start
   ```

## Available Scripts

- `npm start` – Start the Vite development server
- `npm run build` – Create a production build
- `npm run lint-js` – Lint JavaScript and TypeScript files
- `npm run lint-css` – Lint SCSS files
- `npm run lint` – Format and lint the source files
- `npm run deploy` – Build and deploy the app to GitHub Pages

## Features

- **Create todos:** Add tasks with a title and see them appear in the list.
- **Edit todos:** Double-click a task title to edit it; submit the change or press Escape to cancel.
- **Complete tasks:** Mark individual todos complete or active, or toggle all tasks at once.
- **Filter the list:** View all, active, or completed todos.
- **Track remaining tasks:** See the number of active items in the list footer.
- **Delete todos:** Remove individual tasks or clear all completed tasks.
- **API-backed storage:** Load and save todo changes using the Mate Academy Students API.
- **Loading and error feedback:** Show task loading states and notifications when API requests fail.
