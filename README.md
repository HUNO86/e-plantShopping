# Paradise Nursery Shopping Application

**Paradise Nursery** is an online plant shop built with React, Redux Toolkit and Vite as the final project of the IBM course *Developing Front-End Apps with React*.

## Features

- **Landing page** with a background image, the company name, a short "About Us" section and a **Get Started** button.
- **Product listing page** with houseplants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance). Each plant shows a thumbnail, name, description and price.
- **Add to Cart** buttons that add the plant to the cart, disable themselves once the plant is added and update the cart icon counter.
- **Navigation bar** on the product and cart pages with links to Home, Plants and Cart, plus a cart icon showing the total number of items.
- **Shopping cart page** showing each plant's thumbnail, name, unit price and subtotal, the total cart amount, buttons to increase or decrease the quantity, a delete button, a **Checkout** button ("Coming Soon") and a **Continue Shopping** button.

## Tech stack

- React 18
- Redux Toolkit and React Redux (cart state in `src/CartSlice.jsx`)
- Vite

## Getting started

```bash
npm install
npm run dev
```

## Project structure

| File | Purpose |
| --- | --- |
| `src/App.jsx` | Landing page with the company name and "Get Started" button |
| `src/AboutUs.jsx` | Details about the company |
| `src/ProductList.jsx` | Product listing page, navbar and cart icon |
| `src/CartItem.jsx` | Shopping cart page |
| `src/CartSlice.jsx` | Redux slice with `addItem`, `removeItem` and `updateQuantity` reducers |
| `src/store.js` | Redux store configuration |
