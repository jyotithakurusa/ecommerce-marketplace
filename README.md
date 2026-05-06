# E-Commerce Marketplace

> Full-stack e-commerce marketplace with product catalog, cart, checkout, and order management. Stripe integration, JWT auth, and a role-based admin panel.

**Status:** 🚧 Work in progress
**Tech stack:** React · Node.js · Express · MongoDB · Stripe · Tailwind CSS

---

## What it does

A fully featured e-commerce marketplace where buyers can browse a product catalog, add items to a cart, check out via Stripe, and track orders. Sellers/admins use a role-based admin panel to manage products, inventory, and orders.

## Planned features

### Buyer
- [x] Project scaffolding
- [ ] Product catalog with search + filters
- [ ] Product detail pages
- [ ] Cart with persistent state
- [ ] Checkout flow with Stripe (test mode)
- [ ] Order history + tracking

### Seller / Admin
- [ ] Role-based admin panel
- [ ] Product CRUD with image upload
- [ ] Inventory management
- [ ] Order fulfillment dashboard
- [ ] Sales analytics

### Platform
- [ ] JWT authentication + RBAC
- [ ] Responsive UI (mobile-first)
- [ ] Email notifications
- [ ] CI/CD via GitHub Actions

## Tech stack rationale

- **React + Tailwind** — fast component-based UI with utility-first styling
- **Node.js + Express** — clean REST API layer
- **MongoDB** — flexible schema for products, variants, and orders
- **Stripe** — production-grade payments without rolling your own
- **JWT + RBAC** — stateless auth with clean buyer / seller / admin separation

## How to run locally

```bash
git clone https://github.com/jyotithakurusa/ecommerce-marketplace.git
cd ecommerce-marketplace
npm install
npm run dev
```

## Roadmap

- v0.1 — Catalog + product detail pages
- v0.2 — Cart + checkout with Stripe (test)
- v0.3 — Auth + order history
- v0.4 — Admin panel + product CRUD
- v0.5 — Inventory + analytics
- v1.0 — Production deploy

---

**Author:** Jyoti Thakur · [GitHub](https://github.com/jyotithakurusa) · jyotithakurusa@gmail.com
