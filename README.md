# Sooraj Cargo Movers Website

A minimal, modern website for Sooraj Cargo Movers transportation company. Built with vanilla HTML, CSS, and JavaScript for fast loading and optimal performance.

## Features

- **Minimal Design**: Clean, monochromatic design with ample white space
- **Responsive Layout**: Fully responsive design that works on all devices
- **Multi-page Structure**: 
  - Home page with hero section and service previews
  - Services page with detailed service descriptions
  - About page with company information and values
  - Contact page with contact form and quote request form
- **Interactive Elements**: 
  - Mobile-friendly navigation menu
  - Form validation for contact and quote forms
  - Smooth scrolling animations
- **Fast Loading**: No external dependencies, optimized for performance

## File Structure

```
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page with forms
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --color-primary: #000000;
    --color-secondary: #1a1a1a;
    /* ... */
}
```

### Contact Information
Update contact details in:
- Footer section of all HTML files
- Contact page information section

### Form Submission
Currently, forms log to console. To enable actual form submission:
1. Set up a backend service (e.g., PHP, Node.js, or form service like Formspree)
2. Update the form submission handlers in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 Sooraj Cargo Movers. All rights reserved.

