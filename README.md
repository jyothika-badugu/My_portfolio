# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases professional skills, projects, and qualifications with a beautiful and interactive user interface.

## Features

- 🌓 Dark/Light theme toggle with persistent storage
- 📱 Fully responsive design for all devices
- 🎨 Modern and clean UI with smooth animations
- 📜 Smooth scrolling navigation
- 🎯 Interactive portfolio showcase
- 📊 Skills section with progress bars
- 📝 Contact form
- 🔍 SEO optimized
- ⚡ Fast loading and performance optimized

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6+)
- Swiper.js (for portfolio slider)
- Google Fonts (Poppins)

## Project Structure

```
Portfolio-Website/
├── assets/
│   ├── newcss.css      # Main stylesheet
│   └── ptj.js          # Main JavaScript file
├── index.html          # Main HTML file
└── README.md           # Project documentation
```

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Portfolio-Website.git
```

2. Navigate to the project directory:
```bash
cd Portfolio-Website
```

3. Open `index.html` in your web browser to view the website.

## Customization

### Theme Colors
The website uses CSS variables for easy theming. You can modify the colors in the `:root` selector in `newcss.css`:

```css
:root {
  --first-color: #ff69b4;
  --first-color-second: #ffb6c1;
  --first-color-alt: #ff1493;
  /* ... other color variables ... */
}
```

### Dark Theme Colors
Dark theme colors can be modified in the `.dark-theme` selector:

```css
body.dark-theme {
  --first-color: #ff9a9e;
  --first-color-second: #2C3E50;
  /* ... other dark theme variables ... */
}
```

## Features in Detail

### Navigation
- Responsive navigation menu with hamburger toggle
- Smooth scrolling to sections
- Active link highlighting based on scroll position
- Fixed header with scroll shadow effect

### Home Section
- Animated blob background
- Social media links
- Scroll down indicator

### About Section
- Personal information
- Info boxes with hover effects
- Download CV button

### Skills Section
- Expandable skill groups
- Progress bars for skill levels
- Interactive hover effects

### Qualifications Section
- Tabbed interface for education and work experience
- Timeline layout
- Modal popups for detailed information

### Portfolio Section
- Swiper.js powered slider
- Project cards with hover effects
- Modal popups for project details

### Contact Section
- Styled contact form
- Social media links
- Contact information cards

## Browser Support

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Performance

The website is optimized for performance with:
- Efficient CSS using custom properties
- Optimized JavaScript code
- Responsive images
- Smooth animations using CSS transitions
- Lazy loading for images

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/Portfolio-Website](https://github.com/yourusername/Portfolio-Website) 