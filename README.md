# Product List with Cart

A dessert shop web app where you can browse desserts, add them to a cart, change the quantities, and place an order. Built with React, TypeScript and Tailwind CSS.

## Description

The app shows a grid of nine desserts, each with a photo, a category, a name and a price. You add what you like to the cart, and the cart updates right away with the quantities, the price of each line and the order total. When you're happy with your cart, you confirm the order and a popup shows a summary of everything you ordered. After that you can start a new order from scratch.

## Features

- Browse nine desserts with photos, categories and prices
- Add a dessert to the cart with one click
- Increase or decrease the quantity right on the dessert card
- A dessert goes back to "Add to Cart" when its quantity reaches zero
- Remove a dessert from the cart completely with the x button
- The cart shows the number of items, the price of each line and the order total
- An empty cart shows a picture and a message
- "Confirm Order" opens a popup with a summary of the order
- "Start New Order" clears the cart and closes the popup
- Responsive layout for phones, tablets and desktops
- Hover and focus states on all buttons
- live update

## Technologies

- React
- TypeScript
- Tailwind CSS
- Vite

## How to run it

Make sure Node.js is installed, then open a terminal in the project folder and run:

```
npm install
npm run dev
```

Open the link it shows in your browser.

## Project structure

```
src/
  assets/
    components/   ProductCard, Cart, OrderModal, Icons
    data/         App.tsx, products.ts, index.css
    utils/        formatPrice.ts
    images/
    fonts/
    types.ts
  main.tsx
```

`App.tsx` holds the cart and all the logic for adding, changing and removing items. The components just display what they receive.

```
### links
 deployment :https://vercel.com/shiera1/product-list/6VBHStrtKKrNHCKs39N77xWFXqS2

 github :https://github.com/ahlamnuru/Product-list
```
