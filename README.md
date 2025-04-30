# Nazarajs

An open-source, fully customizable, self-hosted eCommerce platform for modern developers — built with freedom and flexibility at its core.

## ✨ Overview

Nazarajs is what Linux is to operating systems — a powerful, developer-first alternative to restrictive eCommerce platforms like Shopify, WooCommerce, or even Medusa. It gives you 100% control over every layer of your store: frontend, backend, APIs, admin, and architecture.

Whether you're building a SaaS storefront, a headless PWA, or a custom commerce experience — Nazarajs is designed to be hacked, extended, and molded to your needs.

## 🧱 Features

- 🔓 100% Open Source and MIT Licensed
- 🧹 Fully modular and composable architecture
- 💅 Customizable UI with built-in starter templates
- 🎛️ Ready-to-use Admin Dashboard (like shadcn/ui but for eCommerce)
- ⚙️ Powerful API layer – easy to extend, override or swap
- 🛒 Headless, frontend-agnostic (Next.js, Nuxt, Astro, etc.)
- 🔐 Self-hosted or cloud-deployable (Vercel, Railway, Docker, etc.)
- 🌐 Multi-store, multi-language, multi-currency support (planned)

## 🏗️ Tech Stack (Planned)

- Framework: Next.js (App Router, Server Components)
- UI Layer: Tailwind CSS + shadcn/ui
- Backend: Node.js + REST / GraphQL API
- ORM: Prisma (PostgreSQL)
- Authentication: Auth.js or Clerk (pluggable)
- Deployment: Docker, Railway, Vercel, etc.
- Monorepo Tooling: Turborepo / pnpm workspaces

## 📦 Monorepo Structure (Planned)

```
nazarajs/
├── apps/
│   ├── admin/       # Admin dashboard (React + Tailwind)
│   └── storefront/  # Starter storefront template
├── packages/
│   ├── core/        # Shared types, logic, utils
│   └── api/         # Headless API (REST + GraphQL)
└── docs/            # Documentation
    .env.example
    turbo.json
    README.md
```

## 🚀 Getting Started

Coming soon. In the meantime:

1. Clone the repo
2. Install dependencies with pnpm
3. Set up environment variables
4. Start dev server for admin/storefront

## 🌍 Philosophy

Nazarajs is built with one simple belief: developers deserve freedom.

Other eCommerce solutions restrict what you can customize, often hiding business logic behind opaque abstractions or third-party dashboards. Nazarajs aims to:

- Be fully transparent — no magic, no black boxes
- Use modern, familiar tools (Next.js, Tailwind, Prisma, etc.)
- Offer flexibility with batteries included — not enforced
- Encourage composability, headless structure, and ownership

## 🛠️ Contributing

Contributions welcome! We’re building in the open and believe in a community-first future for eCommerce.

To contribute:

- Fork the repo
- Create a feature or bugfix branch
- Submit a pull request

Full contributing guide coming soon.

## 📄 License

MIT © Nazarajs

---

> “Nazarajs is not just an eCommerce tool — it's a declaration of independence for developers.”
