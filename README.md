# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript featuring a sleek black and white design.

## ✨ Features

- **Modern Design**: Clean black and white color scheme with elegant typography
- **Fully Responsive**: Optimized for all devices and screen sizes
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Mobile-First**: Mobile navigation with hamburger menu
- **Performance Optimized**: Lightweight and fast loading
- **SEO Friendly**: Semantic HTML structure
- **Cross-Browser Compatible**: Works on all modern browsers

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Installation

1. Download or clone this repository
2. Open `index.html` in your web browser
3. That's it! Your portfolio is ready to view

### Local Development

For development, you can use any local server:

**Using Python:**

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**

```bash
npx serve .
```

**Using Live Server (VS Code Extension):**

- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

## 🎨 Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section

```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full Stack Developer & Creative Designer</p>
<p class="hero-description">
  I create beautiful, functional, and user-centered digital experiences that
  make a difference.
</p>
```

#### About Section

```html
<p>
  I'm a passionate developer with a love for creating innovative solutions and
  beautiful user experiences...
</p>
```

#### Contact Information

```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### Projects

Replace the sample projects with your own:

```html
<div class="project-card">
  <div class="project-image">
    <!-- Add your project image here -->
    <img src="path/to/your/image.jpg" alt="Project Name" />
  </div>
  <div class="project-content">
    <h3>Your Project Name</h3>
    <p>Project description goes here...</p>
    <div class="project-tech">
      <span>Technology 1</span>
      <span>Technology 2</span>
    </div>
    <div class="project-links">
      <a href="your-demo-link" class="project-link">Live Demo</a>
      <a href="your-github-link" class="project-link">Code</a>
    </div>
  </div>
</div>
```

### Skills

Update the skills and proficiency levels:

```html
<div class="skill-item">
  <span>Skill Name</span>
  <div class="skill-bar">
    <div class="skill-progress" style="width: 85%"></div>
  </div>
</div>
```

### Colors and Styling

Modify the color scheme in `styles.css`:

```css
:root {
  --primary-color: #000000;
  --secondary-color: #ffffff;
  --accent-color: #cccccc;
  --text-primary: #ffffff;
  --text-secondary: #cccccc;
  --background-primary: #000000;
  --background-secondary: #0a0a0a;
}
```

### Fonts

Change the font family in `styles.css`:

```css
body {
  font-family: "Your-Font-Name", sans-serif;
}
```

And update the Google Fonts link in `index.html`:

```html
<link
  href="https://fonts.googleapis.com/css2?family=Your-Font-Name:wght@300;400;500;600;700&display=swap"
  rel="stylesheet"
/>
```

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px

## 🔧 Advanced Customization

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add navigation link in the navbar
4. Update JavaScript if needed

### Custom Animations

Add custom CSS animations:

```css
@keyframes yourAnimation {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.your-element {
  animation: yourAnimation 0.8s ease-out;
}
```

### Form Integration

To connect the contact form to a backend service:

1. Update the form action in `index.html`
2. Modify the form handling in `script.js`
3. Add your backend endpoint

Example with a service like Formspree:

```html
<form
  class="contact-form"
  action="https://formspree.io/your-email@domain.com"
  method="POST"
></form>
```

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🌟 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help with customization, please:

1. Check the existing issues
2. Create a new issue with a detailed description
3. Include your browser and operating system information

## 🎯 Roadmap

- [ ] Dark/Light theme toggle
- [ ] Blog section
- [ ] Portfolio filtering
- [ ] Testimonials section
- [ ] Downloadable resume
- [ ] Multi-language support
- [ ] PWA capabilities

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Modern CSS Grid and Flexbox
- Intersection Observer API for animations

---

**Happy coding! 🚀**

Feel free to customize this portfolio to match your personal brand and showcase your skills effectively.
