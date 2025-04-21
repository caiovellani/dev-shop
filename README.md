# Dev Shop 🛒💻

An e-commerce platform built for developers. Dev Shop makes it easy to browse, purchase, and manage digital products, tools, or merchandise — all in one seamless and responsive experience.

## 🚀 Tech Stack

- **Next.js** – React framework for SSR and API routes
- **TypeScript** – Static typing for better scalability
- **Tailwind CSS** – Utility-first CSS framework
- **ShadCN UI** – Prebuilt, customizable UI components
- **pnpm** – Fast and disk-efficient package manager
- **Stripe** – Payment processing (optional/integration-ready)
- **Prisma ORM** – Type-safe database client
- **PostgreSQL** – Relational database

## ✨ Features

- Product listing and detail pages
- Cart management
- Checkout flow (with Stripe integration optional)
- Admin interface (coming soon)
- Fully responsive design
- Modern and clean UI with ShadCN

## ⚙️ Getting Started

### Clone the repository 
```bash
git clone https://github.com/caiovellani/dev-shop.git
cd dev-shop
```

### Install dependencies
```bash
npm instal
```

### Set up environment variables
```bash
cp .env.example .env
# Add your database connection string, Stripe keys (if used), etc.
```

### Run migrations
```bash
npx prisma migrate dev
```

### Start the development server
```bash
npm run dev
```
