# FARHIEN — Minimal Luxury Clothing Brand Website

A minimal, high-aesthetic e-commerce and showcase website crafted for **FARHIEN**, featuring clean typography, architectural proportions, responsive layouts, and interactive shopping features.

---

## Brand Aesthetic & Features

- **Typography & Proportions**: Contemporary sans-serif pairings (*Syne*, *Space Grotesk*, *Cormorant Garamond*) inspired by luxury fashion houses (Fear of God, Acne Studios, Lemaire, Jacquemus).
- **Brand Logo**: Uses the official FARHIEN wordmark logo seamlessly across the header, mobile drawer, and inverted in the footer.
- **Interactive E-Commerce Features**:
  - **Dynamic Product Catalog**: 8 signature pieces across Outerwear, Tailoring, Knitwear, and Leather Goods.
  - **Dual Lookbook Imagery**: Smooth image crossfade and zoom on product card hover.
  - **Sliding Cart Drawer**: Real-time line item management, size/color display, quantity modifier, dynamic subtotal calculations.
  - **Complimentary Shipping Meter**: Visual progress bar tracking orders against the $250 worldwide free shipping threshold.
  - **Promo Code Engine**: Try entering `FARHIEN10` for 10% off or `SS26VIP` for 15% off.
  - **Simulated Checkout**: Clean modal feedback with generated order confirmation reference.
  - **Quick View Modal**: Modal with garment specifications (Fabric composition, Origin, Silhouette fit, and Care instructions).
  - **Currency Switcher**: Real-time currency conversion across USD ($), EUR (€), and GBP (£).
  - **Search Overlay**: Minimalist fullscreen search with popular keyword chips.
  - **Newsletter Subscription**: Real-time feedback with toast alert notifications.
  - **Fully Responsive**: Fluid layout for mobile phones, tablets, laptops, and ultra-wide screens.

---

## Directory Structure

```
farhien-store/
├── assets/
│   └── farhien-logo.png      # Official brand wordmark
├── css/
│   └── style.css             # Complete design system & responsive styling
├── js/
│   └── app.js                # State management, cart, quickview, and UI interactions
├── index.html                # Semantic HTML5 store template
└── README.md                 # Documentation
```

---

## How to Run & Preview

This website is completely code-ready and requires **no build tools or compilation**.

### Option 1: Double-click to open
Simply double-click `index.html` in your file browser (Finder) or drag it into Google Chrome, Safari, or Arc.

### Option 2: Run a local HTTP server
From this folder, run:
```bash
# Python 3
python3 -m http.server 3000

# Or npx serve (if Node.js is installed)
npx serve .
```
Then visit `http://localhost:3000` in your web browser.

---

## Easy Customization

1. **Changing Products**: Open `js/app.js` and modify the `PRODUCTS` array. Each product has fields for `name`, `priceUSD`, `category`, `sizes`, `colors`, `primaryImage`, `secondaryImage`, `description`, and `specs`.
2. **Changing Logo**: Replace `assets/farhien-logo.png` with any updated logo asset.
3. **Deploying**:
   - **GitHub Pages**: Push this repository to GitHub and enable Pages under repository Settings.
   - **Vercel / Netlify / Cloudflare Pages**: Drag and drop the `farhien-store` folder into Netlify Drop or import the GitHub repository into Vercel with zero configuration required.
