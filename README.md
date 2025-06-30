# NC Properties

**Key to Your Dream Home**

A **static** real estate website prototype for Nelson Chauke Properties, built with HTML, CSS, and JavaScript. This repository showcases a responsive, user‑friendly interface for browsing property listings, discovering essential services, and connecting with agents.

---

## Purpose

The NC Properties website serves as a **visual and functional prototype** to demonstrate:

* **Property Discovery**: Hero search bar with filters for "For Sale"/"To Let" and property types, enabling users to find homes by city, suburb, or area.
* **Featured Listings**: Eye‑catching card layout for displaying select properties with images, prices, key details, and brief descriptions.
* **Guidance & Tools**: A tabbed section offering property alerts, sold‑price lookup, and comprehensive buying/renting/selling guides.
* **Team Introduction**: A carousel to showcase real estate agents and their roles.
* **Brand Representation**: Consistent branding, clear navigation, and a polished, modern aesthetic to reflect professional service.

This static version can be used as the front‑end foundation for a future full‑stack implementation.

---

## Tech Stack

* **Markup**: HTML5
* **Styling**: CSS3 (modularised into `general.css`, `home.css`, `forms.css`)
* **Interactive Behaviour**: Vanilla JavaScript
* **Carousel**: [Swiper.js](https://swiperjs.com) for sliding agent cards
* **Fonts & Icons**:

  * Google Fonts: **Lato**, **Roboto**
  * Font Awesome 6 for icons

---

## Project Structure

```plaintext
nc-properties/
├── index.html               # Homepage markup
├── css/
│   ├── general.css          # Global resets and base styles
│   ├── home.css             # Homepage‑specific styles
│   ├── forms.css            # Styling for search and contact forms
│   └── swiper-bundle.min.css# Swiper carousel styles
├── js/
│   ├── main.js              # Hero search and form logic
│   └── swiper-init.js       # Initialisation of Swiper carousel
├── Media/                   # Images and media assets
└── README.md                # This file
```

---

## Getting Started

### Prerequisites

A modern web browser (Chrome, Firefox, Edge, Safari) and a code editor.

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/nc-properties.git
   cd nc-properties
   ```

2. **Open** `index.html` in your browser to view the site locally.

---

## Usage

* Scroll through **featured listings** for property details.
* Switch between **Buying**, **Renting**, and **Selling** tabs to explore available tools and guides.
* Navigate to **Contact Us** (or interact with the sign‑up pop‑up) to see form validation in action.
* View the **agents carousel** by clicking arrows to browse team members.

---

## Customisation

* **Add Listings**: Duplicate a property card in `index.html` and update image paths, text, and icons.
* **Styles**: Modify or extend CSS in the `css/` directory.
* **Scripts**: Enhance interactivity in `js/` (e.g., integrate API calls).

