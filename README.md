# MTM6201 – Final Project  
Home Tail Haven Website

## Overview
This project is a three-page website based on my high-fidelity wireframes in Figma.  
The site is for a fictional animal shelter called **Home Tail Haven**.

Pages included:
- Home  
- Available Pets  
- Adoption Process  

The goal was to follow my Figma designs, use Bootstrap and one extra CSS library, make the layout responsive, and publish the site using GitHub Pages.

---

## Process
1. I started by designing the layouts in Figma (desktop, tablet, and mobile).
2. I created the project structure: HTML files, a CSS folder, and an image folder.
3. I added Bootstrap from the CDN for the grid, spacing, and navigation.
4. I added Animate.css as the one extra CSS library.
5. I exported and resized images (400px, 800px, 1600px) and used them with the `<picture>` tag where needed.
6. I built each page, starting from mobile and then adjusting tablet and desktop layouts.
7. I tested the pages on different screen sizes and fixed spacing issues.
8. Finally, I connected the project to GitHub, pushed the files, and turned on GitHub Pages.

---

## Challenges
Some of the main challenges I faced:

- Matching the spacing and alignment from Figma in the browser  
- Making hero images responsive without stretching or cutting important parts  
- Keeping the HTML semantic and accessible  
- Getting image paths correct after uploading to GitHub Pages  

---

## How I overcame those challenges
- I used Bootstrap’s grid and spacing classes and then added a few custom rules in `main.css` to match the Figma layout more closely.  
- For hero images, I used `background-size: cover` and tested on different screen widths until the cropping looked natural.  
- I used semantic elements like `<header>`, `<main>`, `<section>` and added alt text to all images, plus a skip link to jump to main content.  
- When images did not show up on GitHub Pages, I checked the folder structure and file names and fixed any path mistakes.

---

## What I learned
By building this project I learned:

- How to turn high-fidelity wireframes into working HTML and CSS  
- How to use Bootstrap for real layouts, not just simple examples  
- How responsive images work using `<picture>` and different image sizes  
- How to structure a small multi-page site and keep the code organized  
- How to publish a site using GitHub Pages  
- How important accessibility and good contrast are in a design  

---

## Technologies and tools
- HTML5  
- CSS3  
- Bootstrap 5  
- Animate.css (extra CSS library)  
- Google Fonts (Arimo)  
- GitHub and GitHub Pages  
- Figma (for design)

---

## Assets and resources not created by me
- Bootstrap: https://getbootstrap.com  
- Animate.css: https://animate.style  
- Google Fonts (Arimo): https://fonts.google.com  

Pet photos were downloaded and resized for this project only.  
Social media icons are SVG files based on the official platform logos.  
No copyrighted material from other websites was copied directly into this project.

---

## Figma file
High-fidelity wireframes used for this site:

https://www.figma.com/design/5wttw4haObz3oB1jVa8VTy/High-Fi-wireframes?node-id=6-469&t=29E3g2NsQsvZzcoi-1