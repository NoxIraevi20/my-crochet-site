Crochet Co. — Handmade Crochet Bags & Outfits

A full-stack e-commerce web application built to showcase and sell handmade crochet products — bags, outfits, and accessories. This project was built as part of my self-directed journey into programming, applying Python web development fundamentals to a real-world style online store.

Overview

Crochet Co. is a demo online storefront where customers can browse a catalog of crocheted items, add products to a shopping cart, and walk through a checkout flow. The project simulates a real e-commerce experience end-to-end, from product discovery to order confirmation.

Features

Product Catalog — Browse crocheted bags and outfits with images, descriptions, and prices
Product Detail Pages — View individual product details before adding to cart
Shopping Cart — Add, update quantities, and remove items from the cart
Checkout Flow — Enter shipping/contact details and review order summary before confirming (simulated checkout — no real payment processing is connected)
Contact/Order Form — Customers can submit custom order inquiries directly through the site
Responsive Design — Works across desktop and mobile screen sizes


Tech Stack


Backend: Python (Flask/Django)
Frontend: HTML, CSS, JavaScript
Database: [SQLite / PostgreSQL — update to match what you used]
Templating: [Jinja2 if Flask, or Django Templates — update accordingly]


Project Structure

crochet-ecommerce/
├── app.py                  # Main application entry point
├── templates/               # HTML templates
│   ├── index.html
│   ├── product_detail.html
│   ├── cart.html
│   └── checkout.html
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── models.py                # Database models (Product, Order, etc.)
├── routes.py                 # Application routes/views
└── requirements.txt          # Python dependencies

How It Works


Browse — Visitors land on the homepage and browse the catalog of crochet bags and outfits.
Select — Clicking a product opens a detail page with more images, description, and pricing.
Add to Cart — Items are added to a cart, with quantity adjustments supported.
Checkout — Customers proceed to checkout, enter their details, and review their order before confirming.
Order Confirmation — A confirmation page/message is shown after the order is placed.


What I Learned

Building this project helped me apply core programming concepts in a practical context, including:


Structuring a multi-page web application with routing
Connecting a front-end UI to backend logic and a database
Managing state across a user session (cart contents, quantities)
Designing a simple, clean, and responsive UI for a real-world use case
Handling form submissions and basic data validation


Future Improvements


Integrate a real payment gateway (e.g. Stripe or PayPal sandbox)
Add user accounts and order history
Add an admin dashboard for managing inventory
Add product search and filtering (by category, color, price)
