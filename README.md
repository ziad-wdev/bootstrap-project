# 🍽️ FreshFlavor — Restaurant Website

A fully responsive, single-page restaurant website built with **Bootstrap 5**. FreshFlavor showcases a modern food-service landing page with a rich set of UI components — from a full-screen hero carousel to interactive menus, customer reviews, chef profiles, and more.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-7952B3?style=flat&logo=bootstrap&logoColor=white)

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [Author](#author)

---

## About the Project

FreshFlavor is a static front-end website for a fictional restaurant. It demonstrates real-world usage of Bootstrap 5 components alongside custom CSS animations and vanilla JavaScript. The project is ideal as a learning reference for Bootstrap layouts, or as a starting template for any food & beverage business website.

---

## Features

- **Full-screen hero carousel** — auto-playing slideshow for featured menu categories (Pizza, Burger, Salad, Chicken)
- **Sticky navigation bar** — responsive navbar with dropdown menu, search input, and a login modal
- **Fixed social sidebar** — quick-access social media links anchored to the viewport edge
- **Accordion menu** — collapsible sections detailing signature menu items with descriptions
- **Nutrition & dietary details** — tabbed content with star ratings and customer review cards
- **Customer favorites grid** — 8 dish cards with hover animations
- **Parallax background sections** — full-bleed background images with a parallax scroll effect
- **Chef profiles** — card-style bios for the culinary team
- **Blog / stories section** — news and update cards with slanted image clips
- **Social subscription section** — animated cards linking to social media channels
- **Responsive footer** — contact info, quick links, and brand promise columns
- **Copy-button tooltip** — JavaScript-powered feedback on copy actions
- **Fully responsive** — adapts gracefully from mobile to desktop using Bootstrap's grid

---

## Tech Stack

| Technology                                                        | Version | Delivery        |
| ----------------------------------------------------------------- | ------- | --------------- |
| [Bootstrap](https://getbootstrap.com/)                            | 5.3.8   | CDN             |
| [Font Awesome](https://fontawesome.com/)                          | 6.x     | Bundled locally |
| [Google Fonts — Roboto](https://fonts.google.com/specimen/Roboto) | latest  | CDN             |
| HTML5 / CSS3 / JavaScript (ES6+)                                  | —       | Local files     |

> No build tools, package managers, or server-side dependencies are required.

---

## Project Structure

```
bootstrap-project/
├── index.html          # Main (and only) HTML page
├── css/
│   ├── all.css         # Bundled Font Awesome stylesheet
│   └── style.css       # Custom styles & animations
├── src/
│   └── script.js       # Vanilla JS (copy-button tooltip logic)
├── images/             # All image assets (dishes, carousel, logos, chef photos)
└── webfonts/           # Font Awesome web font files (.woff2)
```

---

## Getting Started

### Prerequisites

All you need is a modern web browser — no Node.js, Python, or any other runtime is required.

### Installation

1. **Clone the repository**

   ```sh
   git clone https://github.com/<your-username>/bootstrap-project.git
   ```

2. **Navigate into the project folder**

   ```sh
   cd bootstrap-project
   ```

3. **Open the site**

   Simply open `index.html` in your browser:

   ```sh
   # macOS
   open index.html

   # Linux
   xdg-open index.html

   # Windows
   start index.html
   ```

   Or drag and drop `index.html` into any browser window.

> **Note:** An active internet connection is required on first load to fetch Bootstrap and Google Fonts from their respective CDNs. Font Awesome is bundled locally and works offline.

---

## Usage

The entire site lives in a single `index.html` file. Here's a quick map of the main sections and where to find them:

| Section                  | What to edit                         | File                  |
| ------------------------ | ------------------------------------ | --------------------- |
| Navigation & Login Modal | `<header>` → `<nav>` / `#loginModal` | `index.html` L34–113  |
| Hero Carousel            | `#mainCarousel`                      | `index.html` L143–217 |
| Welcome blurb            | First `<section>` after `<main>`     | `index.html` L219–227 |
| Accordion Menu           | `#accordion`                         | `index.html` L231–279 |
| Nutrition & Reviews      | Sections with star ratings           | `index.html` L283–411 |
| Customer Favorites       | Dish card grid                       | `index.html` L428–540 |
| Chef Profiles            | `.custom-card` section               | `index.html` L555–610 |
| Blog / Stories           | `.clip-slant-*` section              | `index.html` L612–748 |
| Social Subscribe         | Social card grid                     | `index.html` L750–790 |
| Footer                   | `<footer>`                           | `index.html` L792–828 |

### Customising styles

All custom CSS lives in `css/style.css`. The file is intentionally small — Bootstrap handles the heavy lifting. Key custom classes include:

- `.card-hover` — diagonal shine animation on card hover
- `.custom-card` — background-image card that scales down on hover
- `.clip-slant-right` / `.clip-slant-left` — diagonal clip-path for blog post images
- `.social-card` — subtle scale-up effect on social subscription cards

---

## Contributing

Contributions are welcome! To propose a change:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "feat: describe your change"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a Pull Request against `main`

Please keep pull requests focused — one feature or fix per PR makes review much easier.

---

## Author

**Eng. Ziad Aboughaleb**

> © 2025 FreshFlavor. All Rights Reserved.
