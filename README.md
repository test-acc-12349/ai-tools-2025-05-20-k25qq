# AI Tools Directory 🤖

> The ultimate curated collection of AI tools and resources in a sleek, searchable directory.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Support](#support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources. Built with HTML5, CSS3, and JavaScript, it features a clean 3-column grid layout with filtering capabilities and smooth animations.

## Features

- 🔍 Real-time search functionality
- 📱 Responsive 3-column grid layout
- 🏷️ Category-based filtering
- ⚡ Fast loading and performance
- 🎨 Customizable styling
- 🔧 Easy to maintain and update

## Getting Started

### Prerequisites
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS
- Git installed on your machine

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Open index.html in your browser
```

## Directory Structure

```
ai-tools-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   └── directory-items.json
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "title": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

1. Open `index.html`
2. Locate the category section:

```html
<div class="categories">
  <button class="category-btn active" data-category="all">All</button>
  <button class="category-btn" data-category="chatbots">Chatbots</button>
  <!-- Add more categories here -->
</div>
```

### Customizing Colors

1. Open `assets/css/style.css`
2. Modify the CSS variables:

```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --text-color: #333333;
  --background-color: #ffffff;
}
```

### Updating Hero Section

1. Open `index.html`
2. Locate the hero section:

```html
<section class="hero">
  <h1>AI Tools Directory</h1>
  <p>Your tagline here</p>
</section>
```

## Deployment

### GitHub Pages
1. Go to repository settings
2. Navigate to "Pages"
3. Select main branch
4. Save changes

### Netlify
1. Connect your GitHub repository
2. Select main branch
3. Deploy

## Custom Domain Setup

1. Purchase domain from registrar
2. Add custom domain in deployment platform
3. Configure DNS settings:
```
A     @     76.76.21.21
CNAME www   yourdomain.netlify.app
```

## Troubleshooting

### Common Issues

**Images not loading**
- Check file paths
- Verify image formats
- Ensure proper permissions

**Search not working**
- Check browser console for errors
- Verify JavaScript is enabled
- Clear browser cache

## Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## Support

- 📧 Email: support@aitools.com
- 💬 Discord: [Join our community](https://discord.gg/aitools)
- 📚 Documentation: [Wiki](https://github.com/yourusername/ai-tools-directory/wiki)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name]