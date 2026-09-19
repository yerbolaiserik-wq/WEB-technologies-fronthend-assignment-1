# WEB-technologies-frontend-assignment-1

# created by Yerbol Aisyerik from SE-2536

This repository contains the complete source code, media assets, and technical documentation for **Dostyk Restaurant**, an accessible and semantically structured multi-page web project. The Assignment 2 version adds external CSS for layout, typography, color, spacing, flexbox, grid, positioning, float, clear, and cascade demonstrations.

The site is designed with HTML5 and plain CSS only. It does not use JavaScript, CSS frameworks, templates, site builders, or hosting.

---

# Project Structure & Architecture

To satisfy academic submission requirements and maintain a clean root hierarchy, all primary HTML documents and documentation files are hosted directly at the root level, with media assets organized in a dedicated directory:

* **`index.html`** — The primary landing page featuring high-level restaurant branding, global navigation links, and introductory content.
* **`menu.html`** — The interactive menu page detailing dish categories, ingredients, pricing tables, and promotional items.
* **`order.html`** — The web form interface designed for customer order placement, featuring client-side form controls and input structure.
* **`css/base.css`** — Shared stylesheet for palette, typography, header, nav, main layout, and footer.
* **`css/aiserik.css`** — Personal stylesheet for page-specific components, table/form styling, float/clear, and specificity experiment.
* **`CSS_CHECKLIST.md`** — Assignment 2 checklist with selector and technique line references.
* **`images/`** — Dedicated directory housing all visual assets referenced across the web application:
  * `interior.jpg` — High-resolution imagery of the restaurant's interior dining space.
  * `outside.jpg` — Exterior façade and location identification photo.
  * `palay.jpg` — Featured food presentation asset.
* **`web technologies(report file).pdf`** — The official academic project report detailing requirements fulfillment, design process, and submission specifications.

---

## Technical Features & Standards

Semantic Markup:Built exclusively using structural HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`) to promote SEO visibility and screen-reader compatibility.
Form Architecture: The order interface incorporates varied input types, fieldsets, legends, and attribute-based form validation to ensure structured user input.
Asset Pathing: All media elements utilize clean relative pathing pointing directly to the `images/` directory to prevent broken references during local or remote deployment.
CSS Architecture: Every page loads `css/base.css` first and `css/aiserik.css` second. This shows the cascade and keeps shared rules separate from page-specific styling.
Clean Git Workflow: Managed with Git version control to ensure a tidy commit history, correct remote tracking, and no redundant nested repository structures.

---

## Local Setup & Deployment

To run and inspect this project locally on your machine:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yerbolaiserik-wq/WEB-technologies-fronthend-assignment-1.git](https://github.com/yerbolaiserik-wq/WEB-technologies-fronthend-assignment-1.git)
