# Applet Landing Page

## Project Overview

Applet is a simple, static landing page built with **HTML** and **CSS**, focusing on creating a visually appealing, semantically structured website that matches the design provided in Figma. This project emphasizes using proper HTML5 semantics, CSS grid/flexbox for layout, and pixel-perfect design implementation. No JavaScript is required.

## Learning Objectives

- **HTML fundamentals**: Learn how to build websites with semantic HTML tags.
- **CSS fundamentals**: Gain hands-on experience using CSS Grid & Flexbox for layout.
- **Web Development Tools**: Familiarize yourself with **Chrome DevTools** for debugging.

## Tech Stack

- **HTML5**: To structure the page semantically.
- **CSS3**: To style and create layouts using **Grid** and **Flexbox**.

## General Criteria

- **Vanilla HTML & CSS** only. No external libraries such as Bootstrap, Tailwind, or preprocessors like SCSS.
- **No JavaScript** is required.
- **Pixel-perfect design**: Ensure the website visually matches the Figma design closely.
- Cross-browser compatibility.
- **W3C HTML & CSS validator**: The project must pass validation.
- **Semantic HTML**: Use meaningful HTML tags to create a well-structured page.

## Structure

### Folder Structure

applet-landing/
│
├── assets/ # All images and icons
|── styles.css # Main stylesheet
│── normalize.css # Normalize CSS
├── index.html # Main landing page
├── projects.html # Projects page
└── README.md # Project information


### Pages

1. **Main Page (index.html)**:
   - **Header**: Fixed at the top with navigation links that scroll to corresponding sections (`About`, `FAQ`, `Contact Us`).
   - **Hero Section**: Showcases the main title and a button leading to the Projects page.
   - **Projects Section**: Layouts using Flexbox/Grid to display a list of projects.
   - **Footer**: Contains social media links and contact information.
   - **Buttons**: Interactivity using hover effects (no JS), links to various sections and pages.

2. **Projects Page (projects.html)**:
   - Displays additional details about each project in a grid format.

### Key Features

- **Fixed Header**: Ensures the navigation menu stays at the top of the page while scrolling.
- **Button Functionality**: Implement scroll functionality and links:
    - Clicking the "About" button scrolls to the About section.
    - Clicking the "Projects" button navigates to the Projects page.
    - The "FAQ" button scrolls to the FAQ section.
    - The "Contact Us" button scrolls to the contact section.
- **External Links**: Social media links open in a new tab.
- **Phone Number**: Clicking the phone number on mobile devices will initiate a call.
- **Email Address**: Clicking the email will open the default email client with the address pre-filled.

### Layout Details

- **Hero Section**: The hero section will be centered and display the title and a "Contact Us" button.
- **Projects Section**: A grid layout with project cards. Each card contains the project title and description.
- **FAQ Section**: A simple accordion-style list of frequently asked questions with answers.
- **Contact Section**: Will display contact details including a clickable phone number and email.

### Buttons & Links

- **Hover Effects**: Each button and link should have a hover effect (color change, underline, etc.).
- **Link Behavior**: All links should open in a new tab when navigating to external URLs.

## Development Guide

### 1. **Setting Up**:
   - Clone this repository:
     ```bash
     git clone https://github.com/your-username/applet-landing.git
     ```
   - Open `index.html` in your preferred browser.

### 2. **CSS & HTML Guidelines**:
   - Use **CSS Grid** and **Flexbox** for layout creation.
   - Make sure the design is **pixel-perfect** as per the Figma design (in terms of padding, margins, font sizes, etc.).
   - Ensure semantic HTML is used. For example:
     ```html
     <header>
       <nav>
         <ul>
           <li><a href="#about">About</a></li>
           <li><a href="#projects">Projects</a></li>
         </ul>
       </nav>
     </header>
     ```
### 3. **Theme Toggle (Optional)**:
   - The sun/moon icons for toggling between light and dark mode are already integrated in the navigation bar. Implement them using the provided icons.

### 4. **Validation**:
   - Use the **W3C Validator** to ensure your HTML and CSS pass the official validation tests.

## How to Validate

1. Open your project in a browser.
2. Right-click and select **Inspect** or press `Ctrl + Shift + I` to open DevTools.
3. Check for any issues or errors in the **Console** tab.
4. Use **W3C Validator** for HTML and CSS validation:
   - [HTML Validator](https://validator.w3.org/)
   - [CSS Validator](https://jigsaw.w3.org/css-validator/)

## Conclusion

By completing this project, you will have gained practical experience in creating a professional, responsive website using only **HTML** and **CSS**, while following best practices like **semantic HTML**, **CSS Grid/Flexbox**, and **responsive design principles**. Additionally, you will become familiar with common frontend development tools like **Chrome DevTools** and **W3C Validators**.
