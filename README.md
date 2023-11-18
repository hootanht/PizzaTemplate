# Pizza Shop Website Documentation

This document provides a detailed explanation of the HTML code for a Pizza Shop website. The website includes a navigation menu, a pizza menu, an order section, information about store locations, and a footer.

![image](https://github.com/hootanht/PizzaTemplate/assets/27281206/4f65893e-9c54-4ef1-a64d-9b1e3f472e3c)


## Table of Contents

1. [Introduction](#introduction)
2. [Header](#header)
3. [Pizza Menu](#pizza-menu)
4. [Order Section](#order-section)
5. [Locations](#locations)
6. [Footer](#footer)
7. [Script](#script)

## 1. Introduction<a name="introduction"></a>

The HTML code represents a Pizza Shop website with various sections such as the header, pizza menu, order section, store locations, and a footer. The website is designed to showcase pizza offerings, allow users to add items to their cart, and provide information about store locations.

## 2. Header<a name="header"></a>

The header section contains a navigation menu with three items: "Order History," "Cs Pizza Delivery," and "My Cart." Each item is represented by a `<div>` element within an unordered list (`<ul>`).

```html
<header class="header">
    <nav>
        <ul class="header-menu">
            <li>
                <div href="index.html">🔍 Order History</div>
            </li>
            <li>
                <div href="about.html" class="top-pizza-menu-item">
                    <img src="Images/top-piza-menu.png" class="top-pizza-image">
                    <span class="top-menu-item-red-cs">Cs</span><span>Pizza</span>
                    <div>Delivery</div>
                </div>
            </li>
            <li>
                <div href="contact.html">🍕 My Cart <span class="card-counter">5</span></div>
            </li>
        </ul>
    </nav>
</header>
```

## 3. Pizza Menu<a name="pizza-menu"></a>

The pizza menu section displays multiple pizza cards, each containing an image, pizza details, size options, price, and an "Add to Cart" button. The pizza cards are organized in rows.

```html
<div class="pizza-container">
    <!-- pizza items -->
    <div class="pizza-first-row">
        <!-- Individual pizza cards (repeated for each pizza) -->
        <div class="pizza-card">
            <!-- Pizza details, image, size options, and price -->
        </div>
        <!-- ... Repeat for other pizza cards ... -->
    </div>
    <!-- ... Repeat for additional rows of pizza cards ... -->
</div>
```

## 4. Order Section<a name="order-section"></a>

The order section displays the selected items in the cart, including details such as quantity, image, pizza name, and cost. It also shows the subtotal, e-vat, delivery fee, and total cost of the order.

```html
<div class="order-card">
    <!-- Individual order items (repeated for each item in the cart) -->
    <div class="order-hedear">
        <!-- Order details and item list -->
    </div>
    <!-- ... Repeat for additional order items ... -->
</div>
```

## 5. Locations<a name="locations"></a>

The locations section provides information about the Pizza Shop's store locations, including addresses, contact numbers, and a link to the branch's Facebook page. It also includes a map image.

```html
<div class="our-location">
    <!-- Individual location details (repeated for each store location) -->
    <div class="our-location-container">
        <!-- Location details including address, contact numbers, and Facebook link -->
    </div>
    <!-- ... Repeat for additional store locations ... -->
</div>
```

## 6. Footer<a name="footer"></a>

The footer section contains copyright information and a Facebook follow prompt.

```html
<footer class="footer">
    <!-- Copyright information and Facebook follow prompt -->
</footer>
```

## 7. Script<a name="script"></a>

The website includes an external script (`script.js`) for additional functionality.

```html
<script src="Scripts/script.js"></script>
```

This documentation provides an overview of the structure and purpose of each section in the HTML code. Further details about the CSS and JavaScript components can be found in their respective files (`style.css` and `script.js`).
