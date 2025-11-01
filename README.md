# Dhruv Business - E-Commerce Dashboard

A modern e-commerce dashboard built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🛍️ Product catalog with 12+ items
- 🛒 Shopping cart functionality
- ➕ Add to cart with quantity management
- 🗂️ Category filtering
- 💾 Persistent cart (localStorage)
- 📱 Fully responsive design
- 🎨 Modern UI with Tailwind CSS

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Build for Production

```bash
npm run build
npm start
```

## Technologies Used

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **React Context API** - State management for cart

## Project Structure

```
├── app/                  # Next.js app directory
│   ├── layout.tsx       # Root layout with CartProvider
│   ├── page.tsx         # Main dashboard page
│   └── globals.css      # Global styles
├── components/          # React components
│   ├── Header.tsx       # Navigation header
│   ├── Cart.tsx         # Shopping cart sidebar
│   └── ProductCard.tsx  # Product display card
├── context/            # React context
│   └── CartContext.tsx # Cart state management
├── data/               # Static data
│   └── products.ts     # Product catalog
└── types/              # TypeScript types
    └── product.ts      # Product & CartItem types
```

## Features Overview

### Product Dashboard
- Grid layout displaying all products
- Category filtering (All, Electronics, Accessories)
- Product cards with images, descriptions, and prices
- Stock availability display

### Shopping Cart
- Slide-in cart sidebar
- Add/remove items
- Quantity adjustment
- Real-time total calculation
- Cart badge showing item count
- Persistent storage across sessions

### Responsive Design
- Mobile-first approach
- Adapts to all screen sizes
- Touch-friendly interface

## License

MIT
