# JSL Portfolio Piece: Kanban App

## Overview

This Kanban app is my portfolio piece showcasing modular JavaScript, responsive UI design, and deployment workflows. It provides a clear, intuitive interface for managing tasks, with features like sidebar toggling, dark/light themes, and persistent storage. The app is deployed to Netlify with a custom URL, making it easy to share with recruiters and collaborators.

- Presentation: Loom Recording[(https://www.loom.com/share/568177c84c1149b1bd583a409fde5c7a)]

- Netlify [(https://app.netlify.com/projects/jslppredo23/overview)]

- Design Reference:[Figma Reference File][(https://www.figma.com/design/y7bFCUYL5ZHfPeojACBXg2/Challenges-%7C-JSL?node-id=6033-11092&t=XbQhBWPYxXDAqp3x-1)]

## Features

## Data Handling##

- Loads initial tasks from local storage (with optional API integration).
- Persists all changes automatically in browser local storage.

## Task Management##

- Add new tasks with validation.
- Edit existing tasks directly within the app.
- Delete tasks when no longer needed.
- Task counts update dynamically per column.

## User Interface\*\*

- Sidebar functionality:
- Open and close the sidebar seamlessly on both desktop and mobile views.
- Mobile sidebar accessible from the app logo.
- Emoji eyes animation when hiding sidebar.
- Theme customization:
  - Toggle between dark and light mode for personalized viewing.
- Functional in both desktop sidebar and mobile menu.
- All board elements styled for readability in dark mode.

🛠️ ##Code Structure ##

Modular code split into:

- tasks.js → Task CRUD + localStorage

- sidebar.js → Sidebar toggle

- theme.js → Dark/Light mode

- main.js → Initialization

📱 Mobile Sidebar (Menu)

- Functions as a collapsible menu accessible from the top of the screen.

- Includes theme toggle switch for consistent behavior across devices.

- Closable for unobstructed task viewing.

🌗 ## Theme Toggle##

- Switch between dark mode and light mode instantly.

- Button text updates dynamically (🌑 Dark Mode ↔ ☀️ Light Mode).

- Styles applied across all elements for contrast and readability.

- Optional persistence via localStorage.

🎯 Stretch Goal: Task Priority

- Add High / Medium / Low priority levels.

- Display priority visually on task cards.

- Save priority to localStorage.

- Sort tasks automatically by priority within each column.

📌 Key Objectives

- Deployment & Hosting: Deployed to Netlify with custom URL.

- Data Persistence: Tasks stored and loaded from localStorage.

- Task Editing & Deletion: Full CRUD functionality with modal.

- Sidebar Interaction: Toggleable sidebar with emoji animation.

- Theme Toggle: Dark/Light mode switch across desktop and mobile.

- Code Quality: Modular, documented, recruiter‑friendly.

✅ Expected Outcome

- A fully functional Kanban app that:

- Dynamically fetches and displays tasks.

- Supports task editing, deletion, and persistent storage.

- Has a responsive, mobile‑friendly sidebar with theme toggle.

- Is deployed to Netlify with a custom, readable URL.

- Uses modular, well‑documented code that is easy to maintain and scale.
