# Clothing_Site_Admin

Admin panel for **Rangoli** — a clothing e-commerce platform for Bangladesh.

> **Status: ⏳ not started (0%).** This repository is the next major build. The customer
> storefront (`Clothing_Site_Frontend`) and API (`Clothing_Site_Backend`) are already built.

## Planned stack

- **Next.js 16** (App Router) — TypeScript only
- **UI:** shadcn/ui + TanStack Table
- **State:** React Query · **Forms:** React Hook Form + Zod
- **Auth:** credentials login against `Clothing_Site_Backend`, permission-driven sidebar
- **Drag & drop:** dnd-kit (homepage builder)

## Planned scope

- RBAC login + permission-gated navigation (`menu.*` / `resource:action`)
- Catalog CRUD (categories, products, variants, media/Cloudinary, collections)
- Orders management + delivery/status pipeline
- Homepage builder, banners, navbar, footer
- Discounts/coupons, reviews, customers, loyalty
- System Health dashboards (error logs + data-mismatch reconciliation)

## Requirements

- Node.js 20+
- The backend API running (default `http://localhost:4000/api/v1`)

## Getting started

_Scaffold to be added._ Intended:

```bash
npx create-next-app@latest . --typescript --tailwind --app --src-dir
npm install
npm run dev            # http://localhost:3001
```

## Documentation

See [`PROJECT_MASTER_DOCUMENT.md`](./PROJECT_MASTER_DOCUMENT.md) — especially §7 (Admin Roles &
Permissions), §8 (Homepage Builder) and §18 (System Health).

## License

Proprietary — all rights reserved.
