# Racket Arena

[Racket Arena](https://racketarena.rudihe.com) Online story selling badminton rackets

## Links

- Website/Frontend: <https://racketarena.rudihe.com>
  - Backend API: <https://racketarena-api.rudihe.com>
- Respositories:
  - General: <https://github.com/rudihedev/racketarena>
  - Backend API: <https://github.com/rudihedev/racketarena-api>
  - Frontend Web: <https://github.com/rudihedev/racketarena-web>

## Inspirations

- <https://www.feletsports.com/racquet>
- <https://bambino.budigunawan.com/>

## Features

- Home Page
  - Hero Section
  - Products Catalogue
- Product Page
  - Image
  - SKU (Stock Keeping Unit)
  - Name
  - Price
  - Description
  - Stock Level/In or out of stock
  - Add to Cart Form:
    - Quantity Input
    - Increment and Decrement button
    - Add to Cart Submit Button
- Shopping Cart Page
  - Product Items to buy
    - Image, name, price, quantity, total (price x quantity)
    - Remove Item
    - Change Quantity
  - Link: continue shopping, got to PRoduct Catalogue
  - Link: Checkout
- Checkout Page
  - Order Summary
    - Product Items to buy
    - Grand Total of all product items to buy
- Place Order / Transaction is being processed

## Backend REST API Endpoints

- Production: `https://racketarena.rudihe.com`
- Local: `http://localhost:3000`

Priority:

| Endpoint           | HTTP  | Description       | Permission |
| ------------------ | ----- | ----------------- | ---------- |
| `/products`        | `GET` | Get all products  | Public     |
| `/products/{slug}` | `GET` | Get product by id | Public     |
