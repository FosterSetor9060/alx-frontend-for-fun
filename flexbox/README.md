# Flexbox Project

## Description
This project focuses on learning and implementing Flexbox, a powerful layout module in CSS. You will create responsive web pages using Flexbox for layout and alignment.

## Resources
- A Complete Guide to Flexbox | CSS-Tricks
- Flexbox Froggy - A game for learning CSS flexbox
- Flexbox Defense
- Flexbox Cheatsheet
- CSS Flexible Box Layout - CSS: Cascading Style Sheets | MDN
- afonsopacifer/awesome-flexbox: A curated list of CSS Flexible Box Layout Module or only Flexbox
- Build with Flexbox
- Flexplorer
- CSS Flexible Box Layout Module Level 1
- FLEX: A simple visual cheatsheet for flexbox

## Learning Objectives
By the end of this project, you should be able to:
- Explain what Flexbox is.
- Convert float positioning to a flex display.
- Horizontally and vertically align elements using Flexbox.
- Understand the difference between the main and cross axes.
- Identify properties that work on flex elements vs flex containers.
- Use shorthands for flex properties.
- Create a new page with Flexbox in mind.

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- A `README.md` at the root of the project directory is mandatory.
- All of your code will be executed on Ubuntu 18.04 using Python 3.7.x.
- All of your files should end with a new line.

## Files
### Required images for your HTML files
Download the images linked in the CSS Advanced project and place them into an `images` directory at the root of the project.

### HTML Starter File
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Description of the page less than 150 characters">
    <link rel="icon" type="image/png" href="images/favicon.jpg">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700|Raleway:700&display=swap" rel="stylesheet">
    <link rel='stylesheet' href='styles.css'>
  </head>
  <body>
    <!-- Header -->
    <header class="header" data-section-theme="dark">
      <div class="container">
        <div class="header-logo">
          <a href="#">
            <img src="images/logo-white.png" alt="Techium logo" width="160" height="40">
          </a>
        </div>
        <nav class="navbar-menu">
          <ul class="nav">
            <li class="nav-item">
              <a href="#" class="nav-link">Home</a>
            </li>
            <li class="nav-item">
              <a href="#services" class="nav-link">Services</a>
            </li>
            <li class="nav-item">
              <a href="#works" class="nav-link">Works</a>
            </li>
            <li class="nav-item">
              <a href="#about" class="nav-link">About</a>
            </li>
            <li class="nav-item">
              <a href="#latest_news" class="nav-link">Latest news</a>
            </li>
            <li class="nav-item">
              <a href="#testimonials" class="nav-link">Testimonials</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link">Contact</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
    <!-- Main -->
    <main>
      <!-- Hero section -->
      <section class="section-hero" data-section-theme="dark">
        <div class="container">
          <div class="section-body">
            <section class="section-inner">
              <h2 class="section-title">We help you build your brand</h2>
              <a href="#" class="button">Get Started</a>
            </section>
          </div>
        </div>
      </section>
      <!-- Services section -->
      <section id="services" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Our Services</h2>
          </header>
          <!-- Add your content here -->
        </div>
      </section>
    </main>
  </body>
</html>
