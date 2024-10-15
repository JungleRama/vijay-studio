# Vijay Studio Portfolio Website

This repository contains the source code for the **Vijay Studio** portfolio website, which was originally developed within Shopify's **Dawn theme** using a combination of **HTML, CSS, JavaScript**, and **Liquid**. The website showcases the creative work of Vijay Sarathi, dynamically generating a projects section from a JSON file.

## Live Website

You can access the live version of the website deployed on GitHub Pages/Netlify/Vercel here:
[Live Site URL]([https://your-live-site-link.com](https://4wntvd-y0.myshopify.com/#home))

## Project Overview

### Technologies Used

- **HTML**: Used for the structure of the webpage.
- **CSS**: Custom styles to create a visually appealing and responsive design.
- **JavaScript**: Used to dynamically generate sections of the website, like the projects section, by fetching and processing a JSON file.
- **Liquid**: Originally used within the Shopify platform for templating and dynamic content generation. For deployment on static hosting platforms, some of the Liquid functionality has been replaced with JavaScript.

### Files and Structure

- **`index.json`**: Configurations and content for the homepage.
- **`projects.json`**: Contains the array of objects used to dynamically generate the projects section. Each object represents a project, including fields for the project name, description, image, GitHub link, and Google Drive link.
- **`header.liquid.html`**: The header section of the website, including the navigation menu.
- **`footer.liquid.html`**: The footer section of the website.
- **`custom-hero.liquid.html`**: Contains the HTML and Liquid for the hero section of the site.
- **`custom-about.liquid.html`**: The "About" section content, explaining the portfolio and the work of Vijay Sarathi.
- **`projects-section.liquid.html`**: This file dynamically generates the projects section by fetching project data from the `projects.json` file using JavaScript.
- **`custom-contact-form.liquid.html`**: Contains the HTML and Liquid for the contact form section.
- **`Assets`**: Contains all image assets used in the project, including project images and the website's logo.

### Project Sections

- **Header**: Contains navigation links to different sections of the page.
- **Hero Section**: Introduces the website and its purpose with a prominent heading and background image.
- **About Section**: Provides information about Vijay Sarathi and his work.
- **Projects Section**: Dynamically generated using JavaScript from the `projects.json` file. Each project is displayed in a card layout with an image, brief description, and links to view the project.
- **Contact Section**: A contact form allowing visitors to reach out for inquiries.

## Instructions for Viewing the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/vijay-studio-website.git
