# 🐕 Doggy Website

A responsive static website dedicated to dogs, built with **HTML5**, **SCSS**, and **Vanilla JavaScript**. This front-end web development group project showcases modern web design principles with a dog-themed aesthetic.

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean and professional interface with smooth animations
- **Interactive Components** - Dynamic features using vanilla JavaScript
- **Product Showcase** - Menu, gallery, gift shop sections
- **User Engagement** - Contact forms, reviews, and newsletter subscription
- **Accessibility** - Semantic HTML5 and user-friendly navigation

## 🛠️ Tech Stack

- **HTML5** - Semantic structure
- **SCSS** - Advanced styling with Bootstrap framework
- **JavaScript** - Vanilla JS for interactivity (jQuery + plugins)
- **Bootstrap** - Responsive grid and components
- **jQuery** - DOM manipulation and animations

## 📂 Project Structure

```
doggy-website/
├── index.html              # Homepage
├── pages/                  # Main pages directory
│   ├── about.html          # About page
│   ├── gallery.html       # Image gallery
│   ├── contact.html       # Contact form
│   ├── giftshop.html      # Gift shop
│   ├── order.html         # Order page
│   ├── login.html         # Login page
│   ├── register.html      # Registration page
│   ├── menu/              # Menu categories (cake, coffee, etc.)
│   ├── reviews/           # Customer reviews (food, location, dog)
│   └── replies/           # Reply pages for reviews
├── css/                    # Stylesheets
├── js/                     # JavaScript files
├── images/                 # Image assets
├── fonts/                  # Font files
├── scss/                   # SCSS source files
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

## 🚀 Getting Started

### Option 1: Direct File Opening
Simply open `index.html` in your web browser:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option 2: Local Server (Recommended)
```bash
# Python 3
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

## 📋 Pages Available

| Page | Location | Description |
|------|----------|-------------|
| **Home** | `index.html` | Main homepage with hero section |
| **About** | `pages/about.html` | About the dog café and story |
| **Menu** | `pages/menu/` | Different menu categories (main, cake, drink, etc.) |
| **Gallery** | `pages/gallery.html` | Photo gallery |
| **Gift Shop** | `pages/giftshop.html` | Gift shop products |
| **Order** | `pages/order.html` | Order/booking system |
| **Contact** | `pages/contact.html` | Contact information |
| **Reviews** | `pages/reviews/` | Customer reviews (food, location, dog) |
| **Replies** | `pages/replies/` | Detailed replies for reviews |
| **Auth** | `pages/login.html` | Login & Register pages |

## 🎨 Customization

### Styling (SCSS)
The project uses SCSS for advanced styling. Main stylesheet is located at `scss/style.scss`. 

### JavaScript
Custom scripts are in `js/main.js`. The project uses jQuery and Bootstrap plugins for animations and responsive components.

## 🏗️ Project Organization (May 2026)

The project structure has been reorganized for better maintainability:

- **Root Level**: Only `index.html` remains at the root for easy access
- **Pages Directory**: All content pages are in `pages/` folder
- **Subfolders**: Menu categories, reviews, and replies are organized into dedicated subfolders

### 📐 Path Guidelines

When creating or modifying links, follow these pathing rules:

**From Root `index.html`:**
```
pages/filename.html              # Link to pages
pages/menu/menu-coffee.html      # Link to menu items
```

**From `/pages/` level pages (e.g., `contact.html`):**
```
../index.html                    # Link to root
./about.html                     # Link to sibling page
./menu/menu-cake.html            # Link to menu
../css/style.css                 # Link to CSS
../images/logo.png               # Link to images
```

**From nested pages (e.g., `pages/reviews/review-food.html`):**
```
../../index.html                 # Link to root
../contact.html                  # Link to pages-level file
./review-dog.html                # Link to sibling in same folder
../../css/style.css              # Link to CSS
../../images/gallery/pic.jpg     # Link to images
```

## 📝 Recent Updates

- **File Reorganization**: Separated HTML files into structured folders (`pages/`, `pages/menu/`, `pages/reviews/`, `pages/replies/`)
- **Link Normalization**: Fixed all CSS, JS, and image paths to match new structure
- **HTML Validation**: Corrected malformed HTML tags in menu pages
- **Order System**: Updated form actions and cart sidebar layout
- **Missing Images**: Verified and corrected image paths across review pages

---

**Last Updated:** May 14, 2026 (File reorganization completed)
