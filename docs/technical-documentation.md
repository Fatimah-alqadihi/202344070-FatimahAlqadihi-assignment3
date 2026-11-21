

# Technical Documentation

## Project Overview

This portfolio website was developed as part of SWE Assignment 3. The application showcases personal projects and demonstrates the use of modern web development concepts including API integration, state management, responsive design, and interactive user features.

---

## Technologies Used

- **HTML5** for website structure
- **CSS3** for styling and responsive layout
- **JavaScript (ES6)** for interactivity and application logic
- **GitHub API** for dynamically displaying repository information
- **Local Storage** for saving user preferences
- **GitHub Pages** for deployment

---

## Features Implemented

### 1. Dark Mode (State Management)

The website includes a dark mode toggle button.

Functionality:
- Users can switch between light and dark themes.
- Theme preference is saved using `localStorage`.
- The saved theme is automatically loaded when the website is reopened.

Implementation:
- Uses `classList.toggle()` to switch themes.
- Stores the selected theme in browser storage.
- Updates the button text according to the active mode.

---

### 2. Project Details Toggle

Each project card includes a button that allows users to show or hide additional project information.

Functionality:
- Displays project descriptions and images only when requested.
- Improves content organization and readability.

Implementation:
- Uses JavaScript event listeners.
- Dynamically changes button text between "Show Details" and "Hide Details".

---

### 3. GitHub API Integration

The website retrieves repository information from GitHub using the public GitHub API.

Functionality:
- Displays repositories dynamically.
- Keeps portfolio content up to date.
- Includes error handling if the API request fails.

Implementation:
- Uses the Fetch API.
- Processes JSON responses.
- Displays a user-friendly error message when needed.

---

### 4. Project Filtering

Visitors can filter projects based on project categories.

Functionality:
- Allows users to focus on specific project types.
- Updates visible projects immediately.

Implementation:
- Uses custom HTML data attributes (`data-category`).
- JavaScript checks selected filter values and updates the display.

---

### 5. Project Sorting

Projects can be sorted by year.

Functionality:
- Sorts projects from newest to oldest or oldest to newest.
- Reorders project cards dynamically.

Implementation:
- Uses `data-year` attributes.
- JavaScript sorting functions reorder project elements in the DOM.

---

## Responsive Design

The website is designed to work across different screen sizes.

Techniques Used:
- Flexible layouts using CSS.
- Responsive images.
- Media queries for smaller screens.
- Navigation adjustments for mobile devices.

This ensures a consistent experience on desktops, tablets, and smartphones.

---

## Performance Optimizations

Several optimizations were applied to improve performance:

- Compressed and resized project images.
- Reused CSS classes to reduce duplicate code.
- Removed unused code and assets.
- Minimized DOM operations where possible.

---

## Code Organization

Project structure: