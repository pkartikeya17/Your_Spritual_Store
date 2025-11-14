# YourSpiritualStore - Premium Shopify Theme

A modern, responsive Shopify theme featuring dark/light mode switching and AI chatbot integration.

## Features

- **Modern Design**: Clean, premium UI with elegant typography
- **Dark/Light Mode**: Seamless theme switching with localStorage persistence
- **AI Chatbot**: Integrated Gemini-powered chatbot for customer support
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Product Reels**: Instagram-style product showcase
- **Smooth Animations**: Professional transitions and hover effects
## ✨ Features

### Core Features
- 🌓 **Dark/Light Mode Toggle** - Seamless theme switching with localStorage persistence
- 🤖 **AI-Powered Chatbot** - Integrated Google Gemini chatbot for customer support
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern Design** - Clean, premium UI with elegant typography
- ⚡ **Performance Optimized** - Lazy loading, efficient code, fast load times

### E-commerce Features
- 🛍️ **Product Reels** - Instagram-style product showcase
- 🛒 **Cart Functionality** - Smooth add-to-cart with notifications
- 🔍 **Product Search** - Quick product discovery
- 💳 **Payment Ready** - Ready for Shopify payment integration
- 📦 **Shipping Info** - Clear shipping and delivery information

### Technical Features
- 🎯 **Clean Code Architecture** - Modular, maintainable codebase
- 🔧 **Custom Settings** - Easy theme customization via Shopify admin
- 🌐 **SEO Optimized** - Proper meta tags and structured data
- ♿ **Accessibility** - WCAG compliant with proper ARIA labels
- 🎨 **CSS Custom Properties** - Easy color and style customization

## 🛠️ Technologies Used

- **Shopify Liquid** - Template engine
- **JavaScript (ES6+)** - Modern vanilla JS, no frameworks
- **CSS3** - Custom properties, Grid, Flexbox
- **Google Gemini AI** - AI chatbot integration
- **REST API** - Shopify Cart API integration

## 📁 Project Structure
mysticaura/
├── assets/
│   ├── base.css           # CSS variables and resets
│   ├── theme.css          # Main theme styles
│   ├── theme.js           # Core JavaScript functionality
│   ├── chatbot.js         # AI chatbot implementation
│   └── global.js          # Utility functions
├── config/
│   └── settings_schema.json  # Theme settings configuration
├── layout/
│   └── theme.liquid       # Main layout template
├── sections/
│   ├── header.liquid      # Header with navigation
│   ├── footer.liquid      # Footer with links
│   ├── hero.liquid        # Hero section
│   └── featured-products.liquid  # Product showcase
├── snippets/
│   ├── chatbot.liquid     # Chatbot widget
│   ├── product-card.liquid  # Product card component
│   └── meta-tags.liquid   # SEO meta tags
├── templates/
│   ├── index.liquid       # Homepage
│   ├── collection.liquid  # Collection pages
│   ├── product.liquid     # Product pages
│   └── page.liquid        # Static pages
├── .gitignore
├── package.json
└── README.md


## Products

This theme is designed to showcase:

1. **7 Horses on Raw Pyrite Frame** - Vastu remedy for prosperity
2. **Dhan Yog Bracelet** - Wealth and abundance bracelet

## Pages

- Home
- Shop/Collections
- Product Pages
- About Us
- Contact
- Privacy Policy
- Refund Policy
- Terms of Service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

Edit CSS variables in `assets/base.css`:

```css
:root {
  --color-bg: #ffffff;
  --color-text: #1a1a1a;
  --color-accent: #8b7355;
}
```

### Adding Products

1. Go to Products > Add product
2. Fill in product details
3. Add images (recommended size: 800x800px)
4. Add to collections

### Chatbot Responses

Edit `assets/chatbot.js` to customize bot responses:

```javascript
getMockResponse(userMessage) {
  // Add custom responses here
}
```

## Support

For theme support and customization requests, please contact the developer.

## Credits

- Icons: Lucide Icons (inline SVG)
- Fonts: System fonts for optimal performance
- AI: Google Gemini API

## License

This theme is proprietary. Unauthorized distribution is prohibited.

---

Made with ❤️ 