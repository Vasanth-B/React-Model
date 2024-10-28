# BOWIES - React Shopping Cart Application

## Project Overview

**BOWIES** is a modern, responsive e-commerce web app developed with **React** and **Tailwind CSS**, delivering a straightforward and intuitive shopping experience. This app leverages the **Fake Store API** to dynamically load product data and offers robust cart management features, including adding, removing, and viewing items. The cart integrates seamlessly with the UI, showcasing an interactive modal for reviewing selections and a real-time item count. BOWIES is optimized for both mobile and desktop devices.

### Live Demo: [View Here](#)

---

## Key Features

- **Product Grid:** Displays a grid of products from the Fake Store API with key details like price, name, and image.
  
- **Add to Cart Functionality:** Allows users to add items to the cart; if the item is already present, an alert notifies the user to prevent duplication.

- **Remove from Cart Option:** Users can remove items directly from the cart modal, providing a smooth and flexible shopping experience.

- **Cart Badge:** A live item count is displayed on the cart icon in the navbar, updating instantly with every change.

- **Cart Modal Display:** Users can access a detailed view of their cart items via a modal that opens when clicking the cart icon in the navbar.

- **Fully Responsive:** Designed to adapt smoothly to all screen sizes, providing an optimized shopping experience across devices.

---

## Tech Stack

- **React:** The primary library for building the UI and handling state management.
  
- **Tailwind CSS:** A utility-first CSS framework used for rapid, responsive styling.
  
- **Fake Store API:** A RESTful API that supplies realistic e-commerce product data without requiring a backend.

---

## Usage Guide

1. **Browse Products:** The homepage displays a dynamic grid of products loaded from the Fake Store API.

2. **Add Items to Cart:** Click **Add to Cart** on any product card to add it to the cart. An alert will appear if an item is already in the cart.

3. **View Cart Count:** The cart icon in the navbar shows the current number of items in the cart.

4. **Open Cart Modal:** Click the cart icon to open a modal with an overview of the selected items.

5. **Manage Cart Items:** Inside the modal, click **Remove from Cart** to remove specific items.

---

## Project Structure

```
src
├── assets
│   └── images         // Static images for app branding or UI elements
├── components
│   ├── Navbar.js      // Top navigation bar with links and cart count badge
│   ├── ProductList.js // Main product listing component, displaying products in a grid
│   ├── ProductItem.js // Individual product card component with "Add to Cart" button
│   ├── CartModal.js   // Modal displaying cart items and total count
│   └── CartItem.js    // Component for each item displayed within the cart modal
├── App.js             // Root component for the app
├── index.js           // Application entry point
├── index.css          // Global styles for the application
└── README.md          // Project documentation
```

---

## Additional Notes

- **Fake Store API:** Product data is retrieved from the Fake Store API, simulating an e-commerce experience without backend setup.
- **Tailwind CSS Integration:** The app's responsive design leverages Tailwind CSS, allowing for fast and consistent styling adjustments across devices. 

