# Best Coffee ☕

A modern and responsive coffee shop landing page built with **HTML** and **CSS**. Beautiful showcase of coffee products, services, and brand story.

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- ☕ **Product Showcase** - Beautiful display of coffee products
- 🎨 **Modern Design** - Clean, professional, and attractive layout
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- 🖼️ **High-Quality Images** - Optimized images for fast loading
- 🔗 **Navigation Menu** - Smooth scrolling sections
- 📧 **Contact Form** - Get in touch with the business
- 🗺️ **Location Map** - Embedded map for business location
- 💬 **Customer Reviews** - Testimonials section
- 🎯 **Call-to-Action Buttons** - Clear conversion paths
- ⚡ **Fast Loading** - Optimized CSS and assets
- 🔍 **SEO Friendly** - Proper meta tags and structure

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **Responsive Design** - Mobile-first approach
- **CSS Flexbox/Grid** - Modern layout techniques
- **JavaScript** (optional) - Interactive elements

## 📦 Installation

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, etc.)
- Git

### Setup

```bash
# Clone the repository
git clone https://github.com/dugo-codes/bestcoffee.git
cd bestcoffee

# Open with a local server (recommended)
python -m http.server 8000
# or
cd bestcoffee && python3 -m http.server

# Then open http://localhost:8000 in your browser

# Or simply open index.html in your browser
open index.html
```

## 🚀 Usage

### View Online
Visit the live site: [bestcoffee.com](#) (if deployed)

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Edit HTML/CSS files as needed
4. Refresh browser to see changes

## 📁 Project Structure

```
bestcoffee/
├── index.html                # Main HTML file
├── css/
│   ├── style.css            # Main stylesheet
│   ├── responsive.css       # Mobile styles
│   └── animations.css       # Animation effects
├── images/
│   ├── hero.jpg
│   ├── products/
│   │   ├── coffee-1.jpg
│   │   ├── coffee-2.jpg
│   │   └── coffee-3.jpg
│   ├── team/
│   └── testimonials/
├── assets/
│   └── fonts/
├── js/ (optional)
│   └── script.js            # Interactive features
├── README.md
└── .gitignore
```

## 🎨 Sections

### 1. Header/Navigation
- Logo and brand name
- Navigation menu
- Contact info

### 2. Hero Section
- Eye-catching banner image
- Company tagline
- Call-to-action button

### 3. About Section
- Company story
- Mission and values
- Why choose us

### 4. Products Section
- Featured coffee varieties
- Product cards with descriptions
- Pricing information

### 5. Services Section
- Café services
- Delivery options
- Special offers

### 6. Testimonials
- Customer reviews
- Star ratings
- Customer photos

### 7. Contact Section
- Contact form
- Location and hours
- Social media links

### 8. Footer
- Quick links
- Copyright info
- Newsletter signup

## 🎨 Customization

### Change Colors
Edit `css/style.css`:
```css
:root {
    --primary-color: #8B4513;      /* Brown coffee color */
    --secondary-color: #D2691E;    /* Chocolate */
    --text-color: #333;
    --bg-color: #fff;
}
```

### Update Content
Edit `index.html`:
- Change company name
- Update product descriptions
- Modify contact information
- Add/remove sections

### Add Images
1. Place images in `images/` folder
2. Update image paths in HTML
3. Optimize images for web

## 📱 Responsive Breakpoints

```css
/* Mobile */
@media (max-width: 480px) { }

/* Tablet */
@media (max-width: 768px) { }

/* Desktop */
@media (min-width: 1024px) { }

/* Large Desktop */
@media (min-width: 1440px) { }
```

## ✅ Best Practices Implemented

- ✓ Semantic HTML5 structure
- ✓ Mobile-first responsive design
- ✓ Optimized images
- ✓ Clean CSS organization
- ✓ Accessibility features
- ✓ Fast loading times
- ✓ SEO optimization
- ✓ Cross-browser compatibility

## 🚀 Deployment

### Deploy to GitHub Pages
```bash
# Push to main branch
git add .
git commit -m "Update site"
git push origin main

# Enable Pages in GitHub Settings
# Select main branch as source
```

### Deploy to Netlify
1. Connect GitHub repository
2. Set build command: (leave empty for static site)
3. Set publish directory: `/`
4. Deploy

### Deploy to Vercel
1. Import project from GitHub
2. Click deploy
3. Get live URL

## 🤝 Contributing

Contributions welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit (`git commit -m 'Add AmazingFeature'`)
5. Push (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Inspiration from coffee shop designs
- Icons and fonts from open-source libraries
- Community feedback and suggestions

---

**Made with ❤️ by [Dugo](https://github.com/dugo-codes)**

⭐ If you find this project helpful, please give it a star!
