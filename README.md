# Minimalist Portfolio

A clean, responsive, and elegant portfolio website with a minimalist design aesthetic. This project features a modern layout, dark mode support, and subtle animations.

![Minimalist Portfolio Preview](/assets/images/pookie-duck.jpg)

## Features

- **Responsive Design**: Fully responsive layout that looks great on all devices
- **Dark Mode**: Automatic dark mode support based on user system preferences
- **Modern Aesthetics**: Clean typography and balanced whitespace
- **CSS Animations**: Subtle animations and transitions for enhanced user experience
- **Accessibility**: Built with accessibility in mind, including proper semantic HTML
- **Minimalist UI**: Focus on content with a distraction-free interface
- **Fast Loading**: Lightweight and optimized for performance

## Demo

You can see a live demo of the portfolio at [your-demo-link.com](https://your-demo-link.com)

You need to turn off the ad-blocker

## Tech Stack

- HTML5
- CSS3 (with CSS Variables)
- Google Fonts (Inter)
- Font Awesome Icons

## Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML and CSS (for customization)
- A web server or hosting solution for deployment

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/AddieX/minimalist-portfolio.git
   ```

2. Navigate to the project directory:

   ```
   cd minimalist-portfolio
   ```

3. Open `App.html` in your browser to view the site locally.

### Deployment

This is a static website, so you can deploy it to any web hosting service:

- GitHub Pages
- Netlify
- Vercel
- Or any traditional web hosting

## Customization

### Changing Content

1. Open `App.html` and update:
   - Your name
   - About me text
   - Social media links
   - Profile image (replace `/assets/images/pookie-duck.jpg`)

### Modifying Colors

The color scheme can be customized by editing the CSS variables in the `:root` selector in `src/css/main.css`:

```css
:root {
  --primary-color: #3a86ff; /* Main accent color */
  --secondary-color: #172c66; /* Secondary accent */
  --accent-color: #ff006e; /* Additional accent */
  --text-color: #2b2d42; /* Main text color */
  --text-light: #6c757d; /* Secondary text color */
  --background-color: #f8f9fa; /* Page background */
  --container-bg: #ffffff; /* Container background */
  /* ... other variables ... */
}
```

For dark mode, modify the variables in the `@media (prefers-color-scheme: dark)` section.

### Adding Social Links

To add more social links, copy and modify the existing social link structure in `App.html`:

```html
<a
  href="https://your-link.com"
  target="_blank"
  rel="noopener noreferrer"
  class="social-link your-class-name"
  aria-label="Your Platform Name"
>
  <i class="fab fa-your-icon"></i>
  <span>Your Platform</span>
</a>
```

Then add corresponding CSS in `main.css`:

```css
.your-class-name {
  background-color: #your-color;
}
```

## Browser Support

This portfolio is optimized for modern browsers including:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Fonts: [Google Fonts](https://fonts.google.com/)
- Icons: [Font Awesome](https://fontawesome.com/)

---

Made with ❤️ by [Addie](https://github.com/AddieX)
