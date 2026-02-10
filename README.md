# Interactive Web App

A responsive and interactive web application built with vanilla HTML, CSS, and JavaScript. This app is designed to be simple to maintain and easy to host publicly.

## Features

- 📱 **Fully Responsive**: Works seamlessly on mobile, tablet, and desktop devices
- ⚡ **Fast Performance**: No frameworks, just clean vanilla JavaScript
- 🎨 **Modern Design**: Beautiful gradient backgrounds and smooth animations
- 🔒 **Secure**: Built with security best practices
- 🌐 **Easy to Host**: Can be deployed to any static hosting platform
- 💡 **Interactive**: Engaging user experience with dynamic interactions

## Project Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # Responsive CSS styling
├── script.js       # Interactive JavaScript functionality
└── README.md       # Project documentation
```

## Local Development

To run this web app locally:

1. Clone the repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

Then visit `http://localhost:8000` in your browser.

## Hosting Options

This web app can be easily hosted on various platforms:

### GitHub Pages
1. Go to repository Settings > Pages
2. Select the branch to deploy (e.g., `main` or `copilot/develop-web-app-responsive`)
3. Your site will be available at `https://[username].github.io/[repository-name]/`

### Netlify
1. Sign up at [netlify.com](https://www.netlify.com/)
2. Connect your GitHub repository
3. Deploy with one click

### Vercel
1. Sign up at [vercel.com](https://vercel.com/)
2. Import your GitHub repository
3. Deploy automatically

### Other Options
- AWS S3 + CloudFront
- Azure Static Web Apps
- Google Firebase Hosting
- Cloudflare Pages

## Features Overview

### Navigation
- Responsive mobile menu
- Smooth scroll navigation
- Active section highlighting

### Hero Section
- Animated gradient background
- Floating circle animations
- Call-to-action button

### Features Section
- Grid layout with hover effects
- Icon-based feature cards
- Responsive design

### Gallery
- Interactive gallery items
- Color-coded hover effects
- Click to toggle active state

### Contact Form
- Form validation
- Email validation
- Success/error messages

### Additional Features
- Back-to-top button
- Keyboard navigation (ESC to close gallery items)
- Intersection Observer for scroll animations
- Smooth transitions throughout

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... */
}
```

### Content
Edit the text and structure in `index.html` to match your needs.

### Interactivity
Modify `script.js` to add or customize interactive features.

## License

See LICENSE file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
