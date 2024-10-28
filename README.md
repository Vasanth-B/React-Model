# BOWIES - React Shopping Cart

## Overview

**BOWIES** is a responsive e-commerce web app built with **React** and **Tailwind CSS**, designed to provide a simple shopping experience. Users can browse products fetched from the **Fake Store API**, add items to a cart, and manage their selected products. The cart is seamlessly integrated into the UI, displaying a live count of items and an interactive modal to review and adjust selections. The app’s responsive design ensures compatibility with both desktop and mobile devices.

### Live Demo: [Launch Here](#)

---

## Key Features

- **Product Listing:** Displays products from the Fake Store API in a clean, grid-style layout.
  
- **Add to Cart:** Users can add items to their cart. If an item is already added, an alert provides feedback to the user.

- **Remove from Cart:** Allows users to remove items directly from the cart modal, making the shopping experience more interactive.

- **Cart Count Display:** A live cart count appears in the navbar, updating in real time as items are added or removed.

- **Cart Modal:** Users can view their cart’s contents in a modal overlay, accessible by clicking the cart icon in the navbar.

- **Responsive Design:** The layout adjusts seamlessly to various screen sizes, creating an optimized experience on both desktop and mobile.

---

## Technology Stack

- **React:** Core library used for building the dynamic and component-based UI.
  
- **Tailwind CSS:** A utility-first CSS framework that simplifies responsive styling.
  
- **Fake Store API:** Provides product data, eliminating the need for backend setup.

---

## How to Use

1. **Browse Products:** The homepage displays all products from the Fake Store API in a grid view.
   
2. **Add to Cart:** Click the **Add to Cart** button on any product card. If the item is already in the cart, an alert will notify you.
   
3. **View Cart Count:** The cart icon in the navbar shows the total number of items currently in the cart.
   
4. **Open Cart Modal:** Click the cart icon to open a modal with a detailed view of all selected items.
   
5. **Manage Cart:** Use the **Remove from Cart** button inside the modal to remove items as needed.

---

## File Structure

```
src
├── assets
│   └── images         // Images for the app
├── components
│   ├── Navbar.js      // Main navigation bar with cart count
│   ├── ProductList.js // Main product grid listing
│   ├── ProductItem.js // Individual product card
│   ├── CartModal.js   // Modal displaying cart contents
│   └── CartItem.js    // Each item within the cart modal
├── App.js             // Root app component
├── index.js           // Main entry file
├── index.css          // Global styling
└── README.md          // Project documentation
```

---

## Additional Notes

- **Fake Store API:** All product data is fetched from the Fake Store API, which provides a realistic shopping experience without a custom backend.
- **Tailwind CSS Styling:** The app uses Tailwind for styling, ensuring responsive design across devices without extensive custom CSS.

