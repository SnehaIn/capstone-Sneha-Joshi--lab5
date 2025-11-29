# FoodiesHub – Food Delivery Landing Page

A responsive single-page Food Delivery website built as a Web Dev I Lab capstone project using only HTML5 and CSS3. The page showcases a modern UI for browsing popular dishes, viewing deals, and contacting support.

---

## Project Title & Theme

- **Title:** FoodiesHub – Food Delivery Landing Page  
- **Theme:** Food Delivery App (menu page with featured items, category filters, deals, and contact support)

---

## Sections Implemented

1. **Header & Navigation (`<header>`, `<nav>`):**  
   Logo and primary navigation links for Home, Menu, Deals, and Contact sections.

2. **Hero Section (`<section id="hero">`):**  
   Two-column layout with main headline, supporting text, and primary/secondary call-to-action buttons, plus a hero food image.

3. **Popular Dishes / Menu (`<section id="menu">`):**  
   Section heading and description, category filter chips (All, Pizza, Burgers, Biryani, Desserts), and a responsive card grid of food items with images, descriptions, prices, and “Add to cart” buttons.

4. **Today’s Deals (`<section id="deals">`):**  
   Highlighted combo offers displayed as cards with images, short text, and pricing.

5. **Contact & Order Support (`<section id="contact">`):**  
   Contact form with labeled fields (name, phone, email, order ID, message) and a submit button, plus a support-information panel with phone, email, and service hours.

6. **Footer (`<footer>`):**  
   Simple footer containing copyright text for the FoodiesHub brand.

---

## Breakpoints Used

The site is responsive using CSS media queries:

- **Desktop:**  
  - Default layout with two-column hero section and a 3-column card grid for menu and deals.
- **Tablet (max-width: 1024px):**  
  - Hero section adjusts column widths.  
  - Card grid switches to **2 columns** for better readability.
- **Mobile (max-width: 768px):**  
  - Hero section stacks into a **single column** (image and text stacked).  
  - Navigation menu is hidden for a cleaner top bar (can be replaced by mobile menu in future).  
  - Card grid switches to a **single column** for full-width cards.  
  - Contact section stacks form and info vertically.

---

## Main Layout Techniques

- **Semantic HTML5 structure:** `header`, `nav`, `main`, `section`, `article`, and `footer` elements for clear document structure.  
- **CSS Flexbox:**  
  - Used for header alignment (logo and nav), hero action buttons, and metadata rows inside cards.  
- **CSS Grid:**  
  - Used for the hero two-column layout and for the responsive card grids in the Menu and Deals sections.  
- **Responsive Design:**  
  - Implemented using `@media` queries at `1024px` and `768px` to adjust columns, stacking, and navigation behaviour.  
- **Visual Design:**  
  - CSS custom properties (variables) for colors, spacing, and typography.  
  - Rounded cards, drop shadows, hover states on buttons/cards, and chip-style category filters.

---

## How to Open the Project

### Option 1 – Open Locally

1. Download or clone this repository.  
2. Ensure all images are in the same folder structure as in the code.  
3. Open the file `index.html` in any modern web browser (Chrome, Edge, Firefox, etc.).  
4. No additional server or dependencies are required (pure HTML + CSS).

### Option 2 – View on GitHub Pages (optional)

If GitHub Pages is enabled for this repo:

- **Live demo:** `https://github.com/SnehaIn/capstone-Sneha-Joshi--lab5 `
