# Devixo Solutions – Interactive Business Website

This is a complete, professional, modern, and fully responsive multi-page business website for "Devixo Solutions" built entirely with HTML5, CSS3, and Vanilla JavaScript.

## Technologies Used
- HTML5
- CSS3 (Vanilla)
- Vanilla JavaScript (No frameworks/libraries)

## Features Implemented
1. **Responsive Navigation Menu:** Mobile hamburger menu with smooth toggle.
2. **Dark/Light Mode:** Toggle switches theme globally and persists preference in `localStorage`.
3. **Typing Animation:** Hero section features dynamic Vanilla JS typing effect.
4. **Animated Counters:** Number counters animate when scrolled into view.
5. **Portfolio Filtering:** Filter projects by category seamlessly.
6. **Image Slider:** Fully functional image carousel with dots, navigation arrows, and auto-play using Vanilla JS.
7. **FAQ Accordion:** Interactive frequently asked questions section where only one opens at a time.
8. **Contact Form Validation:** Validates required fields, email format, and message length with success/error handling.
9. **Scroll-to-Top Button:** Appears upon scrolling and smoothly takes the user to the top.

## Project Structure
```text
devixo-solutions/
│
├── index.html        # Home Page
├── about.html        # About Page
├── services.html     # Services Page
├── portfolio.html    # Portfolio Page
├── contact.html      # Contact Page (with form & FAQ)
│
├── css/
│   └── style.css     # Global Styles (Custom properties, themes, responsive rules)
│
├── js/
│   └── script.js     # Global Vanilla JavaScript logic
│
├── images/           # Contains placeholders/assets for the project
│   ├── hero/
│   ├── team/
│   ├── portfolio/
│   └── services/
│
└── README.md
```

## How to Run the Project Locally
1. Clone or download this repository.
2. Open the `devixo-solutions` folder.
3. Simply double-click `index.html` to open it in your default web browser. No server setup is required since it's just static HTML, CSS, and JS.
4. To test `localStorage` (for Dark Mode), some browsers prefer running on a local server (like Live Server extension in VSCode), but it works natively in most modern browsers.

## Deployment Guide

### GitHub Pages
1. Create a new repository on GitHub.
2. Push all the contents of the `devixo-solutions` folder to the repository.
3. Go to your repository **Settings** > **Pages**.
4. Under the "Source" drop-down, select the `main` or `master` branch and click Save.
5. In a few minutes, your site will be live at `https://<your-username>.github.io/<repository-name>/`.

### Netlify
1. Go to [Netlify](https://www.netlify.com/) and log in.
2. Go to your "Team Overview" or "Sites" tab.
3. Drag and drop the entire `devixo-solutions` folder onto the designated dropzone.
4. Netlify will deploy the site instantly and provide you with a live URL (e.g., `https://random-name-123.netlify.app`).
