🌐 CodaExpress Web — Next.js, TypeScript & Dashboard Portal
CodaExpress Web is the modern, customer-facing web portal and analytics dashboard for the CodaExpress logistics ecosystem. Built with Next.js (App Router), TypeScript, and Tailwind CSS, it provides an ultra-fast interface for shipment bookings, "Buy-For-Me" market errand requests, and a feature-rich admin/customer dashboard.

🛠 Tech Stack
Framework: Next.js (React 18 / 19, App Router)

Language: TypeScript (Strict Type Safety)

Styling & UI: Tailwind CSS, Lucide Icons, Headless UI / Radix UI

State & Data Fetching: React Query / Axios

API Backend: Django REST Framework (DRF) + PostgreSQL (Supabase)

Asset Optimization: Cloudinary CDN

Deployment & CI/CD: Vercel

🌟 Planned Architecture & Core Capabilities
📊 1. Management & Operations Dashboard
Customer Portal: Overview of active deliveries, wallet balance, order history, and instant re-booking tools.

Admin & Dispatch Console: Real-time dispatch oversight, rider verification approval queues, driver location mapping, and transaction ledgers.

Analytics & Revenue Metrics: Interactive data visualization tracking delivery completion rates, market demurrage trends, and wallet top-ups.

📦 2. Instant Shipment & Pickup Booking
Interactive Route Input: Dynamic pickup/drop-off address routing with real-time fare estimations.

Service Tier Selection: Choose between Express Parcel Delivery, Bulk Haulage, and Market Errand dispatch.

🛒 3. "Buy-For-Me" Market Procurement Portal
Custom Itemized Ordering: Allows customers to create custom shopping lists for riders to fulfill at local markets.

Live Demurrage & Fare Tracker: Transparent real-time counter showing market dwell time and dynamic service fee logic.

🚧 Development Roadmap
[x] Phase 1: Next.js + TypeScript Base Project Initialization & Dependency Setup

[/] Phase 2: Design System, Tailwind CSS Configuration, and Responsive Layout Shells (In Progress)

[ ] Phase 3: Dashboard Analytics UI, Wallet Management & Role-Based Access Views

[ ] Phase 4: Django REST Framework Authentication, Webhooks & Order Booking Engine

[ ] Phase 5: Production Vercel Deployment & Custom Domain SSL Configuration

⚙️ Local Development Setup
1. Clone the Repository
Bash
git clone https://github.com/InnoCoda/coda-express-web.git
cd coda-express-web
2. Install Dependencies
Bash
npm install
# or
yarn install
# or
pnpm install
3. Environment Variables Configuration
Create a .env.local file in the project root (refer to .env.example):

Code snippet
NEXT_PUBLIC_API_BASE_URL=http://127.0.0.1:8000/api/v1
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
NEXT_PUBLIC_SITE_URL=http://localhost:3000
4. Run Development Server
Bash
npm run dev
# or
yarn dev
Open http://localhost:3000 in your browser to see the application running.

🔗 Connected Ecosystem Repositories
Backend REST API: coda-express-backend

Mobile App (React Native): Mobile_CodaExpress

Parent Agency: innocoda.com

Lead Engineer Portfolio: me.innocoda.com
