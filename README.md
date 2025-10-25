# GymRats – WordPress + WooCommerce E-Shop

**GymRats** is a fully functional e-commerce platform built with **WordPress** and **WooCommerce**, developed as part of the _e-Business (2024-25)_ course at the University of Patras.
The store specializes in **sportswear, footwear, and gym equipment**, offering a complete shopping experience with product variations, coupons, reviews, GDPR compliance, and enhanced accessibility features.

---

## Demo Video

[![GymRats Demo Video](https://img.youtube.com/vi/yLHBovktLV4/0.jpg)](https://youtu.be/yLHBovktLV4)

## Tech Stack

- **Platform:** WordPress (open-source CMS)
- **E-commerce:** WooCommerce
- **Database:** MySQL (via XAMPP local environment)
- **Languages:** PHP, HTML, CSS, JavaScript
- **Plugins Used:**

  - WooCommerce Variation Swatches
  - Yoast SEO
  - Ninja Forms (Contact Form)
  - WP Google Maps
  - Wordfence Security (Firewall & IP Blocking)
  - Accessibility Plugin (for visually impaired users)

---

## Setup Instructions

1. Install [XAMPP](https://www.apachefriends.org) and place the project folder inside:

   ```
   /Applications/XAMPP/xamppfiles/htdocs/
   ```

2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Access `http://localhost/wordpress` (or your chosen folder name).
4. Import the database from `gymrats_db.sql` via phpMyAdmin.
5. Log in to the admin panel:
   `http://localhost/wordpress/wp-admin`
6. Activate all required plugins and ensure permalinks are refreshed.

---

## Key Features

**Dynamic Product Catalog**

- Categorization into main & subcategories (e.g. Clothing → Shoes, Equipment)
- 30+ products with images, descriptions, prices, and stock info
- 8+ variable products with attributes (color, size, material)

**Checkout & Payments**

- Cash on delivery and bank transfer payment methods
- Custom handling fee (3.5€ Greece / 10€ abroad)
- Fully functional checkout & order flow

**Coupons & Discounts**

- 3 unique coupon types (free shipping, percentage, category-specific)
- Multiple coupon compatibility within a single order

- **Product Reviews**

  - 10+ customer reviews across multiple products
  - Top-rated items automatically displayed on homepage

**Filtering & Search**

- Product filtering by attributes (color, price range, etc.)
- Search-friendly product indexing (via Yoast SEO)

**Blog Section**

- Dynamic posts with thumbnails, titles, and dates
- Related to sports tips and new arrivals

**Contact Page**

- Integrated Google Map with store location
- Dynamic contact form using Ninja Forms

**Security & Compliance**

- GDPR notification popup
- Wordfence firewall, IP blocking, and admin URL hardening

**Accessibility**

- Plugin support for visually impaired visitors

**Additional Enhancements**

- Customized footer (logo, contact info, social media, quick links)
- Responsive layout across devices

---

## Project Info

**Course:** e-Business – Computer Engineering and Informatics Department - University of Patras
**Developer:** Evangelia Stavropoulou
**Date:** May 31, 2025

---

## License

This project is for **academic and educational purposes only**.
All trademarks, logos, and product names belong to their respective owners.
