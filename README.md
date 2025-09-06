# 📷 Alec Soth Photography Portfolio

A modern, responsive photography website built with **HTML**, **Tailwind CSS**, and vanilla **JavaScript**. Explore beautiful portfolio features, a professional layout, dark/light mode, and advanced interactivity—all optimized for user experience and accessibility.

![Photography Portfolio](https://img.shields.io/badge/Built%20with-Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Features

### 🌓 **Dark/Light Mode Toggle**

- Top-right switch with animated sun/moon icons
- Smooth transition between light and dark themes
- User preference saved in localStorage
- CSS variables for seamless color switching

### 📱 **Responsive Design**

- Mobile-first layout with adaptive grids and cards
- Hamburger menu for mobile navigation
- Touch-friendly interactions
- Breakpoints: `sm:`, `md:`, `lg:` for different screen sizes

### 🧭 **Smooth Scroll Navigation**

- All navigation links scroll seamlessly to each section
- Progress bar at top indicates scroll position
- Automatic mobile menu closing after navigation

### 📊 **Statistics Section**

- Large animated counters displaying:
  - **150+** Projects Completed
  - **300+** Happy Clients
  - **15+** Years Experience
  - **25+** Awards Won

### 🖼️ **Interactive Projects Gallery**

- Project cards with gradient backgrounds and category tags
- **Filter projects by type**: All, Digital, Documentary, Personal, Nature
- Hover effects and smooth transitions
- Responsive grid layout (1-2-3 columns based on screen size)

### 💬 **Testimonials**

- Glass-morphism styled testimonial cards
- Client names, roles, and professional feedback
- Three-column responsive layout
- Avatar placeholders with initials

### 📧 **Newsletter Signup**

- Eye-catching gradient banner section
- Email input form with validation-ready structure
- Subscription confirmation feedback system

### 📞 **Contact Section**

- Comprehensive contact form with fields:
  - First Name & Last Name
  - Email Address
  - Subject
  - Message (textarea)
- Contact information display:
  - 📍 Location: Minneapolis, Minnesota
  - ✉️ Email: contact@alecsoth.com
  - 📱 Phone: +1 (555) 123-4567
- Social media links: Instagram, Twitter, Facebook

### ⬆️ **Back-to-Top Button**

- Appears after scrolling 300px
- Smooth scroll animation to header
- Fade-in/fade-out transitions

### 🦶 **Professional Footer**

- Four-column layout with sections:
  - **Brand**: Logo and description
  - **Site Menu**: Navigation links
  - **Reviews**: Review-related pages
  - **Support**: Contact and help links
- Copyright notice and year

### ✨ **Animations & Visual Effects**

- **Intersection Observer** for scroll-triggered animations
- Fade-in and slide-up effects
- Hover transforms on cards and buttons
- Glass morphism effects for modern UI
- Gradient backgrounds and text effects

### ♿ **Accessibility & SEO**

- Semantic HTML5 structure
- ARIA labels for screen readers
- Keyboard navigation support
- Focus states for all interactive elements
- SEO-optimized meta tags and descriptions
- Proper heading hierarchy (h1, h2, h3, h4)

---

## 🛠️ Technologies Used

| Technology       | Purpose                        | Version   |
| ---------------- | ------------------------------ | --------- |
| **HTML5**        | Semantic markup structure      | Latest    |
| **Tailwind CSS** | Utility-first CSS framework    | 3.x (CDN) |
| **JavaScript**   | Interactive functionality      | ES6+      |
| **Google Fonts** | Typography (Inter font family) | Latest    |

---

## 📂 Project Structure

```
photography-portfolio/
├── index.html    # Main HTML file
└── README.md     # Project documentation
```

---

## 🚀 Quick Start

### Option 1: Direct Usage

1. **Clone** or download the repository
2. **Open** the HTML file in your preferred code editor
3. **Customize** content, images, and styling as needed
4. **Test** in multiple browsers and devices

---

## 🎨 Customization Guide

### 🎨 **Colors & Theming**

The color system uses CSS custom properties defined in the Tailwind config:

```javascript
colors: {
  primary: {
    50: '#f0fdfa',
    100: '#ccfbf1',
    // ... more shades
    500: '#137548', // Main brand color
    600: '#0f766e',
    // ... darker shades
  }
}
```

### 📝 **Content Updates**

Replace the following placeholder content:

1. **Hero Section**: Update title, quote, and call-to-action text
2. **About Section**: Replace Alec Soth's bio with your information
3. **Projects**: Add your own project images and descriptions
4. **Testimonials**: Include real client feedback
5. **Contact Info**: Update location, email, phone, and social links

### 🖼️ **Images**

Replace gradient placeholders with actual images:

- Hero images (2 images recommended)
- About section portrait
- Project gallery images (6 projects)
- Add proper `alt` text for accessibility

### 📱 **Social Media**

Update social media links in the contact section:

```html
<a href="#" class="...">Instagram</a>
<a href="#" class="...">Twitter</a>
<a href="#" class="...">Facebook</a>
```

---

## 📋 Sections Overview

| Section               | Features                                              | Purpose                           |
| --------------------- | ----------------------------------------------------- | --------------------------------- |
| **Navigation**        | Logo, menu links, theme toggle, mobile hamburger      | Site navigation and theme control |
| **Hero**              | Large title, inspiring quote, CTA button, hero images | First impression and engagement   |
| **About Photography** | Definition and artistic context                       | Educational content               |
| **Statistics**        | Animated counters for achievements                    | Build credibility and trust       |
| **About Founder**     | Biography, skills tags, portrait image                | Personal connection and expertise |
| **Projects**          | Filterable gallery with project cards                 | Showcase portfolio work           |
| **Testimonials**      | Client feedback with glass-morphism design            | Social proof and credibility      |
| **Newsletter**        | Email signup with gradient background                 | Lead generation                   |
| **Contact**           | Form, contact info, social media links                | Communication channels            |
| **Footer**            | Site links, copyright, additional navigation          | Site completion and legal info    |

---

## 🔧 Advanced Features

### **Theme System**

- Automatic dark mode detection based on system preferences
- Manual toggle override with persistent storage
- Smooth transitions between themes using CSS transitions

### **Performance Optimizations**

- Single HTML file with embedded CSS and JavaScript
- Optimized for fast loading and minimal HTTP requests
- Lazy loading preparation for images

### **Browser Compatibility**

- Modern browsers (Chrome 88+, Firefox 85+, Safari 14+)
- Progressive enhancement for older browsers
- Mobile browsers fully supported

---

## 🧪 Testing Checklist

- [ ] **Responsive Design**: Test on mobile, tablet, and desktop
- [ ] **Dark/Light Mode**: Toggle functionality and theme persistence
- [ ] **Navigation**: All links work and smooth scroll functions
- [ ] **Forms**: Contact form and newsletter validation
- [ ] **Accessibility**: Screen reader compatibility and keyboard navigation
- [ ] **Performance**: Page load speed and animation smoothness

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the project
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

---

## 🙏 Acknowledgments

- **Alec Soth**: Inspiration from the renowned American photographer
- **Tailwind CSS**: For the amazing utility-first framework
- **Unsplash**: For high-quality placeholder images
- **Font Awesome/Heroicons**: For beautiful SVG icons

---

## 🔄 Changelog

### Version 1.0.0 (Current)

- ✅ Initial release with all core features
- ✅ Dark/light mode toggle
- ✅ Responsive design
- ✅ Project filtering system
- ✅ Contact form and newsletter
- ✅ Testimonials section
- ✅ Accessibility improvements

---

**⭐ If you found this project helpful, please give it a star!**

---

_Built with 💜 By Saurabh, using Tailwind CSS and vanilla JavaScript_
