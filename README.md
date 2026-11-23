# Teravex Digital Menu

A mobile-first, QR-powered digital menu platform for Kenyan hotels, restaurants, cafés and other food businesses.

**Repository:** `jark-zenith/digital-menu`  
**Status:** Product discovery and MVP planning  
**Product:** Teravex Digital Menu

## The idea

A guest scans a QR code printed on a table, counter or takeaway card. The QR code opens the restaurant's branded menu in the phone browser—no app installation required.

The first release will be a polished, realistic Kenyan hotel demo that can be shown to prospective customers. The longer-term product can support multiple businesses, each with its own menu, branding and QR destination.

## MVP experience

### Guest-facing menu
- Responsive, mobile-first layout.
- Restaurant name, logo, cover image, location and contact details.
- Categories such as breakfast, Kenyan meals, mains, sides, snacks and drinks.
- Food image, item name, short description and price in KSh.
- Clear availability labels (available / sold out).
- Search and category filtering.
- Optional WhatsApp ordering or call-to-order action.
- QR code that opens a stable menu URL.
- No account or app installation required for guests.

### Restaurant management (planned)
- Secure owner/admin sign-in.
- Create, edit, reorder and hide menu categories and items.
- Update prices, descriptions, photos and availability.
- Restaurant profile and branding settings.
- Preview the guest menu and download/print its QR code.
- Multi-restaurant support with strict data separation.

## Kenyan menu catalogue

The starter catalogue lives in [docs/kenyan-menu-catalog.md](docs/kenyan-menu-catalog.md). It is a research and content baseline, not a claim that every Kenyan hotel serves every dish. Menus vary by region, price point, supplier and hotel type.

## Product principles

1. **Fast on affordable phones:** keep pages lightweight and images optimized.
2. **Guest-first:** QR scan should lead directly to the menu.
3. **Easy to maintain:** restaurant staff should be able to update a menu without a developer.
4. **Accurate:** prices and availability must be controlled by the restaurant.
5. **Accessible:** readable typography, strong contrast and clear tap targets.
6. **Kenyan-ready:** KSh pricing, familiar meals and WhatsApp contact as an optional channel.

## Suggested implementation path

1. Build the static demo menu with realistic sample content and responsive design.
2. Add category navigation, search and item detail presentation.
3. Add a QR code pointing to the deployed demo URL.
4. Test on Android phones, low-bandwidth connections and common browsers.
5. Add the restaurant admin dashboard and persistent data.
6. Add multi-tenant restaurant onboarding, custom branding and subscription options.

## Important demo-data note

All menu prices, descriptions, availability and restaurant details used in the demo must be clearly treated as sample data. Replace them with each customer's approved menu before launch. Do not imply that sample prices are market quotations.

## Initial acceptance criteria

- A guest can scan/open the QR URL and understand the menu without instructions.
- Layout works on narrow mobile screens and desktop.
- Menu categories and items are easy to browse.
- Prices are clearly displayed in KSh.
- Sold-out items are visibly distinguished.
- QR destination remains stable when menu content changes.
- No customer order or payment is represented as completed unless a real ordering/payment workflow is implemented.

## Repository structure

```
digital-menu/
├── README.md
└── docs/
    └── kenyan-menu-catalog.md
```

## Brand

**Teravex Digital Menu**  
*Scan. Browse. Order.*

The tagline is a working direction and can be refined during visual design.
