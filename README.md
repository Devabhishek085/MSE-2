# ShopEasy 🛍️

A modern React-based E-commerce Shopping Application that provides users with a smooth online shopping experience. ShopEasy allows users to browse products, search items instantly, apply filters, sort products, and manage a shopping cart in real time.

---

## ✨ Features

### 🛒 Product Catalog
- Displays multiple products with:
  - Product Image
  - Product Name
  - Price
  - Rating
  - Description
- Products are loaded from `products.json`
- Includes multiple categories
- Real product images integrated

---

### 🔍 Search Functionality
- Real-time product search
- Searches through:
  - Product names
  - Descriptions
  - Categories
- Search bar available in header
- Clear search button included
- Instant filtering while typing

---

### 📂 Category Filtering
Available categories:

- All
- Electronics
- Footwear
- Clothing
- Kitchen
- Sports
- Accessories
- Home

Features:
- Click-based filtering
- Active category highlighting
- Reset to **All** anytime

---

### 💰 Price Range Filtering

Available price filters:

- All Prices
- Under ₹500
- ₹500 – ₹1,000
- ₹1,000 – ₹2,000
- ₹2,000 – ₹4,000
- ₹4,000+

Real-time filtering based on selected range.

---

### 📊 Sorting Options

Users can sort products by:

- Default (Original Order)
- Price: Low to High
- Price: High to Low
- Rating
- A-Z (Alphabetical)

---

### 🛍️ Shopping Cart System

- Add products with one click
- Cart sidebar slides from right
- Auto opens when item added

Cart Features:

- Product image, name, price
- Quantity controls (+ / −)
- Remove item button
- Real-time total calculation
- Item count badge
- Empty cart message
- Close cart button
- Overlay close support

---

## 🎨 UI Components

### Header
- ShopEasy logo
- Search bar
- Cart button with badge

### Filters Panel
- Category filters
- Price filters
- Sorting dropdown
- Results count

### Product Card
- Product image
- Product name
- Rating stars
- Price in ₹
- Description preview
- Add to Cart button

### Cart Panel
- Slide-in sidebar
- Product list
- Quantity controls
- Total price
- Empty cart state

---

## ⚙️ Technical Implementation

- Built with **React**
- Uses React Hooks:
  - `useState`
  - `useMemo`
- Optimized filtering and sorting
- Responsive modern CSS design
- Component-based architecture

---

## 📁 Project Structure

```bash
ShopEasy/
│── public/
│── src/
│   │── components/
│   │   │── Header.js
│   │   │── Filters.js
│   │   │── ProductCard.js
│   │   │── Cart.js
│   │── data/
│   │   │── products.json
│   │── App.js
│   │── App.css
│   │── index.js
│── package.json
