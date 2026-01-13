# Nuvatra Website

Professional website for Nuvatra showcasing innovative AI products including Grubify, RepsRight, and Nuvatra Voice.

## Features

- **Modern Design**: Clean, professional aesthetic with gradient accents
- **Responsive Layout**: Fully responsive design that works on all devices
- **Product Showcases**: Dedicated sections for each product
- **Interactive Elements**: Smooth scrolling, animations, and mobile navigation
- **Contact Form**: Built-in contact form for inquiries

## Products

1. **Grubify** - AI-powered food ordering and restaurant management platform
   - Website: https://grubify.ai

2. **RepsRight** - Fitness companion app available on the App Store
   - Features workout tracking, progress monitoring, and AI-powered insights

3. **Nuvatra Voice** - AI receptionist for 24/7 call handling
   - Intelligent call routing, message taking, and appointment scheduling

## File Structure

```
Nuvatra-site/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript for interactivity
├── assets/             # Logo and image assets
│   ├── nuvatra-logo.png
│   ├── nuvatra-logo.svg
│   ├── repsright-logo.png
│   ├── repsright-logo.svg
│   ├── nuvatra-voice-logo.png
│   └── nuvatra-voice-logo.svg
├── config.js           # EmailJS configuration
└── README.md           # This file
```

## Deployment & Hosting

**Current Setup:**
- **Domain Management**: Squarespace (nuvatrahq.com)
- **Hosting**: Netlify
- **Repository**: GitHub (https://github.com/rajveer-gill/Nuvatra-homepage)

**Deployment Process:**
1. Push changes to GitHub repository
2. Netlify automatically deploys from GitHub
3. Domain is configured through Squarespace DNS settings pointing to Netlify

**Important Notes:**
- Domain DNS is managed through Squarespace
- Netlify handles hosting and SSL certificates
- Changes pushed to GitHub automatically trigger Netlify deployments
- Contact form uses EmailJS (credentials in `config.js`)

## Setup

1. Clone or download this repository
2. Open `index.html` in a web browser
3. For production deployment:
   - Push changes to GitHub
   - Netlify will automatically deploy
   - Ensure DNS settings in Squarespace point to Netlify

## Customization

### Updating Contact Information
Edit the contact section in `index.html` to update email addresses and contact details.

### Email Form Configuration
The contact form uses EmailJS for automatic email sending. Configuration is in `config.js`:
- Public Key: EmailJS public key
- Service ID: EmailJS service ID
- Template ID: EmailJS email template ID

To update EmailJS settings, edit `config.js` with your new credentials.

### Adding Products
Add new product cards in the `products-grid` section following the existing structure.

### Styling
Modify `styles.css` to customize colors, fonts, and layout. Key CSS variables are defined at the top of the file.

### Logo Updates
Replace the SVG files in the `assets` folder with updated logos if needed. Ensure they maintain the same dimensions or update the CSS accordingly.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 Nuvatra. All rights reserved.
