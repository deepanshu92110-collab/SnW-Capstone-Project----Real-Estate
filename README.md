# DealFree - Real Estate Website

## SNW Capstone Project - Phase 1

**Student Name:** Deepanshu  
**Subject:** SNW (Web Development)  
**Mentor:** Swati Priya Ma'am  
**Project Theme:** Real Estate  
**Reference Website:** NoBroker.in  
**Phase 1 Submission:** November 2025 (Mid Evaluation)  
**Phase 2 Submission:** December 2025 (Final Evaluation)

---

## 📋 Project Overview

DealFree is an interactive real estate website that enables users to browse properties, learn about services, and contact property owners directly - eliminating broker fees. This project showcases fundamental web development skills using **HTML5**, **CSS3**, and **Vanilla JavaScript**.

---

## ✨ Features

### 1. **Responsive Navigation Bar**
- Sticky navigation with smooth scrolling
- Links to all major sections
- Mobile-friendly design

### 2. **Hero Section**
- Eye-catching gradient background
- Property search box (UI only for Phase 1)
- Clear call-to-action

### 3. **Services Section**
- 4 core services: Buy, Rent, Sell, Consultation
- Card-based layout with icons
- Hover effects for better UX

### 4. **Featured Properties**
- 6 property listings with detailed cards
- Property images (gradient placeholders)
- Key details: Price, location, bedrooms, bathrooms, area
- "For Sale" and "For Rent" badges

### 5. **About Section**
- 4 key advantages of DealFree
- Clean card design with icons
- Highlights: Zero brokerage, verified listings, quick process, 24/7 support

### 6. **Testimonials**
- 3 customer reviews
- Gradient background for visual appeal
- Builds trust and credibility

### 7. **Contact Section**
- Contact information (email, phone, location)
- Contact form with validation attributes
- Responsive grid layout

### 8. **Footer**
- Quick links and services
- Professional multi-column layout
- Copyright notice with student credit

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup, forms, data attributes, accessibility
- **CSS3** - Flexbox, Grid, animations, gradients, transitions, media queries
- **JavaScript (ES6+)** - DOM manipulation, event handling, array methods, filtering, sorting
- **Google Fonts** - Poppins font family
- **Responsive Design** - Mobile-first approach

---

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Tablet:** 768px - 1199px
- **Mobile:** Below 768px
- **Small Mobile:** Below 480px

---

## 🎨 Design Highlights

### Color Scheme
- Primary: Blue gradient (`#2563eb` to `#764ba2`)
- Secondary: Dark slate (`#1e293b`)
- Accent: Light blue (`#0ea5e9`)
- Background: Clean white and light gray

### Key CSS Features
- CSS Variables for easy theme management
- Smooth scroll behavior
- Hover animations and transitions
- Box shadows for depth
- Gradient overlays
- Flexbox and CSS Grid for layouts

---

## 📂 Project Structure

```
dealfree-website/
│
├── index.html          # Home page with hero and quick info
├── services.html       # Services page with detailed offerings
├── properties.html     # Properties listing page
├── about.html          # About us page with company info
├── contact.html        # Contact page with form and FAQ
├── styles.css          # Complete CSS styling for all pages
└── README.md          # Project documentation (this file)
```

---

## 🌐 Website Pages

1. **Home (index.html)** - Hero section with search box and quick info
2. **Services (services.html)** - Detailed service offerings
3. **Properties (properties.html)** - Property listings for sale and rent
4. **About (about.html)** - Company information and testimonials
5. **Contact (contact.html)** - Contact form, information, and FAQ

---

## 🚀 How to Run

### Method 1: Direct Browser Opening
1. Download/clone the project folder
2. Open `index.html` in any modern web browser
3. Navigate to other pages using the navigation menu

### Method 2: Local Server (Recommended)
```bash
# Navigate to project directory
cd dealfree-website

# Start a local server (Python)
python3 -m http.server 8000

# Open in browser
# http://localhost:8000
```

All 5 pages are now accessible through the navigation menu.

---

## 📸 Pages Overview

1. **Home (index.html)** - Landing page with hero section and quick features
2. **Services (services.html)** - All services offered (Buy, Rent, Sell, etc.)
3. **Properties (properties.html)** - Complete property listings
4. **About (about.html)** - Company mission, vision, and achievements
5. **Contact (contact.html)** - Contact form, info, map, and FAQs

---

## 🎯 Learning Outcomes

Through this project, I have demonstrated:

✅ HTML5 semantic elements and data attributes  
✅ CSS3 advanced styling (Flexbox, Grid, animations, transitions)  
✅ Vanilla JavaScript DOM manipulation  
✅ Event handling and user interactions  
✅ Dynamic filtering and sorting algorithms  
✅ Responsive web design principles  
✅ Form design and validation  
✅ Modern UI/UX design patterns  
✅ Code organization and clean code practices  
✅ Cross-browser compatibility  

---

## ✅ Phase 2 - JavaScript Implementation (Completed)

Phase 2 has been successfully completed with the following JavaScript features:

### 1. **Login/Register Popup Modal (index.html)**
- Full-screen overlay with dark background
- Animated popup form with email validation
- Multiple close methods: X button, overlay click, Escape key
- Body scroll lock when popup is active
- Success alert on form submission

### 2. **Smooth Scroll Navigation (index.html)**
- Hero buttons converted to smooth scroll anchors
- "View Property" scrolls to services section
- "Contact Now" scrolls to footer
- Smooth `scrollIntoView()` animation

### 3. **Featured Properties Search & Filter (index.html)**
- Live property grid with 6 sample cards
- Real-time text search on property titles
- Multiple filter dropdowns: Type, Location, Amenities
- Data attributes for filtering logic
- Dynamic show/hide with CSS `.hidden` class

### 4. **Expandable Service Cards (services.html)**
- Click-to-expand accordion system for 6 service cards
- Rotating arrow indicators (▼ ↔ ▲)
- Smooth max-height transitions
- Hover effects on headers
- All service details collapsed by default

### 5. **Advanced Property Filtering (properties.html)**
- Comprehensive filter bar with:
  - Status filter (All/For Sale/For Rent)
  - City filter (Mumbai/Bangalore/Delhi/Hyderabad/Gurgaon)
  - Min/Max price range inputs
- Data attributes: `data-status`, `data-city`, `data-price`, `data-area`
- Auto-filter on dropdown change
- Reset button to clear all filters
- 9 properties with complete filtering support

### 6. **Property Sorting System (properties.html)**
- Toggle buttons for Price and Area sorting
- Dynamic switching between Low to High ↑ and High to Low ↓
- DOM reordering using `appendChild()`
- Preserves active filters while sorting
- Visual arrow indicators for sort direction

### JavaScript Techniques Implemented:
- DOM manipulation (`querySelector`, `classList`, `getAttribute`)
- Event handling (click, change, input, keydown events)
- Array methods (`Array.from()`, `forEach()`, `sort()`)
- Conditional filtering logic
- Dynamic content updates
- Smooth animations with CSS transitions
- Data attribute-based filtering

### CSS Enhancements Added:
- Auth popup overlay and modal styles
- Filter bar with styled inputs and dropdowns
- Sort bar with hover animations
- Expandable service card transitions
- Hidden utility class for filtering
- Responsive mobile layouts for all new features

**Total Lines of JavaScript:** 150+  
**New CSS Classes:** 12+  
**Interactive Elements:** 20+  
**Event Listeners:** 15+

---

## 📝 Notes for Evaluation

- This is a **Phase 2 submission** - HTML, CSS, and Vanilla JavaScript
- All code is written from scratch (no frameworks/libraries except Google Fonts)
- The website is fully responsive and tested on multiple devices
- Design inspired by NoBroker.in but created with original content and layout
- Follows web accessibility best practices
- Clean code without comments (as requested)
- All JavaScript features use vanilla ES6+ syntax
- No jQuery or external libraries used

---

## 🙏 Acknowledgments

- **Mentor:** Swati Priya Ma'am
- **Reference:** NoBroker.in
- **Fonts:** Google Fonts (Poppins)
- **Icons:** Emoji icons for simplicity
- **Images:** Gradient placeholders (Unsplash for hero background)

---

## 👨‍💻 Author

**Deepanshu**  
SNW Capstone Project  
Phase 1: November 2025  
Phase 2: December 2025

---

## 📞 Contact

For any queries regarding this project:
- Project Email: contact@dealfree.com
- Student: Deepanshu

---

**Thank you for reviewing my project! 🙏**
