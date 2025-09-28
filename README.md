# Portfolio Website - Piyush Sahu

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, featuring a clean design with dark/light theme toggle and smooth animations.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Theme Toggle**: Users can switch between dark and light themes with theme persistence using localStorage
- **Smooth Animations**: Hover effects, transitions, and smooth scrolling for enhanced user experience
- **Modern UI/UX**: Clean, professional design with gradient accents and glassmorphism effects
- **Contact Form**: Integrated contact form using Formspree for message handling
- **Interactive Navigation**: Fixed header with smooth scroll-to-section navigation

## 🚀 Live Demo

Visit the live portfolio: [Portfolio Website](https://your-portfolio-url.com)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── images/            # Portfolio images and assets
│   ├── WHITE_11zon.jpeg
│   ├── PRES.png
│   ├── ecommerce.png
│   └── slideshow.png
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and CSS Variables
- **JavaScript**: Theme toggle functionality and form handling
- **External Libraries**:
  - [Feather Icons](https://feathericons.com/) - Clean, customizable icons
  - [Devicons](https://devicon.dev/) - Technology stack icons
  - [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter) - Typography
  - [Formspree](https://formspree.io/) - Contact form backend

## 🎨 Design Features

### Color Scheme
- **Light Mode**: Clean whites and grays with purple and teal accents
- **Dark Mode**: Dark backgrounds with consistent accent colors
- **Gradient Accents**: Beautiful gradient combinations for buttons and highlights

### Typography
- Primary font: Inter (Google Fonts)
- Responsive font sizing
- Proper contrast ratios for accessibility

### Layout
- Mobile-first responsive design
- CSS Grid for complex layouts
- Flexbox for component alignment
- Smooth scroll behavior

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 991px
- **Desktop**: ≥ 992px

## 🔧 Setup and Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/piyushs8589/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server like Live Server (VS Code extension)

3. **Customize content**
   - Update personal information in `index.html`
   - Replace images in the `/images` folder
   - Modify styling in the `<style>` section as needed

## 📧 Contact Form Setup

The contact form uses Formspree for backend processing:

1. Sign up at [Formspree](https://formspree.io/)
2. Create a new form and get your form endpoint
3. Update the form action in the HTML:
   ```html
   <form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 🎯 Sections Overview

### 1. Hero Section
- Profile photo and introduction
- Call-to-action buttons
- Gradient text effects

### 2. About Me
- Personal introduction and background
- Career objectives

### 3. Skills
- Technical skills organized by category
- Visual skill badges with icons

### 4. Projects
- Featured projects with images
- Technology stack tags
- Live demo and GitHub links

### 5. Experience
- Work experience and internships
- Chronological timeline format

### 6. Education
- Academic background
- Institution details

### 7. Honors & Awards
- Recognition and achievements

### 8. Certifications
- Professional certifications with verification links

### 9. Contact
- Social media links
- Contact form
- Professional networking information

## 🌙 Theme Toggle Implementation

The theme toggle uses:
- CSS custom properties (variables) for easy theme switching
- JavaScript to toggle body class
- localStorage to persist user preference
- Animated icon transitions

```javascript
// Theme persistence
localStorage.setItem('theme', 'dark');
const savedTheme = localStorage.getItem('theme');
```

## 🎨 Customization Guide

### Changing Colors
Update the CSS variables in the `:root` selector:
```css
:root {
    --accent-color-1: #your-color;
    --accent-color-2: #your-color;
    /* Add more custom colors */
}
```

### Adding New Sections
1. Add HTML structure following existing patterns
2. Include appropriate styling
3. Update navigation links
4. Ensure responsive behavior

### Modifying Animations
Adjust transition properties and transform effects:
```css
.element {
    transition: transform 0.3s ease;
}
.element:hover {
    transform: translateY(-5px);
}
```

## 🚀 Performance Optimizations

- Efficient CSS with minimal specificity
- Optimized images and assets
- Minimal JavaScript for core functionality
- External resources loaded from CDNs
- Smooth scroll behavior with CSS

## 🔍 SEO Considerations

- Semantic HTML structure
- Proper heading hierarchy
- Meta tags for description and viewport
- Alt texts for images
- Accessible navigation

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Feather Icons](https://feathericons.com/) for beautiful iconography
- [Devicons](https://devicon.dev/) for technology logos
- [Google Fonts](https://fonts.google.com/) for typography
- [Formspree](https://formspree.io/) for form handling

## 📞 Contact

**Piyush Sahu**
- 📧 Email: piyushsahu00096@gmail.com
- 🔗 LinkedIn: [piyush-sahu-147137269](https://www.linkedin.com/in/piyush-sahu-147137269)
- 💻 GitHub: [piyushs8589](https://github.com/piyushs8589)

---

<p align="center">Made with ❤️ by Piyush Sahu</p>
