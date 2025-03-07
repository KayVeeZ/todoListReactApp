# Vite React Tailwind To-Do List

A simple yet powerful To-Do List application built using **Vite**, **React**, and **Tailwind CSS**. This app allows users to add, edit, delete, and mark tasks as completed while storing them in **localStorage** for persistence.

## Features
- Add new tasks
- Edit existing tasks
- Delete tasks with confirmation
- Mark tasks as completed
- Filter to show/hide completed tasks
- Persist tasks using localStorage

## Technologies Used
- **React** (useState, useEffect)
- **Vite** (fast development server)
- **Tailwind CSS** (for styling)
- **UUID** (for unique task IDs)
- **React Icons** (for edit and delete icons)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KayVeeZ/todoListReactApp
   ```

2. Navigate to the project directory:
   ```bash
   cd todoListReactApp
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## File Structure
```
/todolist-vite-react
├── public
│   ├── index.html
├── src
│   ├── components
│   │   ├── Navbar.jsx
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
├── package.json
├── vite.config.js
└── README.md
```

## Usage
- Enter a task in the input field and click **Save**.
- Click the **Edit** button (✏️) to modify a task.
- Click the **Delete** button (🗑️) to remove a task (with confirmation).
- Mark tasks as completed using checkboxes.
- Toggle "Show Finished" to display/hide completed tasks.

## Screenshots
*(Add screenshots of the app here if needed)*

## Deployment
To deploy the app, build it with:
```bash
npm run build
```
Then, deploy the `dist/` folder to any static hosting provider like **Vercel**, **Netlify**, or **GitHub Pages**.

## License
This project is licensed under the MIT License.

## Author
*Kshitij Vashisth*

