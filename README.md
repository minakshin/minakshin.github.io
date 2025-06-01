# Portfolio Website - Minakshin

A modern, responsive portfolio website built with HTML5, CSS3, and JavaScript. Designed for GitHub Pages hosting to showcase your skills, projects, and professional experience.

## 🌟 Features

### Design & UX
- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and hover effects throughout
- **Interactive Elements**: Dynamic navigation, form validation, and user feedback

### Sections
1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction with animated statistics
3. **Skills**: Categorized technical skills with hover animations
4. **Projects**: Featured project showcase with overlay effects
5. **Contact**: Contact form with validation and social media links

### Technical Features
- **Smooth Scrolling**: Enhanced navigation experience
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Form Validation**: Client-side validation with user-friendly notifications
- **Scroll Animations**: Elements fade in as they come into view
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Performance Optimized**: Efficient CSS and JavaScript

## 🚀 Quick Start

### For GitHub Pages
1. **Fork or Clone** this repository
2. **Rename** the repository to `yourusername.github.io`
3. **Customize** the content in `index.html`
4. **Push** changes to the main branch
5. **Access** your site at `https://yourusername.github.io`

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/yourusername.github.io.git

# Navigate to the project directory
cd yourusername.github.io

# Open index.html in your browser or use a local server
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have live-server installed)
npx live-server

# Using PHP
php -S localhost:8000
```

## 📝 Customization Guide

### Personal Information
Replace placeholder content in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Your Professional Title</p>
<p class="hero-description">
    Your personal description and what you do.
</p>
```

#### About Section
- Update the about description paragraphs
- Modify statistics in the `.about-stats` section
- Replace placeholder content with your experience

#### Skills Section
- Add your technical skills in the `.skill-items` sections
- Organize skills by Frontend, Backend, and Tools categories

#### Projects Section
- Replace sample projects with your actual work
- Update project titles, descriptions, and technology stacks
- Add links to live demos and GitHub repositories

#### Contact Information
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
```

### Styling Customization

#### Color Scheme
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #ffd700;
    --text-dark: #333;
    --text-light: #6b7280;
}
```

#### Fonts
Change fonts by updating the Google Fonts import and CSS:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update navigation menu to include new section
4. Add scroll animations in `script.js` if needed

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#2563eb` - Main brand color
- **Secondary Purple**: `#7c3aed` - Accent color
- **Gold Highlight**: `#ffd700` - Special highlights
- **Text Dark**: `#333` - Primary text
- **Text Light**: `#6b7280` - Secondary text
- **Background Light**: `#f8fafc` - Section backgrounds

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: 700 weight
- **Body**: 400 weight
- **Buttons**: 600 weight

### Spacing
- **Sections**: 5rem padding (top/bottom)
- **Containers**: 1200px max-width
- **Grid Gaps**: 2-4rem between elements

## 📱 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

### Progressive Enhancement
- Core functionality works without JavaScript
- Enhanced features require modern browser capabilities
- Graceful degradation on older browsers

## 🔧 Technical Stack

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern layout with Grid and Flexbox
- **JavaScript ES6+**: Interactive functionality

### External Dependencies
- **Font Awesome**: Icons (CDN)
- **Google Fonts**: Typography (CDN)
- **No JavaScript frameworks**: Pure vanilla JS for optimal performance

## 📈 Performance Features

- **Optimized Images**: Responsive and compressed
- **Minimal Dependencies**: Only essential external resources
- **Efficient CSS**: Optimized selectors and properties
- **Lazy Loading**: Content loads as needed
- **Smooth Animations**: Hardware-accelerated transforms

## 🛡️ SEO & Accessibility

### SEO Optimized
- Semantic HTML structure
- Meta descriptions and Open Graph tags
- Structured data markup ready
- Optimized images with alt attributes

### Accessibility Features
- Keyboard navigation support
- Screen reader friendly
- ARIA labels where appropriate
- High contrast ratios
- Focus indicators

## 📄 File Structure

```
minakshin.github.io/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── assets/             # Images and other assets (create as needed)
    ├── images/
    └── icons/
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Google Fonts** for the Inter font family
- **Font Awesome** for the icon library
- **GitHub Pages** for free hosting
- **Inspiration** from modern portfolio designs

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to:
- Open an issue on GitHub
- Reach out via the contact form on the website
- Check the documentation for common customization tasks

---

**Happy coding! 🚀**

Made with ❤️ for the developer community.
