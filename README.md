# dashboard-invoices

**Developed by** **`Grace Chen Abudi`** 👩🏽‍💻

## 📣 Overview:

- Intro
- Tech Stack
- Techniques & Tools
- How to Get Started
- Live Project

## 🔎 Intro:

This is a dynamic full-stack app centered around the creation of a dashboard. This meticulously crafted dashboard display and manage a collection of invoices, showcasing the capabilities and versatility of Next.js. This is a practice project in Next.js.

## 🧰 Tech Stack:

- Next.js
- TypeScript
- JavaScript
- TailwindCSS
- Responsive Layout
- Vercel
- Relational Database - PostgresSQL
- SQL Queries

## 🛠️ Techniques & Tools:

- **`clsx`**: A tiny utility for constructing className strings conditionally.
- **`Hooks`**: usePathname
- **`Vercel Postgres`** is a serverless SQL database designed to integrate with Vercel Functions and your frontend framework.
- **`seed scripts`**: Contains the instructions for creating and seeding the **invoices**, **customers**, **user**, and the **revenue** tables.
- **`Server Components`**: Server Components facilitate asynchronous tasks with promises, enabling streamlined async/await syntax. They execute server-side, optimizing data fetches and logic, allowing direct database querying without an extra API layer.
- **`Request Waterfalls`**: A **"waterfall"** denotes a series of network requests reliant on prior completions. While useful for conditional dependencies, it can inadvertently impede performance in unintentional instances, emphasizing the need for careful consideration in system design.
- **`Parallel Data Fetching`**: A common way to avoid waterfalls is to initiate all data requests at the same time - in parallel. In JavaScript, you can use **"Promise.all()"** or **"Promise.allSettled()"** for performance gains. This native pattern is versatile but consider potential delays if one request lags behind others.
- **`Dynamic Rendering`**: Dynamic rendering renders content on the server for each user at request time. Benefits include real-time data display, user-specific content, and access to request-time information. However, application speed is constrained by the slowest data fetch.

---

# ✨ Live Project:

- `Visit the App` [&#128073;&#127997; **HERE !**](https://dashboard-invoices-zeta.vercel.app/)

---

## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
