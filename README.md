# Responsive Navigation and Layout CSS

This repository contains the CSS styles for a responsive website header, navigation, and some page sections like About and Footer. It is designed to work well on both desktop and mobile devices, including:

- Flexible header layout with a brand logo and navigation links.
- A collapsible mobile navigation menu with a "Show More" toggle.
- Responsive search bar styles.
- Clean footer and about section styling.

---

## Features

- **Mobile-friendly:** Adjusts layout and font sizes for screens up to 768px wide.
- **Collapsible navigation menu:** Limits visible nav items on mobile with a "Show More/Less" toggle.
- **Clean desktop navigation:** Horizontal nav links for screens wider than 768px.
- **Consistent styling:** Colors, spacing, and fonts chosen for readability and usability.

---

## Usage

1. Link the CSS file in your HTML `<head>` section:

```html
<link rel="stylesheet" href="path/to/your/styles.css">

Structure your HTML with classes matching the CSS selectors:

2 header
.row for the main header container.

.brand for the logo and site title.

.nav-container for the navigation and search area.

.nav-list for the navigation links list.

.show-more-label and .toggle-checkbox for the mobile "Show More" toggle.

.search-bar for the search input and button.

.footer and .footer-links for footer content.

.about-section and .about-container for the About page section.

3 Customization
Change colors in the CSS variables or directly in the stylesheet.

Add or remove navigation links in .nav-list.

Adjust breakpoints in media queries if needed.

4 License
This project is open-source and free to use under the MIT License.
