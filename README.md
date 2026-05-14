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
├── about.html              # About page
├── menu-*.html            # Menu pages (coffee, drink, cake, etc.)
├── gallery.html           # Image gallery
├── contact.html           # Contact form
├── order.html             # Order page
├── review-*.html          # Review pages
├── css/
│   ├── style.css          # Main stylesheet
│   ├── bootstrap/         # Bootstrap utilities
│   └── (other vendor CSS)
├── js/
│   ├── main.js            # Custom JavaScript
│   ├── jquery-*.js        # jQuery and plugins
│   └── (other vendor JS)
├── images/                # Image assets organized by category
├── fonts/                 # Font files
├── scss/                  # SCSS source files
├── README.md              # This file
└── .gitignore             # Git ignore rules
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

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if available)
npx http-server
```
Then open http://localhost:8000 in your browser.

## 📋 Pages Available

| Page | Description |
|------|-------------|
| `index.html` | Main homepage with hero section |
| `about.html` | About the dog café and story |
| `menu-*.html` | Different menu categories |
| `gallery.html` | Photo gallery |
| `giftshop.html` | Gift shop products |
| `order.html` | Order/booking system |
| `contact.html` | Contact information |
| `review-*.html` | Customer reviews |
| `login.html` | Login page |
| `register.html` | Registration page |

## 🎨 Customization

### Styling (SCSS)
The project uses SCSS for advanced styling. Main stylesheet is located at `scss/style.scss`. Build SCSS to CSS using:
```bash
# Using Prepros (included in config)
# Or use your own SCSS compiler
```

### JavaScript
Custom scripts are in `js/main.js`. The project uses:
- jQuery for DOM manipulation
- Bootstrap for responsive components
- Custom vanilla JavaScript for specific features

## 📸 Key Sections

- **Header/Navigation** - Main menu and branding
- **Hero Section** - Eye-catching banner
- **Service Showcase** - Featured offerings
- **Menu Display** - Product listings
- **Gallery** - Image portfolio
- **Reviews** - Customer testimonials
- **Contact Section** - Location and inquiry form
- **Footer** - Links and information

## 🔧 Development Notes

### Adding New Pages
1. Create a new `.html` file
2. Include common header and footer
3. Link stylesheets and scripts
4. Update navigation menus

### Adding Images
Place images in the appropriate subfolder under `/images`:
- Gallery images → `/images/gallery/`
- Menu items → `/images/mainmenu/`, `/images/coffee/`, etc.
- Product photos → Organize by category

### Modifying Styles
1. Edit SCSS files in `/scss/`
2. Compile to CSS
3. Or directly edit `/css/style.css`

## 📌 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ✅ Best Practices Implemented

- Semantic HTML5 markup
- Mobile-first responsive design
- Organized file structure
- Modular SCSS architecture
- Optimized images
- Clean and readable code

## 👥 Team Contribution

This is a collaborative group project created as part of a web development fundamentals course. Each team member contributed to:
- HTML structure and pages
- SCSS styling and design
- JavaScript functionality
- Image assets and content

## 📄 License

This project is for educational purposes.

## 🎯 Future Improvements

- [ ] Implement backend functionality
- [ ] Add form validation and submission
- [ ] Optimize image loading
- [ ] Improve performance metrics
- [ ] Add dark mode option
- [ ] Implement SEO best practices

---

**Last Updated:** May 2026

## หมายเหตุการแก้ไขที่ทำในไฟล์ index.html
- แก้ปุ่ม "Add to cart" ที่ปิดด้วยแท็กผิด (</a>) เป็น </button> เพื่อให้ HTML ถูกต้องและปุ่มทำงานได้
- ปรับ path รูปที่มีช่องว่างให้เป็น quoted URL (ตัวอย่าง: 'images/cake/Chocolate Lava Cakes.jpg')
- เพิ่ม overlay element:
  - <div id="offcanvasOverlay" class="offcanvas-overlay" onclick="closeSidebar()"></div>
  เพื่อให้ overlay ด้านหลังทำงานเมื่อเปิด sidebar
- ปรับสคริปต์ openSidebar/closeSidebar ให้เช็คการมีอยู่ของ element ก่อนเรียก classList เพื่อป้องกัน error ถ้า element ยังไม่อยู่ใน DOM

---

## แนะนำการปรับแต่งสั้นๆ
- เพิ่ม/แก้ไขเมนู: แก้ใน index.html ที่บล็อกเมนู (div class="block-7")
- เปลี่ยนสไตล์: แก้ css/style.css
- เชื่อม backend: เปลี่ยนปุ่มหรือฟอร์มเป็นการ POST ไปยัง API ของคุณ

---
