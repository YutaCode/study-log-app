# Study Log App

A simple app to record and visualize daily study activities.  
Built with **Next.js** and **Prisma**.  
This is my very first app project 🚀

## ✨ Features (MVP)
- Add study logs (title, category, minutes, date, note)
- View recent logs
- Dashboard with this week’s total study time & recent entries

## 🛠 Tech Stack
- Next.js (App Router)
- TypeScript
- Prisma + SQLite (local) → Neon Postgres (deploy)
- Tailwind CSS

## 📌 Roadmap
- [ ] Study log create form
- [ ] Logs list (latest 10)
- [ ] Dashboard (weekly total & recent logs)
- [ ] Validation with Zod
- [ ] Deployment on Vercel

## 🚀 Getting Started
```bash
pnpm install
npx prisma migrate dev
pnpm dev
