# Maddy and Lily's Cross Country Road Trip Website

A multi-page website documenting our cross-country road trip from California to Vermont!

---

## Project Summary

- **Homepage** — intro to the trip, a list of all our stops, and a drive time table
- **Route** — an interactive map showing every stop along the way
- **West Coast** — photos and stories from California, Arizona, and Colorado
- **Mid States** — highlights from Kansas and Chicago
- **East Coast** — the final stretch through Pittsburgh, Connecticut, and Vermont
- **Trip Planning Notes** — visitors can leave trip planning notes saved and displayed

---

## List of Implemented Features

## HTML

- Uses semantic elements like `<header>`, `<nav>`, `<footer>`, `<section>`, and `<article>` throughout every page
- 6 separate HTML pages, each with a consistent structure

## CSS

- Styled with external CSS
- Flexbox used for image layouts so they wrap nicely on smaller screens
- Media queries make the site responsive on mobile
- Each page has its own color theme while keeping the same fonts and general vibe

## JavaScript

- Interactive map on the Route page built with Leaflet.js
- Guestbook form saves comments to localStorage and displays them dynamically
- DOM manipulation used to build and show comment entries without reloading the page
- Form validation checks that required fields are filled before submitting
- Uses arrays, objects, loops, and conditionals throughout

## Data

- Trip planning notes comments are stored in `localStorage` as JSON so they stick around between visits

## Navigation

- Every page has the same nav bar linking to all 6 pages

## Deployment

- Deployed via GitHub Pages

---

## Team Members and Roles 

- A lot of the website was completed before this project. We built on it from the first project to
  make it more interactive using JS. Here's what we added and how we split it up after finishing
  the first half (Basic HTML and CSS).

## Maddy Smith 

- Added an interactive map feature using the Leaflet API, including functions and images.
  The map has a marker on each stop, and clicking a marker shows the stop name. Additionally
  updated all files to GitHub and created the README.md. 

## Lily Verna

- Created an HTML form with JS validation that takes trip planning notes from site visitors and posts them
  to the site. Also added a CSS file for consistent flexbox styling throughout the website. 
