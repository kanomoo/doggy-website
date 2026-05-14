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

## 🔧 Development Notes (Reorganization Update - May 2026)

The project structure has been organized to keep HTML files manageable:

- **Root Level**: Only `index.html` remains at the root for easy access.
- **Pages Directory**: All other pages are moved to `pages/`.
- **Sub-categorization**: Menus, reviews, and replies are further organized into subfolders.

### Pathing Guidelines
When adding or modifying links, ensure relative paths are correct:
- From **Root** to **Pages**: `pages/filename.html`
- From **Pages** to **Assets**: `../css/`, `../images/`, etc.
- From **Menu/Reviews** to **Root**: `../../index.html`
- From **Menu/Reviews** to **Assets**: `../../css/`, `../../images/`, etc.

---

**Last Updated:** 14 พฤษภาคม 2569 (หลังการจัดระเบียบไฟล์)

## สรุปการแก้ไขล่าสุด
- **จัดระเบียบไฟล์ HTML**: แยกไฟล์ลงในโฟลเดอร์ `pages/`, `pages/menu/`, `pages/reviews/`, และ `pages/replies/`
- **แก้ไข Path ทั้งระบบ**: ปรับลิงก์ Assets (CSS, JS, Images) และลิงก์นำทาง (Navigation) ทั้งหมดให้ทำงานได้ถูกต้องตามโครงสร้างใหม่
- **แก้ไขปุ่ม Add to Cart**: ซ่อมแซม Tag HTML ที่ผิดพลาดในหน้าเมนูทั้งหมด
- **แก้ไขระบบ Order**: ปรับ Form Action และ Layout ของ Cart Sidebar ให้รองรับโครงสร้างโฟลเดอร์ใหม่และแสดงผลสวยงามขึ้น
- **แก้ไขภาพหาย**: ตรวจสอบและซ่อมแซมเส้นทางรูปภาพในหน้ารีวิวและหน้าย่อยต่างๆ

---
