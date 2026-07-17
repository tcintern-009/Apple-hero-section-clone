# Apple Homepage Clone

A responsive clone of the Apple.com homepage built using HTML & CSS. This project focuses on advanced CSS techniques including Flexbox, Grid, Positioning, Media Queries, and Transition effects.

## Live Demo

Open `HTML/index.html` in any modern browser to view the project.

## Project Structure

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

## CSS Concepts Practiced

### 1. **CSS Flexbox** Used in:

- **Navbar** (navbar.css): Horizontal layout of nav items using `display: flex` with `justify-content: space-between` and `align-items: center`.
- **Hero Section** (hero.css): Centering content vertically and horizontally in hero containers.
- **Footer** (footer.css): Horizontal footer links with `flex-wrap: wrap` for responsive wrapping.

### 2. **CSS Grid** Used in:

- **Features Section** (features.css): Two-column grid layout using `display: grid; grid-template-columns: 1fr 1fr` for product feature cards. On mobile, it collapses to a single column.

### 3. **Positioning** Used in:

- **Navbar**: Fixed positioning (`position: fixed`) to keep the navigation bar at the top during scroll.
- **Hero & Feature Cards**: Relative positioning on containers, absolute positioning on background images to layer content on top.

### 4. **Responsive Design (Media Queries)** Used in:

- **734px breakpoint**: Mobile layouts — hamburger menu visible, single column grid, smaller font sizes, vertical link layouts.
- **768px breakpoint**: Mobile navigation adjustments.
- **1068px breakpoint**: Tablet adjustments — reduced font sizes and card heights.

### 5. **Transitions & Hover Effects** — Used in:

- Navbar links: Smooth color transitions on hover.
- Feature cards: Scale transform (`scale(1.01)`) and box-shadow on hover.
- Hero links: Arrow icon sliding (`translateX(4px)`) and underline on hover.

## Technologies Used

- **HTML5** — Semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS3** — Flexbox, Grid, Positioning, Media Queries, Transitions


## What I Learned

1. **Breaking CSS into modular files**
2. **CSS Grid**
3. **Fixed positioning**
4. **Media queries**
5. **Hover transitions**
