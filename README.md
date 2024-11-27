# Post Management Application

## Table of Contents

- [Overview](#overview)
- [Technologies](#technologies)
- [Features](#features)
- [File Structure](#file-structure)
- [Setup](#setup)
- [Contributions](#contributions)
- [License](#license)

## Overview

This project is a simple post management application that allows users to create, update, and delete posts. It fetches data from the JSONPlaceholder API and provides a dynamic interface for post management using Vue.js. The project leverages modern web development practices with Vue 3, providing a responsive and interactive experience.

## Technologies

- **Vue 3**: A JavaScript framework used for building the user interface.
- **HTML5**: Used to create the semantic structure of the webpage.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **JavaScript (ES6+)**: For handling the logic of creating, updating, and deleting posts.
- **Fetch API**: Used for making requests to the JSONPlaceholder API.
- **Vite**: A fast development environment for modern web projects.
- **pnpm**: A fast, disk space-efficient package manager.

## Features

- **Post Management**: Allows users to create, update, and delete posts.
- **Dynamic Updates**: Post list updates in real-time after performing any action.
- **Responsive Design**: The application is responsive and adapts to different screen sizes.
- **Error Handling**: Provides error messages when operations fail.
- **Fast Development**: Set up with Vite for quick builds and live reloading.
- **API Integration**: Uses the JSONPlaceholder API to simulate real-world data handling.

## File Structure

```
public/                         # Public static files
src/                            # Source files
├── assets/                     # Images and other assets
├── components/                 # Vue components
│   ├── PostForm.vue            # Form to create and update posts
│   └── PostList.vue            # Displays the list of posts
├── scripts/                    # JavaScript logic files
│   └── postLogic.js            # Contains logic for fetching and managing posts
├── views/                      # Views for different routes
│   └── HomeView.vue            # Main view for the homepage
├── App.vue                     # Main Vue component
├── main.js                     # Main entry point for the app
└── style.css                   # Global styles
index.html                      # Main HTML file
tailwind.config.js              # Tailwind CSS configuration
postcss.config.js               # PostCSS configuration
package.json                    # Project dependencies
vite.config.js                  # Vite configuration
```

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sangariusss/post-management-app.git
   cd post-management-app
   ```

2. **Install dependencies (using pnpm)**:
   ```bash
   pnpm install
   ```

3. **Run the development server**:
   ```bash
   pnpm dev
   ```

4. **Build the project**:
   ```bash
   pnpm build
   ```

5. **Preview the build**:
   ```bash
   pnpm preview
   ```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

## Contributions

Contributions are welcome! If you'd like to add features or fix issues, please open a pull request or file an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
