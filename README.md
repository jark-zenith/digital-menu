# Teravex Digital Menu

A mobile-first, QR-powered digital menu platform for Kenyan hotels, restaurants, cafés and other food businesses.

**Repository:** `jark-zenith/digital-menu`  
**Product:** Teravex Digital Menu  
**Current demo:** Urban Plate Restaurant (fictional sample business)  
**Status:** Front-end demonstration / MVP foundation

## Live demo experience

The root `index.html` is a dependency-light, responsive restaurant menu designed for guests opening a QR link on a phone.

### Included in this version

- Modern white restaurant interface with bold typography and Kenyan food photography.
- Sample Urban Plate identity and Nairobi setting.
- Responsive layout for mobile, tablet and desktop.
- Menu categories, search and featured/popular filtering.
- Kenyan favourites, grills, mains, snacks, breakfast, drinks and desserts.
- Sample KSh prices, explicitly identified as illustrative.
- Add-to-order-list interactions, quantity controls and estimated total.
- Copyable order summary for demonstration; it does not submit an order or process payment.
- No guest account or app installation required.

## Run locally

This is a static site. Open `index.html` in a browser or serve the repository root with any static web server. No build step is required.

For example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Kenyan menu catalogue

See [docs/kenyan-menu-catalog.md](docs/kenyan-menu-catalog.md) for the broader starter catalogue and content rules.

## Product roadmap

1. **Demo polish:** validate responsive behaviour, image loading and accessibility on real Android devices.
2. **QR entry point:** generate a stable QR code for the deployed restaurant menu URL.
3. **Restaurant admin:** secure owner login and CRUD for categories, items, prices, photos and availability.
4. **Multi-tenant platform:** each restaurant gets its own profile, branded menu URL and QR code.
5. **Ordering integrations:** optional WhatsApp handoff or a real order workflow, with clear order status.
6. **Commercial launch:** onboarding, support and subscription or setup-fee packages.

## Product principles

- Fast on affordable phones and low-bandwidth connections.
- Guest-first: scan and browse without installing an app.
- Restaurant owners control menu content, pricing and availability.
- Accessible typography, contrast and touch targets.
- KSh as the default currency, with configurable business details.

## Accuracy and demo-data policy

Urban Plate is a fictional demonstration restaurant. Menu prices, opening hours, location, descriptions and imagery are sample content, not a real business offer or market price guide. Replace all sample content with restaurant-approved details before using this product for a customer. Confirm ingredients, allergens, dietary claims, portions and availability with the restaurant owner.

## Repository structure

```
digital-menu/
├── index.html
├── README.md
└── docs/
    └── kenyan-menu-catalog.md
```

**Teravex Digital Menu** — *Scan. Browse. Order.*
