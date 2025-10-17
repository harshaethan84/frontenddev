# CSCI 6313 - Final Examination Project

This project is a multi-page website created for the final examination of CSCI 6313. It demonstrates proficiency in front-end web development, API integration, form validation, and web accessibility standards.

**Author:** Pulapaka Harsha
**GitHub:** [harshaethan84](https://github.com/harshaethan84)

## Live Demo

**(Assuming your repo name is `CSCI6313-Final`)**
`https://harshaethan84.github.io/[your-repo-name]/`

**Note:** You must replace `[your-repo-name]` with the actual name of your repository.

---

## Features

This project is divided into several parts, each fulfilling a specific requirement from the exam.

### Part 01: Home Page (Profile)
* A fully responsive, dynamic home page (`index.html`) built with semantic HTML5 elements like `<header>`, `<main>`, `<nav>`, and `<footer>`.
* All styling is handled by a single external stylesheet (`style.css`), which uses CSS variables for a consistent (dark mode) theme.
* Features a responsive navigation bar with a dropdown menu and a mobile-friendly hamburger button.

### Part 02: Secure Form with Validation
* A secure form page (`form.html`) for changing a password and updating an address.
* Features robust client-side JavaScript validation.
* Prevents form submission if validation fails and displays clear success or error messages.
* Includes a complex regex pattern for the password field, requiring:
    * Minimum 9 characters
    * **Exactly** 2 uppercase letters
    * **Exactly** 1 special symbol

### Part 03: Google Maps API Integration
* A map explorer page (`map.html`) that integrates the Google Maps JavaScript API and the Google Places Library.
* Users can search for any nearby place (e.g., "restaurants," "hospitals").
* The page dynamically fetches and displays the **top 5 results** from the search.
* Results are displayed in a responsive grid of cards, matching the website's theme.
* Clicking on a result card pans the map and highlights the corresponding marker.

### Part 04: SEO & WCAG (Accessibility)
* **SEO (Search Engine Optimization):** The main page includes a meaningful `<title>` and `<meta name="description">` and uses a proper heading structure (a single `<h1>`).
* **WCAG (Accessibility):** The site is keyboard-accessible, including all navigation links and the dropdown menu (which is a `<button>`). All images have descriptive `alt` text, and the color scheme provides sufficient color contrast.

### Part 05: GitHub Hosting
* All project source code is hosted in this GitHub repository.
* The site is deployed and publicly accessible via GitHub Pages.

---

## Technologies Used

* **HTML5** (Semantic)
* **CSS3** (Flexbox, Grid, CSS Variables, Responsive Design)
* **JavaScript (ES6+)** (DOM Manipulation, Event Listeners, Client-Side Validation)
* **Google Maps JavaScript API**
* **Google Places API**

---

## Required Documentation Screenshots

*(As requested, this section is a placeholder for you to add your screenshots as required by the assignment.)*

### Part 01: Home Page (Desktop + Mobile)
*(Add your desktop screenshot here)*
*(Add your mobile screenshot here)*

### Part 02: Form Validation (Invalid + Valid)
*(Add screenshot of form with validation error here)*
*(Add screenshot of form with success message here)*

### Part 03: Map with 5 Results
*(Add screenshot of the map page with 5 card results here)*

### Part 04: Lighthouse/WAVE Report
*(Add screenshot of your Lighthouse or WAVE accessibility report here)*

### Part 05: Deployed Site (URL Bar Visible)
*(Add screenshot of your live GitHub Pages site with the URL bar visible)*
