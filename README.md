# JSL Portfolio Piece: Kanban App

## Overview

This Kanban app is my portfolio piece showcasing modular JavaScript, responsive UI design, and deployment workflows. It provides a clear, intuitive interface for managing tasks, with features like sidebar toggling, dark/light themes, and persistent storage. The app is deployed to Netlify with a custom URL, making it easy to share with recruiters and collaborators.

- Presentation: Loom Recording[(https://www.loom.com/share/568177c84c1149b1bd583a409fde5c7a)]

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

## WHAT to Submit

- **JSLPP GitHub Repo**: Your JSLPP GitHub repository
- Netlify[(https://unamat25572-unathi-matiwane-jspp.netlify.app/)]
  - You can find the link record for my presentation [Loom][(https://www.loom.com/share/d3eb324867264f9488fcb9a91d2794c0)],
  - Make sure your recorded presentation link is publicly accessible and is included in your GitHub README.

## Before You Begin

**Check out the [Figma Reference File](https://www.figma.com/design/y7bFCUYL5ZHfPeojACBXg2/Challenges-%7C-JSL?node-id=6033-11092&t=XbQhBWPYxXDAqp3x-1) and the project user stories in your student dashboard** before you start building.

## Key Objectives

- Deployment & Hosting: Prepared and deployed to Netlify with custom URL.

- Data Persistence: Tasks stored and loaded from local storage.

- Task Editing & Deletion: Full CRUD functionality with modal.

- Sidebar Interaction: Toggleable sidebar with emoji eyes animation.

- Theme Toggle: Dark/Light mode switch in both desktop and mobile views.

- Code Quality: Modular structure, descriptive names, documented functions.

✅ Expected Outcome

- A fully functional Kanban app that:

- Dynamically fetches and displays tasks.

- Supports task editing, deletion, and persistent storage.

- Has a responsive, mobile‑friendly sidebar with theme toggle.

- Is deployed to Netlify with a custom, readable URL.

- Uses modular, well‑documented code that is easy to maintain and scale.

### Task Editing & Deletion

- Allow users to **edit task details** (title, description, status) in a modal. Upon saving, the task should reflect the updated data on the board and in local storage.
- Implement a **delete button** within the modal to allow users to remove tasks. A confirmation message should appear before deleting a task, and if confirmed, the task will be removed from both the task board and local storage.

### Sidebar Interaction

- Implement a **sidebar** that contains all required elements as shown in the Figma design.
- Allow the sidebar to be **toggleable**, so users can hide or show it based on their preferences.
- Provide a mobile version of the sidebar that can be **accessed from the app logo**, and ensure it matches the design and functionality of the desktop sidebar.

### Mobile Sidebar (Menu) Functionality

- On mobile, the sidebar should function as a **menu** accessible from the top of the screen.
- Include the **theme toggle** switch in the mobile menu and ensure all features match the desktop sidebar, as shown in the Figma design.
- Ensure that the mobile menu is **closable**, allowing users to dismiss it for an unobstructed view of the tasks.

### Theme Toggle (Dark/Light Mode)

- Include a **theme toggle switch** to allow users to switch between dark mode and light mode.
- The toggle should be functional in both the **desktop sidebar** and the **mobile menu** for consistent theme switching across devices.
- Ensure all elements of the **Kanban board** are styled appropriately in dark mode, ensuring good contrast and readability.

### Stretch Goal: Adding Priority (Optional)

Enhance your task management application by introducing a **priority system**. Users should be able to select a priority level—**High, Medium, or Low**—when creating or editing tasks. The priority should be:

- **Visually displayed** on each task card as shown on the Figma design to clearly communicate urgency.
- **Saved to local storage** to ensure persistence across page reloads.
- **Editable** so users can adjust a task's importance as needed.
- **Reflected immediately** on the UI upon changes.
- **Sorted automatically** within each status column by priority (High → Medium → Low), with **High-priority tasks appearing at the top**.
- **Persistently ordered**, maintaining correct priority display after refreshing the page.

## Code Quality & Maintainability

- **Break the code into separate modules** with clear responsibilities (e.g., local storage handling, task rendering, modal management) to improve maintainability and scalability.
- Use **descriptive, meaningful variable and function names** to make the code easy to understand.
- **Document every major function and module** using **JSDoc comments** to explain the purpose, parameters, and return values of each part of the code.

## Expected Outcome

A fully functional Kanban app that:

- Dynamically fetches and displays tasks.
- Supports task editing, deletion, and persistent storage through local storage.
- Has a responsive, mobile-friendly sidebar with a theme toggle switch.
- App deployed to **Netlify** with a custom, readable URL.
- Uses modular, well-documented code that is easy to maintain and scale.
