# 🎨 Street Art Photography Website

**Author:** Parth Dwivedi
**Student ID:** E25B070716
**Tech Stack:** HTML5, CSS3 (Flexbox, Grid, Responsive Design)
**Project Type:** Horizontal Scrolling Website
**Theme:** Urban Graffiti & Street Art Aesthetic

---

## 🧱 Overview

This project is a visually immersive **Street Art Photography Website** built entirely with **HTML and CSS**, designed to demonstrate every concept from your syllabus — from basic tags to Grid and Flexbox layouts.

The site uses a **side-scrolling layout** inspired by urban street walls, featuring:

* A **flex-based navigation bar**.
* **Full-width section backgrounds** with gradient overlays.
* A **scrollable image gallery** using CSS Grid.
* An **artist showcase section** with hover effects.
* A **styled contact form**.
* A **fixed footer** with social links.

---

## 🧩 Sections Breakdown

### 1. **Navbar (Flexbox)**

* Implemented using `display: flex;` for alignment.
* Positioned at the top using `position: fixed;`.
* Contains logo and navigation links.
* Hover glow effects simulate neon lighting with `text-shadow`.

### 2. **Home Section**

* Hero section introducing the theme.
* Background image with gradient overlay using `linear-gradient()`.
* Text centered with Flexbox alignment.

### 3. **Gallery Section (Grid + Scroll)**

* Built with **CSS Grid** and `grid-auto-flow: column`.
* Horizontally scrollable using `overflow-x: scroll;`.
* Each image brightens and scales on hover using `transform` and `filter`.
* Custom scrollbar styling applied with `::-webkit-scrollbar`.

### 4. **Artists Section (Grid)**

* Uses a 2-column Grid (`grid-template-columns: repeat(2, 1fr)`).
* Artist cards feature hover animations and glowing box shadows.
* Each card contains artist name and a short bio.

### 5. **Contact Section (Forms)**

* Uses semantic form tags: `<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`.
* Demonstrates CSS box model (margin, padding, borders).
* Includes hover color transitions for the button.

### 6. **Footer (Fixed)**

* Always visible at the bottom using `position: fixed;`.
* Styled with consistent color scheme and border glow.
* Includes social links styled with hover glow.

---

## 🎨 Design Language

### **Color Palette**

| Color     | Usage                      |
| --------- | -------------------------- |
| `#2e1571` | Deep Purple (Primary tone) |
| `#a5fd45` | Neon Green (Accent)        |
| `#ff1e75` | Hot Pink (Glow & Shadow)   |
| `#ffe500` | Yellow (Highlights)        |
| `#0c0b10` | Black (Base background)    |
| `#f5f5f5` | White (Text color)         |

**Design Philosophy:**

> The palette evokes the nighttime neon ambiance of street art, balancing dark depth with vivid electric hues.

---

## ⚙️ Features & Interactions

| Feature           | Implementation                                       |
| ----------------- | ---------------------------------------------------- |
| Horizontal Scroll | Flex container with `scroll-snap-type: x mandatory;` |
| Gallery Hover     | `transform: scale(1.1)` + `filter: brightness(1.2)`  |
| Artist Glow       | `box-shadow` transitions with color highlights       |
| Sticky Navbar     | `position: fixed;` on top                            |
| Responsive Layout | `@media (max-width: 768px)` rules                    |
| Form Styling      | Border-radius + hover transitions                    |
| Custom Scrollbar  | Styled `::-webkit-scrollbar`                         |

---

## 🧠 HTML Concepts Used

* Semantic Tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
* Inline vs Block Elements: `<a>` (inline), `<div>` (block)
* Lists: `<ul>` used for artist listings
* Forms: `<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`
* Attributes: `src`, `alt`, `href`, `placeholder`, `type`

---

## 🎨 CSS Concepts Used

| Concept                          | Example                                          |
| -------------------------------- | ------------------------------------------------ |
| Inline / Internal / External CSS | External `style.css` file                        |
| Text Styling                     | `text-shadow`, `color`, `font-weight`            |
| Colors & Background              | `background-image`, `linear-gradient()`          |
| Box Model                        | Padding, margin, border-radius in `.artist-card` |
| Display                          | `flex`, `grid`, `block`, `inline-block`          |
| Positioning                      | `fixed`, `relative`                              |
| Flexbox                          | Navbar layout and section alignment              |
| Grid                             | Gallery and artist cards                         |
| Attribute Selectors              | `input[type='text']` styling                     |
| Pseudo Selectors                 | `:hover`, `:root`, `::-webkit-scrollbar-thumb`   |
| Responsive Design                | Media queries for mobile adjustments             |

---

## 📱 Responsiveness

When viewed on screens below 768px:

* Scroll direction switches from horizontal to vertical.
* Navbar stacks vertically.
* Artist grid becomes single-column.
* Gallery grid adjusts to fit smaller screens.

---

## 🧩 Learning Outcomes

* Understand difference between **Flexbox** and **Grid**.
* Learn how to **combine both** for modern web layouts.
* Practice **semantic HTML structure** and accessibility.
* Apply **CSS transitions**, **pseudo selectors**, and **responsive design**.
* Experience working with **color psychology** in design.

---

## 📜 License

This project is open for educational and personal use. Feel free to adapt it for your own learning and creative portfolio.

---

**Created with ❤️ by Raka**
*Where urban art meets digital design.*
