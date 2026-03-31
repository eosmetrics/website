<<<<<<< HEAD
# EosMetrics - Professional Testing Services Website

A modern, responsive website for a software testing services company built with HTML, CSS, and JavaScript.

## Features

- 🎨 **Modern Design**: Clean, professional design with gradient accents and smooth animations
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight**: No heavy frameworks, pure HTML/CSS/JS for optimal performance
- 🎯 **SEO Optimized**: Proper semantic HTML and meta tags
- 💫 **Interactive Elements**: Smooth scrolling, animations, and form validation
- 📝 **Contact Form**: Fully functional contact form with validation

## Sections

1. **Hero Section**: Eye-catching introduction with key statistics
2. **Services**: Six comprehensive testing service offerings
3. **About**: Company information and key features
4. **Testimonials**: Client testimonials and reviews
5. **Contact**: Contact information and inquiry form
6. **Footer**: Additional links and social media

## Services Offered

- Manual Testing
- Test Automation
- Performance Testing
- Security Testing
- Mobile Testing
- API Testing

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.) if you want to customize

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

### Local Development

You can use any local server to run the website. Here are a few options:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

Then visit `http://localhost:8000` (or the port shown) in your browser.

## Customization

### Colors

The website uses CSS custom properties (variables) for easy color customization. Edit these in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --secondary-color: #0ea5e9;
    /* ... more colors */
}
```

### Content

- **Company Name**: Search and replace "EosMetrics" in `index.html`
- **Contact Info**: Update the contact section in `index.html`
- **Services**: Modify the services grid section to add/remove services
- **Testimonials**: Edit the testimonials section with your own reviews

### Images

Replace the placeholder icons with your own:
- Add images to an `images/` folder
- Update the image references in `index.html`
- The current design uses emoji placeholders for simplicity

## Form Integration

The contact form currently logs data to the console. To integrate with a backend:

1. **Email Service (e.g., EmailJS, Formspree)**:
```javascript
// In script.js, replace the fetch comment with:
emailjs.send("service_id", "template_id", formData)
    .then(() => showSuccessMessage())
    .catch(() => showErrorMessage());
```

2. **Custom Backend**:
```javascript
// In script.js, uncomment and modify the fetch call:
const response = await fetch('YOUR_API_ENDPOINT', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
});
```

3. **Third-party Forms**: Use services like Netlify Forms, Google Forms, or Typeform

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies
- Minimal CSS and JavaScript
- Fast load times
- Optimized for Core Web Vitals

## File Structure

```
website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## License

This project is open source and available for personal and commercial use.

## Credits

- Font: Inter from Google Fonts
- Icons: Unicode emoji characters
- Design: Custom modern gradient design

## Support

For questions or support, contact: info@eosmetrics.com

---

**Built with ❤️ for quality assurance professionals**
=======
# website
>>>>>>> origin/main
