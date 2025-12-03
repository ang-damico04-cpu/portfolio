# Portfolio Website - Angelina D'Amico

An elegant portfolio website showcasing web design projects.

## Features

- **Navigation Bar**: Clean header with name and section links
- **About Me Section**: Professional bio with image on the left
- **Projects Section**: Showcase of web design projects with descriptions
- **Contact Section**: Contact form for potential employers
- **Footer**: LinkedIn link and copyright information

## Customization Guide

To personalize this portfolio:

1. **Profile Image**: Replace the placeholder image in the About section (line 32 of `index.html`) with your professional photo
2. **Project Images**: Replace all placeholder project images (lines 51, 66, 81, 96) with actual screenshots of your work
3. **LinkedIn Profile**: Update the LinkedIn URL in the footer (line 146) with your actual LinkedIn profile
4. **Contact Form**: The form currently needs backend integration. You can:
   - Add a form action to send to your email service
   - Integrate with a service like Formspree, Netlify Forms, or Google Forms
   - Add JavaScript to handle form submissions

## Viewing the Website

Simply open `index.html` in a web browser, or use a local server:

```bash
python3 -m http.server 8080
```

Then navigate to `http://localhost:8080`

## Design

- **Fonts**: Playfair Display for headings, Raleway for body text
- **Colors**: Warm brown (#8b7355), Navy (#2c3e50), and Gold accents (#d4af37)
- **Fully Responsive**: Adapts to mobile, tablet, and desktop screens