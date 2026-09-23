# E-commerce Website

A responsive front-end shopping experience for browsing phones and accessories. The project is built with semantic HTML, CSS, and vanilla JavaScript, with product data stored in JSON and a static cart flow for the demo store.

## Highlights

- Responsive storefront landing page
- Product collections for iPhones, Samsung phones, and headphones
- Product detail view with reusable product data
- Shopping cart page and add-to-cart interactions
- Promotional banners, collections, news content, testimonials, and responsive navigation
- Local image assets for products and site content
- Deployed demo: [e-commerce-website-pi-peach.vercel.app](https://e-commerce-website-pi-peach.vercel.app/)

## Pages and Data

```text
phone_website/
  index.html             Storefront home page
  product.html           Product detail view
  cart.html              Shopping cart view
  data/products.json     Product catalog data
  js/index.js            Home page interactions
  js/products.js         Product and cart behavior
  js/slider.js           Slider behavior
  styles.css             Responsive visual styling
  images/                Product and editorial assets
```

## Technology Stack

- HTML5
- CSS3
- JavaScript
- JSON product data
- Vercel for the deployed demo

## Run Locally

This is a static website and does not require a build step. From the repository root, serve the `phone_website` directory with any static server. For example:

```bash
cd phone_website
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser.

## Design and Implementation Insights

- Product content is separated into JSON so catalog updates do not require changing page markup.
- The storefront, product details, and cart are separate pages connected through shared scripts and browser-side state.
- Responsive CSS adapts the layout for desktop and smaller screens while preserving the shopping flow.
- The project is intentionally front-end only; it does not include authentication, server-side inventory, payment processing, or order persistence.