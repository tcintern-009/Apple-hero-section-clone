# Apple Homepage Clone

A responsive clone of the Apple.com homepage built using HTML & CSS. This project focuses on advanced CSS techniques including Flexbox, Grid, Positioning, Media Queries, and Transition effects.

## 🚀 Live Demo

Open `HTML/index.html` in any modern browser to view the project.

## 📁 Project Structure

```
├── HTML/
│   └── index.html          # Main HTML file
├── CSS/
│   ├── navbar.css          # Navigation bar styles (Flexbox)
│   ├── hero.css            # Hero section styles (Flexbox + Positioning)
│   ├── features.css        # Features grid styles (CSS Grid)
│   └── footer.css          # Footer styles (Flexbox)
├── assets/                 # Image assets (img1.jpg to img7.jpg)
├── README.md
```

## 🎯 CSS Concepts Practiced

### 1. **CSS Flexbox** — Used in:

- **Navbar** (navbar.css): Horizontal layout of nav items using `display: flex` with `justify-content: space-between` and `align-items: center`.
- **Hero Section** (hero.css): Centering content vertically and horizontally in hero containers.
- **Footer** (footer.css): Horizontal footer links with `flex-wrap: wrap` for responsive wrapping.

### 2. **CSS Grid** — Used in:

- **Features Section** (features.css): Two-column grid layout using `display: grid; grid-template-columns: 1fr 1fr` for product feature cards. On mobile, it collapses to a single column.

### 3. **Positioning** — Used in:

- **Navbar**: Fixed positioning (`position: fixed`) to keep the navigation bar at the top during scroll.
- **Hero & Feature Cards**: Relative positioning on containers, absolute positioning on background images to layer content on top.

### 4. **Responsive Design (Media Queries)** — Used in:

- **734px breakpoint**: Mobile layouts — hamburger menu visible, single column grid, smaller font sizes, vertical link layouts.
- **768px breakpoint**: Mobile navigation adjustments.
- **1068px breakpoint**: Tablet adjustments — reduced font sizes and card heights.

### 5. **Transitions & Hover Effects** — Used in:

- Navbar links: Smooth color transitions on hover.
- Feature cards: Scale transform (`scale(1.01)`) and box-shadow on hover.
- Hero links: Arrow icon sliding (`translateX(4px)`) and underline on hover.
- Footer links: Color transitions.

## 🛠️ Technologies Used

- **HTML5** — Semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS3** — Flexbox, Grid, Positioning, Media Queries, Transitions
- **No frameworks** — Pure CSS only

## 📸 Image Assets

Place your images in the `assets/` folder with the following names:

- `img1.jpg` — iPhone 16 Pro (Hero)
- `img2.jpg` — iPhone 16 (Secondary Hero)
- `img3.jpg` — MacBook Air
- `img4.jpg` — iPad Pro
- `img5.jpg` — Apple Watch
- `img6.jpg` — AirPods Pro
- `img7.jpg` — Apple Trade In

## 🧠 What I Learned

1. **Breaking CSS into modular files** improves maintainability and makes it easier to locate and update specific styles.
2. **CSS Grid** is ideal for 2D layouts like product grids, while **Flexbox** excels at 1D layouts like navigation bars and centering.
3. **Fixed positioning** with `backdrop-filter: blur()` creates Apple-like translucent navbars.
4. **Media queries** at multiple breakpoints (734px, 768px, 1068px) ensure a smooth responsive experience across devices.
5. **Hover transitions** add polish and make the interface feel interactive and engaging.
