# GGRCC - Global Governance Research Centre Consortium

This repository contains the static website for the Global Governance Research Centre Consortium.

## Website Structure

The website consists of the following pages:

- **index.html** - Landing page with hero section and overview
- **about.html** - Information about GGRCC, mission, and values
- **events.html** - Upcoming and past events, conferences, and workshops
- **publications.html** - Research publications, working papers, and notices
- **style.css** - Shared stylesheet for all pages

## Local Development

To view the website locally, simply open any of the HTML files in a web browser:

```bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js http-server (requires installation)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Deployment

This static website can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

For GitHub Pages deployment, enable GitHub Pages in the repository settings and select the branch containing these files.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Clean and professional styling
- Easy to navigate with consistent navigation bar
- Accessible HTML structure
- Modern CSS with CSS variables for easy customization

## Customization

To customize the colors and styling, edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... other variables */
}
```

## License

© 2026 Global Governance Research Centre Consortium. All rights reserved.