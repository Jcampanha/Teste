# Dancer Portfolio Website

A modern, responsive portfolio website designed specifically for professional dancers and choreographers. This website showcases dance performances, skills, and provides a professional online presence.

## Features

### 🎨 Design
- **Modern & Elegant**: Clean, professional design with beautiful gradients and animations
- **Responsive**: Fully responsive design that works on all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS animations and JavaScript interactions for an engaging user experience
- **Typography**: Beautiful typography using Google Fonts (Playfair Display & Poppins)

### 📱 Sections
1. **Hero Section**: Eye-catching introduction with animated elements
2. **About**: Professional background, skills, and statistics
3. **Performances**: Showcase of featured dance performances
4. **Gallery**: Visual portfolio of dance photos/videos
5. **Contact**: Contact form and professional information

### ⚡ Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Smooth navigation between sections
- **Form Validation**: Contact form with email validation
- **Scroll Animations**: Elements animate as they come into view
- **Hover Effects**: Interactive hover effects on cards and buttons
- **Scroll to Top**: Convenient button to return to the top
- **Notifications**: Success/error notifications for form submissions

### 🎭 Performance Showcase
- Performance cards with descriptions
- Dance style tags
- Performance dates and venues
- Hover effects and animations

## File Structure

```
dancer-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md          # This documentation
```

## Customization

### Personal Information
Update the following in `index.html`:
- Name: "Elena Rodriguez" → Your name
- Email: "elena.rodriguez@email.com" → Your email
- Phone: "+1 (555) 123-4567" → Your phone number
- Location: "New York, NY" → Your location
- Social media links in the contact section

### Content
- **About Section**: Update the personal story and experience
- **Statistics**: Modify the numbers in the stats section
- **Performances**: Add your own performance details
- **Skills**: Update the dance style tags
- **Gallery**: Replace placeholder text with actual images

### Styling
The website uses a modern color scheme:
- Primary: `#e74c3c` (Red)
- Secondary: `#f39c12` (Orange)
- Accent: `#667eea` to `#764ba2` (Purple gradient)
- Text: `#2c3e50` (Dark blue-gray)

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

- **Fast Loading**: Optimized CSS and JavaScript
- **SEO Friendly**: Semantic HTML structure
- **Accessibility**: Proper ARIA labels and keyboard navigation
- **Cross-browser**: Compatible with all modern browsers

## Getting Started

1. **Download/Clone** the files to your local machine
2. **Customize** the content in `index.html` with your information
3. **Replace** placeholder content with your actual content
4. **Add Images**: Replace gallery placeholders with actual dance photos
5. **Deploy**: Upload to your web hosting service

## Adding Real Images

To add real images to the gallery:

1. Replace the gallery placeholders in `index.html`:
```html
<div class="gallery-item">
    <img src="path/to/your/image.jpg" alt="Dance Performance">
</div>
```

2. Update the CSS for gallery items:
```css
.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 15px;
}
```

## Contact Form

The contact form includes:
- Name field
- Email field (with validation)
- Subject field
- Message field
- Form validation and success notifications

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
1. Set up a backend service (PHP, Node.js, etc.)
2. Configure email sending functionality
3. Update the JavaScript to make actual HTTP requests

## License

This project is open source and available under the MIT License.

## Support

For questions or customization help, feel free to reach out!

---

**Created with ❤️ for dancers and performers worldwide**