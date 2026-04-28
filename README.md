# Deftones Fan Landing Page

## Description

This is a simple landing page for the band **Deftones**, created as a frontend practice project. The page promotes the band's identity, music catalog, upcoming tour events, and includes a personal carousel of favorite songs. It was built with pure HTML5, CSS3, and a small amount of JavaScript.

## Technologies Used

- **HTML5** - Semantic structure with tags like `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, `<table>`, and lists
- **CSS3** - Custom properties (variables), Flexbox, CSS Grid, keyframe animations, and media queries for responsive design
- **JavaScript** - DOM manipulation for the mobile menu and song carousel (no external libraries)
- **Google Fonts** - "Bebas Neue" for headings and "Roboto" for body text

## Project Structure

```
deftones-landing/
├── index.html          # Main HTML file with all sections
├── css/
│   └── styles.css      # All styles, animations, and responsive rules
├── js/
│   └── main.js         # Carousel logic and mobile menu toggle
├── images/             # Album cover images (user provided)
│   ├── adrenaline.jpg
│   ├── around-the-fur.jpg
│   ├── white-pony.jpg
│   ├── deftones.jpg
│   ├── saturday-night-wrist.jpg
│   ├── diamond-eyes.jpg
│   ├── koi-no-yokan.jpg
│   ├── gore.jpg
│   ├── ohms.jpg
│   └── private-music.jpg
└── README.md           # This file
```

## How to Run Locally

1. Download or clone the project folder to your computer.
2. Make sure all files keep the folder structure shown above.
3. Add the album cover images to the `images/` folder (optional - the page works without them).
4. Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
5. No server or build process is required - it runs entirely in the browser.

## Features

- Fixed header navigation with smooth scrolling
- Hero section with CSS animated background
- Events section with semantic list and HTML table
- About section with band info and member lists
- Discography grid showing all 10 studio albums
- Interactive carousel with favorite songs and auto-play
- Embedded YouTube videos in responsive wrappers
- Mobile hamburger menu
- Simple scroll reveal animations

## Notes

- This is a fan-made page for educational purposes, not the official Deftones website.
- The album cover images should be named exactly as listed in the structure above so the HTML finds them automatically.
