# Savanna Grill — Restaurant Website

A multi-page restaurant website built as a front-end web development course project. 
The site represents a fictional fine dining restaurant based in Nairobi, Kenya, 
that reimagines classic Kenyan dishes with modern culinary techniques.

---

## Overview

Savanna Grill is a 4-page static website built with HTML5 and CSS3. 
The project covers core front-end concepts including semantic HTML structure, 
Flexbox and Grid layouts, responsive design, and consistent multi-page navigation.

---

## Project Structure

week-1-restaurant-website/
├── index.html          # Home page
├── menu.html           # Menu page
├── about.html          # About page
├── contact.html        # Contact page
├── css/
│   └── styles.css      # All styles including responsive breakpoints
├── images/
│   └── (placeholder)   # Folder reserved for real photos
└── README.md           # Project documentation

---

## Technologies Used

- **HTML5** — Semantic page structure across 4 pages
- **CSS3** — Styling, layout, and responsive design
- **Flexbox** — Used for navbar, dish cards, menu items, team grid, and feature sections
- **CSS Grid** — Used for the footer three-column layout
- **Google Fonts** — Playfair Display (headings) and Inter (body text)
- **Google Maps** — Embedded iframe on the Contact page

---

## Pages & Features

### Home (`index.html`)
- Sticky navigation bar with active link highlighting
- Full-width hero section with background image, restaurant name, tagline, and CTA button
- Featured Dishes section with 3 dish cards (image, name, description)
- Why Savanna Grill section with 3 feature cards
- Footer with address, opening hours, quick links, and social media

### Menu (`menu.html`)
- 4 menu categories: Breakfast, Lunch, Dinner, Drinks
- 18 menu items each with name, description, and price in KES
- Alternating section backgrounds for visual separation
- Item layout with name/description on the left and price on the right

### About (`about.html`)
- Two-column layout with restaurant story and interior image
- Values section with 3 cards on a dark background
- Meet the Team section with 3 team member cards (photo, name, role, bio)

### Contact (`contact.html`)
- Contact details: address, phone, and email
- Opening hours displayed in a clean table format
- Contact form with Name, Email, Phone, Message fields and a Submit button
- Embedded Google Map showing the Kilimani area of Nairobi

---

## Responsive Design

The site is fully responsive across three breakpoints:

| Breakpoint | Width         | Behaviour                              |
|------------|---------------|----------------------------------------|
| Desktop    | Above 1024px  | Full multi-column layouts              |
| Tablet     | 768px–1024px  | Reduced padding, footer reflows        |
| Mobile     | Below 768px   | All columns stack vertically           |

---

## How to Run & Test

### Opening the site
1. Download or clone the project folder
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No build tools, servers, or installations required — it runs entirely in the browser

### Testing navigation
- Click every link in the navbar and confirm it takes you to the correct page
- Confirm the active link is visually highlighted on each page
- Click the footer quick links and confirm they work from every page

### Testing responsiveness
**Option 1 — Browser DevTools:**
1. Open the site in Chrome or Firefox
2. Press `F12` to open DevTools
3. Click the device toolbar icon (or press `Ctrl + Shift + M`)
4. Select a device preset (iPhone, iPad) or drag the viewport width manually
5. Check all 4 pages at mobile and tablet sizes

**Option 2 — Resize the browser window:**
1. Drag the browser window narrower and watch the layout reflow
2. Check that nothing overflows or breaks below 768px

### Things to check on each page
- [ ] Navbar brand is on the left, links are on the right
- [ ] Active nav link is highlighted on the correct page
- [ ] Hero image and overlay display correctly
- [ ] All dish card images load
- [ ] Menu items show name/description left, price right
- [ ] About page story and image sit side by side on desktop
- [ ] Team cards display in a row on desktop, stack on mobile
- [ ] Contact form fields are labelled and aligned
- [ ] Google Map iframe loads on the Contact page
- [ ] Footer displays in 3 columns on desktop, stacks on mobile

---

