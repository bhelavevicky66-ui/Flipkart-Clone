# Flipkart Clone Project

A responsive e-commerce web application clone of Flipkart, built using HTML, CSS, and Vanilla JavaScript.

## Features

-   **User Interface**: Responsive design matching the Flipkart layout with navigation bars, sliders, and product banners.
-   **Navigation**:
    -   Functional Search Bar (Product search).
    -   Login/Signup Modal with OTP simulation.
    -   Link to Cart and "More" options.
-   **Product Display**:
    -   Dynamic product categories (Top Offers, Fashion, Electronics, etc.).
    -   Product Details Page (`des2.html`) with details, ratings, and offers.
-   **Shopping Cart**:
    -   Add products to cart.
    -   Increase/Decrease quantity.
    -   Real-time total calculation.
-   **Checkout**:
    -   "Buy Now" functionality directly from product page.
    -   Payment Gateway simulation (`payment.html`) with card validation and OTP.

## Tech Stack

-   **HTML5**
-   **CSS3** (with Flexbox and Grid)
-   **JavaScript** (ES6 modules and DOM manipulation)
-   **LocalStorage** (For persisting user sessions and cart data)

## How to Run Locally

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/bhelavevicky66-ui/Flipkart-Clone.git
    cd Flipkart-Clone
    ```

2.  **Run the Server**
    You can use any static file server. For example:
    ```bash
    npx serve .
    ```
    Or simply open `index.html` in your browser.

3.  **Explore**
    -   Home Page: `index.html`
    -   Product Details: Click on a product or navigate to `pages/des2.html`
    -   Cart: Click the Cart icon or navigate to `pages/cart.html`

## Folder Structure

-   `components/`: Reusable HTML components (Navbar, Footer, etc.) generated via JS.
-   `pages/`: Individual HTML pages for categories, product details, cart, and payment.
-   `script/`: JavaScript logic for pages and components.
-   `style/`: CSS stylesheets for styling the application.

## Screenshots

*(You can add screenshots of your project here)*

---
*This project is for educational purposes only.*
