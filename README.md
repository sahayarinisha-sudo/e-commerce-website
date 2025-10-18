Description
🛍️ Description

This project is a front-end implementation of an e-commerce site (NM). It enables users to browse products, view product details, add items to a shopping cart, and simulate checkout (frontend logic only). The UI is responsive to different screen sizes (desktop, tablet, mobile).
The NM E-Commerce Web project is a front-end prototype of an online shopping website.
It allows users to browse different products, view details, add them to a cart, and simulate a checkout process.
This project focuses on user interface design, interactivity, and responsiveness without using any backend.

You can think of it as a “mock” e-commerce frontend (no backend, no real payments) that demonstrates interactive features, DOM manipulation, and state management in vanilla JS.
✨ Features

Features
Responsive layout for desktop, tablet, and mobile

Here are the main features / functionality included:
Product listing page with grid display

Responsive layout (works well on desktop, tablet, mobile)
Product detail view

Product listing / grid view
Add to cart and remove from cart functionality

Product detail view (when you click a product)
View cart page showing items and total price

Add to cart / remove from cart
Quantity increase/decrease options

Cart page showing selected items, total cost
Dynamic total price calculation

Ability to increase / decrease quantity of each item
Simple and clean CSS design

JavaScript-based state management (keeping cart in memory)
Easy to customize and extend

Basic styling with CSS
⚙️ How to Run

Modular code structure (HTML, CSS, JS separated)
Follow these steps to run the project locally:

Easy to extend / customize
Clone the repository:

How to Run / Usage
git clone https://github.com/sabin9679/NM-e-commerce-web.git

To run this project locally, follow these steps:

Clone the repository
Go to the project directory:

git clone https://github.com/sabin9679/NM-e-commerce-web.git
cd NM-e-commerce-web


Navigate into the project folder
Run the project:

cd NM-e-commerce-web
Just open the index.html file in any web browser

OR run a local server:

Open in browser
Open the index.html file in your browser (you can double-click it or open index.html).
# Using Python
python3 -m http.server 8000

Optionally, serve via a static file server so things like relative paths and modules work more reliably.

Interact with UI
Then open:

Browse the product listing
http://localhost:8000

Click on a product to view details

Add it to cart
Explore the app:

Visit cart, change quantities or remove items
Browse products

(Simulated) Proceed to checkout
Add them to your cart

Development / making changes
Just modify the HTML / CSS / JS files and refresh the browser to see changes.
If you want to use a local development server:
View or modify your cart

# e.g. with Python
python3 -m http.server 8000
# or use VSCode Live Server plugin
Simulate checkout

🚀 Technologies Used

HTML5 – Structure of the web pages

CSS3 – Styling and responsive layout

JavaScript (Vanilla JS) – Logic for interactivity and cart management

🧠 Challenges Faced

State Management: Maintaining cart data using JavaScript without a database or backend.

Dynamic DOM Updates: Updating cart totals and item counts in real-time.

Responsive Design: Ensuring the UI adapts to different screen sizes smoothly.

Challenges / What I Learned
Code Modularity: Organizing JS functions for scalability and readability.

During the development, I encountered and overcame several challenges. Some notable ones:
Edge Cases: Handling product removal, zero quantities, and total recalculation.

State management in vanilla JS — Keeping track of the cart state (items, quantities, totals) purely in JavaScript without frameworks required careful logic.
💡 What I Learned

Updating UI dynamically — When quantities changed or items removed, re-rendering parts of the UI (cart list, totals) and ensuring DOM updates correctly.
DOM manipulation and event handling in JavaScript

Responsive design & layout — Making sure the site looked good on different devices and screen widths; dealing with CSS flexbox, media queries, and breakpoints.
Using CSS Flexbox and Media Queries for responsive layouts

Edge cases & validation — Handling cases like quantity zero, removing last item, ensuring totals recompute correctly.
Writing clean and reusable code

Scalability & modular code — Structuring the code so that adding new features (e.g. sorting, filtering, backend integration) would be easier.
Debugging and improving UI/UX interactions
