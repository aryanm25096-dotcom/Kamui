# KAMUI

KAMUI is an 18-page, scroll-driven website built entirely from scratch with **HTML** and **CSS**. It features complex pure-CSS illustrations, layouts, typography systems, and interaction effects without relying on any external images or JavaScript libraries.

## 🚀 Features

* **Scroll-Driven Hero Sequence:** A dynamic opening animation where a CSS-drawn house rises, a portrait frame expands to full-screen, and a pathway widens into the foreground—all triggered by user scroll.
* **100% CSS Illustrations:** 
  * The house illustration and pathway
  * Dashboard Data Visualizations (Line graphs, bar charts, donut charts)
  * Design Tool Icons (Terminal, Browser, Folder, Code Brackets, Pencil, Layers)
  * Apple Studio Display Mockup
  * Custom geometric KAMUI logo
  * Social Media Icons
* **Global Liquify Effect:** An SVG turbulence filter applied globally that dynamically distorts the entire webpage based on mouse movement, simulating a liquid environment.
* **Custom Cursor:** A dual-element custom cursor with trailing interactions and click ripple effects.
* **Typography & Color Systems:** Showcases dynamic font scaling (Bebas Neue and Shippori Mincho), color tint generation, and comprehensive brand identity layouts.

## 🛠 Tech Stack

* **HTML5** (Semantic structure)
* **CSS3** (Variables, Grid, Flexbox, custom shapes using borders/gradients/clip-path)
* **Vanilla JavaScript** (Only used to bind scroll progress to CSS variables and map cursor coordinates to the SVG filter)
* **Zero Images:** No JPGs, PNGs, or external SVGs are used for visual content.

## 💻 Structure

The project consists of two core files:
* `index.html`: Contains the structural markup for all 18 sections (`<section id="page1">` to `page18`).
* `style.css`: Contains the entire design system, variables (`--purple`, `--red`, `--ink`, etc.), layout grids, and the mathematical CSS drawing logic for all shapes and icons.

## 🎨 Design Philosophy

KAMUI emphasizes striking digital architecture, generous whitespace, and high-contrast editorial design. The lack of standard imagery forces a creative reliance on raw CSS to generate premium, engaging visual experiences.
