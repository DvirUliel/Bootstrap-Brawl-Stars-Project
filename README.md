# Brawl Stars Project

## Project Overview

This project is a responsive recreation of a Brawl Stars-themed website. It showcases multiple sections, including news, videos, and a download area for the game. The project uses HTML, CSS, and Bootstrap to create a clean and flexible layout that adapts to different screen sizes.

## Features

1. **Responsive Navigation Bar:**
   - The navbar is implemented using Bootstrap's `navbar` component.
   - It collapses into a hamburger menu on smaller screens and provides smooth navigation across different sections.

2. **Dynamic Media Content:**
   - The page integrates multiple media elements such as videos and images.
   - Bootstrap's responsive utilities ensure that the media resizes appropriately for various screen sizes.

3. **Cards Layout:**
   - News articles are displayed in a card layout, which scales responsively for mobile and desktop views.
   - Bootstrap's grid system is used to organize the cards in rows and columns.

4. **Responsive Images:**
   - Images are displayed in a way that ensures they do not overflow the page layout, using Bootstrap's `img-fluid` class for responsiveness.
   - Custom CSS is applied to ensure a consistent look, with contained and well-positioned images on all devices.

5. **Responsive Videos:**
   - Embedded YouTube videos are displayed in a responsive manner using Bootstrap’s `ratio` utility, ensuring that they adjust proportionally on various screen sizes.

6. **Smooth Scrolling:**
   - The page uses CSS smooth scrolling for a better user experience when navigating between sections.

## Technologies Used

- **HTML5:** The structure of the page.
- **CSS3:** Custom styles are written for the layout and visual design of the website.
- **Bootstrap 5:** The project leverages Bootstrap 5's grid system, cards, navigation bar, buttons, and responsive utilities to create a flexible, mobile-first layout.
- **JavaScript:** Bootstrap's JavaScript bundle is used for the navbar toggle functionality on smaller devices.

## Media Queries and Responsiveness

Bootstrap provides a mobile-first design strategy, meaning the layout is built to look great on small screens first, then scaled up for larger screens. Some important aspects of media matching:

- **Grid System:** Used to ensure a responsive design. The content in the `News` and `Videos` sections is arranged using Bootstrap's `row` and `col` classes, which adjust the layout depending on the screen size (e.g., `col-lg-6`, `col-md-6`, and `col-sm-12`).
  
- **Responsive Images:** The `img-fluid` class ensures that images resize based on the screen width, and custom CSS ensures that they remain well-aligned and visible across all devices.

- **Container Scaling:** The `.container` and `.container-fluid` classes are used to ensure that the layout spans appropriately across the screen while keeping the content centered.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/DvirUliel/Bootstrap-Brawl-Stars-Project.git
