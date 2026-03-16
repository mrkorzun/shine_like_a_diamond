# 💎 Handmade Jewelry Website — "Shine Like a Diamond"

[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/)
[![Agile](https://img.shields.io/badge/Agile-0052CC?style=for-the-badge&logo=jira&logoColor=white)](https://www.atlassian.com/agile)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)
[![Project Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/mrkorzun/shine_like_a_diamond)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## 📌 Project Overview

**Shine bright like a diamond** — a responsive landing page for a handmade jewelry brand. <br>
The website presents the brand story, key benefits, product gallery, testimonials, and <br> a contact section to increase customer trust and support inquiries.

**Timeline:** 1 week  
**Format:** Team project (BloomingGems)

---

## 🔗 Live Demo
🚀 **[Explore the Live Website](https://mrkorzun.github.io/shine_like_a_diamond/)**

---

## ✅ Functionality

- Responsive layout (mobile / tablet / desktop)
- Optimized images (including responsive `1x/2x`)
- Navigation (including burger menu)
- Brand information (About Us)
- Benefits section
- Product gallery
- Testimonials section
- Contact form + social links
- Favicon and SVG sprite icons

## ✨ Key Features & Technical Highlights

- **Mobile-First Responsive Design:** Seamless experience across mobile, tablet, and desktop devices using flexible layouts and media queries.
- **Performance Optimization:**
  - Implemented `fetchpriority="high"` for LCP (Largest Contentful Paint) images in the Hero section.
  - Used responsive images with `1x/2x` descriptors for Retina displays.
  - Optimized SVG icons using a unified **SVG Sprite** system.
- **Clean & Semantic Code:** Strictly followed HTML5 semantic standards to ensure accessibility (A11y) and SEO friendliness.
- **Modern CSS Architecture:**
  - Modular CSS structure for better maintainability.
  - Refactored media queries for improved readability and reduced specificity issues.
- **Interactive UI:** Smooth transitions, hover effects, and a functional contact form interface.

---

## 👤 My Contributions ([Romario Korzun](https://github.com/mrkorzun))

As a developer on this project, I was responsible for the full implementation of the **Header** and **Hero** sections — the core entry experience of the website.

### 🔧 Header & Navigation
- Implemented a **sticky header** with fixed positioning and a responsive navigation menu with anchor links.
- Added a **logo as an SVG link** and an "Order Now" button with hover/focus effects.
- Implemented **smooth scrolling** for all internal navigation links.

### 📱 Mobile Burger Menu
- Built a **full-screen mobile overlay menu** with burger/close buttons for screens up to 768px.
- Implemented smooth open/close **animations** using `cubic-bezier(0.4, 0, 0.2, 1)` transitions.
- Solved a "ghost menu" issue where the overlay was blocking the header on tablet/desktop — fixed with explicit `display: none` in media queries.
- Resolved **CSS specificity conflicts** between mobile menu and main header styles by prefixing selectors with `.mobile-menu`.

### 🖼 Hero Section
- Implemented the Hero section using a **mobile-first approach** with breakpoints at `768px` and `1440px`.
- Used `image-set()` to support modern image formats: **AVIF**, **WebP**, with JPEG as a fallback.
- Added **Retina (@2x) support** for mobile, tablet, and desktop versions.
- Moved `background-image` from `.hero` to `.hero-container` following team lead feedback for better layout control.

### ⚡ Performance & Refactoring
- Added `fetchpriority="high"` and `preload` link for the hero image to optimize **LCP (Largest Contentful Paint)**.
- Migrated static `<button>` elements to semantic `<a>` links where appropriate.
- Refactored media queries and removed redundant CSS properties (e.g., `cursor: pointer` on links).
- Fixed responsive font sizes and `max-width` for hero text across all breakpoints.

---

## 👥 The Team: BloomingGems

We practiced **Agile/Scrum** methodologies, including daily stand-ups and mandatory **Code Reviews** via Pull Requests to ensure high code quality.

- **[Dmytro Levchenko](https://github.com/d-levchenko)** — **Team Lead** (About Us, Final Build, Tech Support)
- **[Viktoriia Dmytryk](https://github.com/viktoriia-dmytryk)** — **Scrum Master** (Benefits, Responsive Images, Presentation)
- **[Romario Korzun](https://github.com/mrkorzun)** — **Developer** (Header, Hero, Burger Menu, Project Naming)
- **[Ivan Alekseev](https://github.com/IvanAlekseev45)** — **Developer** (Gallery)
- **[Vladyslav Daletskyi](https://github.com/daletskyiv)** — **Developer** (Testimonials)
- **[Yuliia Babaieva](https://github.com/JulieBabaeva)** — **Developer** (Contacts)
- **[Alona Shykova](https://github.com/Tigra26)** — **Developer** (Footer, SVG Assets, Team Naming)
---
## 🛠 Tech Stack

- **Bundler:** [Vite](https://vitejs.dev/) (Fast HMR and optimized production builds)
- **Styling:** CSS3 (Flexbox, Grid, Custom Properties)
- **Icons:** SVG Sprites
- **Deployment:** GitHub Pages
---
## 📄 Documentation

- **Technical Specification (TZ):** [View](https://trello.com/c/dbee2B60/25-https-docsgooglecom-presentation-d-1b4f4umx06yazpdi7hai7hefyunwrenqbfdausjcvjx0-editslideidg1213dc4fa4d03967slideidg1213dc4fa4d0)
- **Design:** [Figma Prototype](https://www.figma.com/design/7P5JaOLykmEqWPwi4O9YQi/Handmade-Jewelry--Copy-?node-id=5999-10563&t=FXsmKXpjoLKO4GJe-1)
- **Team Presentation:** [View](https://docs.google.com/presentation/d/12zf-8RfkfiQivEFH3CemprcPyw8MdzdY4JfN4Br7ZpE/edit?slide=id.g22c5bd215de_0_40#slide=id.g22c5bd215de_0_40)

## 🚀 Getting Started Locally

Follow these steps to set up the project on your local machine:


1. **Clone the repository:**
   ```bash
   git clone https://github.com/mrkorzun/shine_like_a_diamond.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd shine_like_a_diamond
   ```

3. **Install dependencies:**
   (Ensure you have Node.js installed)
   ```bash
   npm install
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

Open http://localhost:5173 in your browser to view the project.

---

## 📂 Project Structure

```text
├── src/
│   ├── css/          # Modular stylesheets
│   ├── img/          # Optimized images & SVG sprites
│   ├── js/           # JavaScript logic
│   └── main.js       # Entry point
├── index.html        # Main HTML document
├── package.json      # Project dependencies and scripts
└── vite.config.js    # Vite configuration
```
---

## 📝 License

MIT License.
