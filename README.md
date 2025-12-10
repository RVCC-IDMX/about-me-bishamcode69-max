# About Me - Bisham Khanal

[![Netlify Status](https://api.netlify.com/api/v1/badges/7ae42cff-4bb6-4d4b-b255-b543a3bbe014/deploy-status)](https://app.netlify.com/projects/about-me-bishamcode69-max-0/deploys)

## Project Description

Welcome to my personal "About Me" portfolio. This project represents a semester-long journey into the fundamentals of Web Development, evolving from a simple static HTML page into a fully responsive, multi-page website.

The primary goal of this site is to serve as a digital introduction to my professional interests and hobbies while demonstrating mastery of core web technologies. Throughout the development process, I have adhered to a "Mobile-First" design philosophy, ensuring that the content is accessible and aesthetically pleasing on devices ranging from small smartphones to large desktop monitors.

Key skills and features demonstrated in this project include:
* **Semantic HTML5**: Utilizing proper tag structures (sections, articles, figures) to ensure the site is accessible and search-engine friendly.
* **Responsive Layouts**: moving beyond basic flows to implement complex visual hierarchies using Flexbox and Media Queries.
* **Interactive UI**: A custom-built mobile navigation system and hover effects that enhance user engagement.
* **CSS Animation**: A dedicated blog section featuring a custom keyframe animation (a bouncing ball) to demonstrate physics-based motion.

---

## Design Documentation

### Navigation Design (Step 4)
For the navigation bar, I implemented a responsive strategy. 
* **Desktop View**: On screens wider than 60em (960px), the menu links are displayed in a traditional horizontal row for immediate access.
* **Mobile View**: On smaller screens, I utilized the **"CSS Checkbox Hack"**. This technique involves placing a hidden `<input type="checkbox">` in the HTML. The "Hamburger Icon" is actually a `<label>` for this checkbox. When a user taps the icon, the checkbox state changes to `checked`. I then use the CSS sibling selector (`#nav-toggle:checked ~ .navbar-links`) to override the `display: none` property and reveal the menu. This allows for a functional toggle menu without requiring any JavaScript.

### Color Scheme
I chose an **Earth Tone** palette to reflect a grounded, natural aesthetic. The design relies on high-contrast containers to ensure accessibility.

**Accessibility Check:**
* **Primary Content**: White text on Dark Espresso background (Ratio: 11.5:1).
* **Secondary Content**: Dark text on Sandstone background (Ratio: 4.8:1).
* *All main text content meets WCAG AA standards (> 4.5:1).*

| Color Name | Hex Code | RGB | Visual Use |
| :--- | :--- | :--- | :--- |
| **Clay Brown** | `#8C6C5A` | `140, 108, 90` | Page Background |
| **Deep Espresso** | `#594438` | `89, 68, 56` | Header, Footer, & Blog |
| **Forest Shadow** | `#1E2620` | `30, 38, 32` | Borders & Text |
| **Ghost White** | `#F8F8FF` | `248, 248, 255` | Primary Text |
| **Sandstone** | `#A68E7D` | `166, 142, 125` | Content Cards |

### Typography
* **Headings**: `Franklin Gothic Medium` / `Arial Narrow`. Chosen for its strong, industrial look that commands attention.
* **Body Text**: `Platypi` (Google Fonts). A serif font that provides a classic, editorial feel to the reading experience.

---

## Citations & Resources

This project was built using original code, with the following exceptions and resources:

* **Fonts**: 
    * *Platypi*, *DM Serif Text*, and *Markazi Text* via [Google Fonts](https://fonts.google.com/).
* **Images**:
    * *Avataaars.png*: Created using the [Avataaars Generator](https://getavataaars.com/).
    * *Shivapuri Trail Photos*: Personal photography collection.
* **Code References**:
    * **Hamburger Menu**: Adapted from the "CSS Checkbox Hack" technique (Referenced from MDN and CSS-Tricks tutorials).
    * **CSS Animation**: Logic for the bouncing ball physics derived from *MDN Web Docs: Using CSS Animations*.

---

## License

**Copyright © 2025 Bisham Khanal.**

All rights reserved. This project is created for educational purposes within the "Web Dev I" curriculum. You may view the source code for learning purposes, but please do not copy the design or content for your own commercial use without permission.