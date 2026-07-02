#  Horizon — Full-Stack Finance & Banking Platform

Horizon is a production-grade financial management platform and online banking system designed to securely link multiple real-world bank accounts, process financial transactions in real-time, and provide an interactive dashboard for personal wealth management.

##  Key Features
* **Multi-Bank Integration:** Connects seamlessly to external bank accounts via the industry-standard Plaid API to securely fetch live account balances and transaction data.
* **Real-Time Fund Transfers:** Processes secure internal balance updates and transaction tracking when sending money to other users on the platform.
* **Interactive Financial Dashboard:** Visualizes income and spending categories utilizing high-performance Doughnut charts powered by Chart.js.
* **Enterprise-Grade Form Management:** Built robust, type-safe data entry forms with client-side schema validation using React Hook Form and Zod.
* **Production Observability:** Integrated Sentry tracking for real-time application monitoring, performance analytics, and error tracking.

##  Tech Stack & Architecture
* **Framework:** Next.js 14 (App Router, Server-Side Rendering, Nested Layouts, Server Actions)
* **Language:** TypeScript (Strict type-safety)
* **Backend BaaS:** Appwrite (Authentication, Database Storage, and real-time functions)
* **Banking APIs:** Plaid (Sandbox Link Mode)
* **UI/UX Design:** Tailwind CSS, Shadcn UI components, Chart.js
* **Performance Monitoring:** Sentry

## 💻 Local Installation
1. Clone the repository: `git clone https://github.com/AyeshaK007/jsm_banking.git`
2. Install dependencies:
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

