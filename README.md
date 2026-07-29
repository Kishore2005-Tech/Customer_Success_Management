# **ORBIT** - Customer Success Command Center

ORBIT is a modern, internal dashboard built for Customer Success Managers (CSMs) to track accounts, monitor customer health scores, and predict churn — all from a single command center.

🔗 [kishorep-customer-success-management-dashboard.vercel.app](https://kishorep-customer-success-management-dashboard.vercel.app/)

---

## ✨ Overview

Customer Success teams juggle dozens of accounts across multiple health signals — ARR, engagement, support tickets, renewals — often scattered across spreadsheets and disconnected tools. ORBIT consolidates all of it into one clean, keyboard-driven interface so CSMs can spot risk early and act on it fast.

## 🚀 Features

- **Portfolio Pulse** — Executive-level overview showing Total Book of Business, Net Retention Rate, Average Health Score, and Active Accounts at a glance
- **Churn Prediction Radar** — 12-month forecast vs. actual churn trend visualization
- **Accounts at Risk** — Auto-surfaced list of accounts needing immediate attention, ranked by health score
- **Account Management** — Sortable, filterable account list (All / At Risk / Enterprise / Healthy) with ARR, industry, and last-activity tracking
- **Recent Activity Feed** — Real-time timeline of touchpoints across the portfolio (QBRs, product demos, support resolutions, expansion planning)
- **Command Menu (⌘K)** — Fast keyboard-driven search and navigation across accounts and views
- **Dashboard / Accounts / Analytics / Settings** — Full multi-view app structure for day-to-day CSM workflows

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | [Next.js 16](https://nextjs.org/) (App Router), [React 19](https://react.dev/) |
| Language | TypeScript |
| Styling | Tailwind CSS 4, `tailwindcss-animate` |
| UI Components | Radix UI primitives, shadcn/ui, `lucide-react` icons |
| Forms & Validation | React Hook Form + Zod |
| Data Visualization | Recharts |
| Animation | Framer Motion |
| Utilities | `date-fns`, `embla-carousel-react`, `cmdk`, `sonner` (toasts), `next-themes` |
| Analytics | Vercel Analytics |
| Deployment | Vercel |

> Scaffolded and designed with [v0.app](https://v0.app).

## 📂 Project Structure

```
Customer_Success_Management/
├── app/            # Next.js App Router pages & layouts
├── components/     # Reusable UI components (shadcn/ui based)
├── hooks/          # Custom React hooks
├── lib/            # Utilities, helpers, and shared logic
├── public/         # Static assets
├── styles/         # Global styles
├── components.json # shadcn/ui configuration
└── next.config.mjs # Next.js configuration
```

## ⚙️ Getting Started

### Prerequisites
- Node.js 18.18+ (recommended: 20+)
- npm, pnpm, or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/Kishore2005-Tech/Customer_Success_Management.git
cd Customer_Success_Management

# Install dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the app for production |
| `npm run start` | Start the production server |
| `npm run lint` | Run ESLint |

## 🗺️ Roadmap

- [ ] Live backend integration (currently UI/dashboard prototype with sample data)
- [ ] Authentication & role-based access for CSM teams
- [ ] Configurable health score model
- [ ] Export reports (CSV/PDF)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/Kishore2005-Tech/Customer_Success_Management/issues).

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

## 👤 Author

**Kishore**
- GitHub: [@Kishore2005-Tech](https://github.com/Kishore2005-Tech)

---

⭐️ If you find this project useful, consider giving it a star!
