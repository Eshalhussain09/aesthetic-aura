# Aesthetic Aura 🏡

> A multi-page home decor e-commerce website built with HTML, CSS, and vanilla JavaScript — featuring a shopping cart, 15+ product categories, and a clean storefront.

---

## Overview

Aesthetic Aura is a frontend home decor shopping website that lets users browse products across five categories (Bedroom, Bathroom, Kitchen, Decoration, Wall Decor), add items to a persistent cart, and checkout. Cart state is managed via `localStorage`, so items persist across page navigation.

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Landing page with hero section and navigation |
| Products | `product.html` | Category directory linking to all product pages |
| About | `about.html` | Brand story and mission |
| Contact | `contact.html` | Contact form and social links |
| Cart | `cart.html` | Shopping cart with total and checkout |

---

## Product Categories

**Bedroom** — Bedding Sheets, Cushion Covers, Curtains

**Bathroom** — Bathroom Accessories, Bath Mats, Towels

**Kitchen & Table** — Kitchen Accessories, Crockery & Cutlery, Mugs

**Decoration** — Lamps, Lanterns & Candles, Book Storages

**Wall Decor** — Wall Canvas Art, Wall Clocks

---

## Features

- **Add to Cart** — Every product page has "Add to Cart" buttons with prices in Rs
- **Persistent Cart** — Cart survives page navigation using `localStorage`
- **Cart Page** — Displays all items, running total, and a Checkout button
- **Checkout Flow** — Clears cart and redirects to homepage on purchase
- **Responsive Navigation** — Navbar with links to all main sections
- **Contact Form** — Message form with email and Instagram info

---

## Project Structure

```
├── index.html              # Homepage
├── product.html            # Category overview
├── about.html              # About page
├── contact.html            # Contact page
├── cart.html               # Shopping cart
│
├── bedsheet.html           # Product pages (x14)
├── cushions.html
├── curtains.html
├── bathroom.html
├── bathmat.html
├── towels.html
├── kitchen.html
├── crocery.html
├── mugs.html
├── lamps.html
├── lanterns.html
├── bookstorage.html
├── canvas.html
├── clocks.html
│
├── styles.css              # Homepage styles
├── stylePage.css           # Product category page styles
├── styleProducts.css       # Individual product page styles
├── styleCart.css           # Cart page styles
├── about.css               # About page styles
└── contact.css             # Contact page styles
```

---

## How to Run

No build tools or dependencies required. Just open `index.html` in any browser:

```bash
# Option 1: Direct open
open index.html

# Option 2: Use a local server (recommended)
npx serve .
# or
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Tech Stack

- **HTML5** — Semantic page structure
- **CSS3** — Custom styling per section
- **Vanilla JavaScript** — Cart logic with `localStorage`
- No frameworks, no build tools, no dependencies

---

*© 2024 Aesthetic Aura. All rights reserved.*
