<div align="center">

# Top10 Qatar

### The best of Qatar, hand-picked — a bilingual (English / العربية) business‑directory platform

<br/>

![Type](https://img.shields.io/badge/Platform-Business_Directory-1D4ED8)
![Locales](https://img.shields.io/badge/Locales-English_%7C_%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-0EA5E9)
![RTL](https://img.shields.io/badge/RTL-Fully_Supported-10B981)
![Status](https://img.shields.io/badge/Status-Live-22C55E)
![License](https://img.shields.io/badge/Code-Client_Property-6B7280)

</div>

---

> ### About the source code
> **Top10 Qatar was designed and built by me for a client.** The application source code is the **client's property** and is therefore **not published** in this repository.
>
> This repository exists to **showcase the product** — its features, architecture, and screenshots — for portfolio purposes only. No proprietary code, credentials, or client data are included here.

---

## Live Links

| Portal | Audience | Link |
| ------ | -------- | ---- |
| **Consumer Website** | The public — discover & review businesses | **[Visit Live Site](https://www.qatartopten.net/en)** |
| **Business Dashboard** | Merchants — manage listings, boosts & subscriptions | **[Visit Live Dashboard](https://business.qatartopten.net/en)** |
| **Admin Panel** | Internal operations & moderation | *Private — not publicly linked (features documented [below](#admin-panel--internal))* |


---

## What is Top10 Qatar?

**Top10 Qatar** is a full, production‑grade platform that helps people in Qatar discover the best local businesses — restaurants, cafés, salons, services and more — while giving business owners a complete toolkit to list, promote, and grow their presence, and giving the operating team a powerful back office to run it all.

It is a **multi‑application system** built around a single API, with three separate front‑end portals for three separate audiences, and full **English + Arabic** support with right‑to‑left (RTL) layouts throughout.

```
                          ┌────────────────────────────────┐
                          │        Top10 Qatar API         │
                          │   (NestJS · Prisma · Postgres) │
                          └──────────────┬─────────────────┘
                                         │
             ┌───────────────────────────┼───────────────────────────┐
             │                           │                           │
   ┌──────────────────┐        ┌──────────────────┐        ┌──────────────────┐
   │  Consumer Site   │        │ Business Portal  │        │   Admin Panel    │
   │  (the public)    │        │   (merchants)    │        │  (operations)    │
   └──────────────────┘        └──────────────────┘        └──────────────────┘
```

---

## Highlights at a Glance

- **Fully bilingual** — every screen available in **English & Arabic**, with true RTL mirroring, not just translated text.
- **Ratings & reviews** — verified users leave reviews; businesses can reply; **AI sentiment analysis** surfaces the mood of feedback.
- **Paid promotion ("Boosts")** — businesses pay to rank higher in their category for a chosen period.
- **Subscriptions & payments** — tiered plans (Starter / Pro / Premium) with a real Qatar payment gateway (**Sadad**) integration.
- **Digital contracts** — merchants sign onboarding agreements electronically (**DocuSeal** e‑signature).
- **Business verification (KYB)** — a structured "Know Your Business" document & data review workflow before a business goes live.
- **AI built‑in** — an AI help assistant for shoppers, an AI content assistant for merchants, and automated review‑sentiment scoring.
- **Analytics everywhere** — growth, revenue, and engagement dashboards for admins; performance analytics for businesses.
- **QR codes** — every listing gets a scannable QR code for print & offline marketing.
- **Modern, responsive UI** — light & dark mode, mobile‑first, accessible.

---

## Consumer Website — Features

The public‑facing site where anyone can discover and review Qatar's best businesses.

| Area | What it does |
| ---- | ------------ |
| **Home & Discovery** | Curated homepage with featured categories, sponsored/boosted listings, and hand‑picked highlights. |
| **Trending** | See what's popular right now across the directory. |
| **Search** | Fast, debounced search across all listings with live results. |
| **Category Browse** | Drill down through parent categories → subcategories → listings. |
| **Listing Detail** | Rich business profile: photos, description, opening hours, phone/WhatsApp/website, map location, reviews & a shareable **QR code**. |
| **Reviews** | Signed‑in, email‑verified users write, edit and delete reviews (one per business). Sort by newest / oldest / highest / lowest. |
| **AI Assistant** | An in‑site assistant that helps visitors find what they're looking for. |
| **Accounts** | Register, log in, email verification, forgot/reset password. |
| **My Account** | Manage profile, change password, view **My Reviews**, save **Favourites**, delete account. |
| **Info Pages** | Plans, Packages, About, Contact, Privacy, Terms. |
| **Language & Theme** | Instant English ⇄ Arabic switch (RTL) and light/dark theme toggle. |

---

## Business Dashboard — Features

The merchant portal where business owners manage their entire presence on Top10.

| Area | What it does |
| ---- | ------------ |
| **Onboarding funnel** | Guided multi‑step signup: email → verification → contract → subscription → live. |
| **Listing management** | Create, edit and preview a listing — bilingual descriptions, photos, hours, contact details, location. |
| **Listing QR code** | Generate and download a QR code that links straight to the public listing. |
| **Boosts** | Purchase paid promotion to rank higher within a category for a set period. |
| **Subscriptions** | Choose and manage a plan (Starter / Pro / Premium); pay via the Sadad gateway. |
| **Reviews** | Read customer reviews on owned listings and **reply** to them. |
| **AI Content Assistant** | AI help for writing and improving listing content. |
| **Analytics** | Track views, engagement and listing performance over time. |
| **Verification (KYB)** | Submit business documents & details for the "Know Your Business" review. |
| **Contracts** | Review and **e‑sign** the onboarding agreement digitally. |
| **Notifications** | In‑app notifications for important account & listing events. |
| **Settings** | Manage business profile and account preferences. |

---

## Admin Panel — (Internal)

> The admin panel is an internal operations tool. Its **live URL is kept private**, but here is what it does.

The command center for the operations team, with **role‑based access** (Super Admin & Moderator).

| Area | What it does |
| ---- | ------------ |
| **Dashboard** | At‑a‑glance overview of the whole platform's health and activity. |
| **Analytics** | Dedicated **Overview**, **Growth**, and **Revenue** dashboards with charts. |
| **Businesses** | Browse, inspect and manage every business account, their listings and subscriptions. |
| **Users** | Manage consumer accounts. |
| **Listings moderation** | Approve, reject, suspend, restore or remove business listings. |
| **Reviews moderation** | Review the flagged‑content queue; flag/unflag and bulk‑delete reviews. |
| **Categories** | Full CRUD for categories & subcategories, ordering, icons and background images. |
| **Boosts** | Oversee all boost campaigns, configure boost tiers per category, export to CSV. |
| **Verification** | Configure the KYB field set and process pending business verification submissions. |
| **Contracts** | Manage contract templates and per‑business contract lifecycle. |
| **Subscription Plans** | Create and manage the Starter / Pro / Premium plans and pricing. |
| **Announcements** | Publish platform‑wide announcements. |
| **Email Templates** | Visually edit every transactional email (bilingual, live preview, reset‑to‑default). |
| **Site Settings** | Hero image, header navigation, footer, "top businesses" showcase, and more. |
| **Admin & Roles** | Manage admin accounts and fine‑grained permissions (RBAC). |

---

## Under the Hood — What Makes It Powerful

Even though the code isn't shared, here's what's running behind the scenes:

- **Ranking engine** — listings carry a computed ranking score (rating, reviews, views & active boosts) that decides discovery order, recalculated automatically as data changes.
- **Paid boosts** — time‑boxed, category‑scoped promotion with tiered pricing, expiry automation and full admin oversight.
- **Payments** — pluggable payment layer with a real **Sadad (Qatar)** gateway integration and automated payment reconciliation.
- **E‑signature contracts** — **DocuSeal**‑backed digital contract signing with webhook‑driven status tracking.
- **Business verification (KYB)** — configurable structured + document fields with an admin approval workflow and compliance automation.
- **AI services** — help assistant, merchant content assistant, and review **sentiment analysis** (via OpenRouter).
- **Transactional email** — a full templating system with **admin‑editable, bilingual** templates, branded layouts, and delivery guardrails.
- **Automated background jobs** — email delivery, subscription expiry / reminders / dunning, boost expiry, ranking snapshots, payment reconciliation and verification compliance all run on schedules.
- **Media & QR** — cloud object storage for images and on‑the‑fly QR‑code generation for every listing.
- **Bilingual by design** — localized data end‑to‑end; every user string lives in translation files; RTL applied at the layout level.

---

## Technology Stack

**Backend**
- **NestJS 11** (Node.js, TypeScript) — modular, three‑tenant API
- **Prisma 6** ORM over **PostgreSQL** (with `pg_trgm` full‑text / trigram search)
- **Redis** for caching (gracefully degrades when unavailable)
- **JWT** auth with refresh tokens across three independent account types
- **Sadad** payment gateway · **DocuSeal** e‑signatures · **OpenRouter** AI
- **S3‑compatible** object storage · **Swagger/OpenAPI** docs · scheduled cron jobs

**Frontends** (three separate apps)
- **Next.js 16** (App Router) · **React 19** · **TypeScript**
- **Tailwind CSS 4** for styling · light/dark theming
- **TanStack Query** (server state) · **Zustand** (client state) · **nuqs** (URL state)
- **next‑intl** for English/Arabic i18n with full RTL support

**Practices**
- Bilingual (en/ar) and RTL from the ground up
- Money handled as integer cents end‑to‑end (default currency **QAR**)
- Consistent typed API contracts between backend and every frontend
- Role‑based access control and secure, HTTP‑only refresh‑token handling

---

## Screenshots

> All images live in the [`screenshots/`](./screenshots) folder.

<br/>

## Consumer Website

<div align="center">

![Consumer Home](./screenshots/consumer-home.png)

</div>

**The homepage** — a Doha‑skyline hero with a unified **Qatar / Category / City** search, a *"Top 10 Middle Eastern in Qatar"* ranked carousel, a 12‑category browse grid, a live **Trending This Week** rail, a *"How Top10 Works"* explainer, and headline stats (**10,000+ businesses · 250,000+ verified reviews**).

<br/>

| Listing Detail | Category Browse | Live Search |
| :--: | :--: | :--: |
| ![Listing](./screenshots/consumer-listing.png) | ![Category](./screenshots/consumer-category.png) | ![Search](./screenshots/consumer-search.png) |
| Full business profile: photo gallery, **Verified & Sponsored** badges, **4.4★** rating, one‑tap **Call / WhatsApp / Website / Location**, embedded map + opening hours, an AI **"90% Positive"** sentiment strip, and threaded reviews with owner replies. | A filterable grid of **ranked** listings inside a category, each card showing rank, rating and location. | Fast, debounced search across the whole directory with live results. |

| Reviews | Trending | Arabic (RTL) |
| :--: | :--: | :--: |
| ![Reviews](./screenshots/consumer-reviews.png) | ![Trending](./screenshots/consumer-trending.png) | ![Arabic RTL](./screenshots/consumer-arabic-rtl.png) |
| Star ratings, AI sentiment tags and sortable review threads. | *"Trending This Week"* — what's hot across Qatar right now. | The **exact same site in Arabic** — a fully mirrored **right‑to‑left** layout, not just translated text. |

<br/>

## Business Dashboard

<div align="center">

![Business Dashboard](./screenshots/business-dashboard.png)

</div>

**The merchant home** (here for *"Souk Spice Kitchen"*) — live status chips (**Approved · Verified · #1 in Middle Eastern · Pro**), KPI cards (total & 30‑day views, reviews, **category rank**, active boosts), a profile‑views trend, a **Bayesian ranking‑score** chart, a star‑rating breakdown, and an AI review‑sentiment **"Happiness Score"**.

<br/>

| Listing Editor | Analytics | Reviews & Replies |
| :--: | :--: | :--: |
| ![Listing Editor](./screenshots/business-listing-editor.png) | ![Business Analytics](./screenshots/business-analytics.png) | ![Business Reviews](./screenshots/business-reviews.png) |
| Create/edit a listing — bilingual content, photos, opening hours, contact details and map location. | Views and engagement performance over time. | Read customer reviews on owned listings and **reply** to them. |

| Boosts | Subscription | Verification (KYB) |
| :--: | :--: | :--: |
| ![Boosts](./screenshots/business-boosts.png) | ![Subscription](./screenshots/business-subscription.png) | ![Business Verification](./screenshots/business-verification.png) |
| Buy paid, time‑boxed **category promotion** to rank higher. | Manage the plan, billing and renewal (Starter / Pro / Premium). | Submit business documents & details for the **"Know Your Business"** review. |

<br/>

## Admin Panel

<div align="center">

![Admin Dashboard](./screenshots/admin-dashboard.png)

</div>

**The operations command center** — revenue / profit / traffic KPIs, revenue‑over‑time and weekly‑performance charts, best‑selling listings, a customer‑satisfaction scatter, a **revenue‑by‑country world map**, an **action queue** (pending listings, verifications, boosts, flagged reviews), and a live activity feed.

<br/>

| Listings Moderation | Businesses | Analytics |
| :--: | :--: | :--: |
| ![Admin Moderation](./screenshots/admin-moderation.png) | ![Admin Businesses](./screenshots/admin-businesses.png) | ![Admin Analytics](./screenshots/admin-analytics.png) |
| A filterable, paginated queue (**All / Pending / Approved / Rejected / Suspended**) with bilingual titles, owner, status and timestamps. | Inspect every merchant, their listings and subscriptions. | Dedicated **overview / growth / revenue** dashboards with charts. |

| Verification Queue | Email Templates | Categories |
| :--: | :--: | :--: |
| ![Admin Verification](./screenshots/admin-verification.png) | ![Admin Email Templates](./screenshots/admin-email-templates.png) | ![Admin Categories](./screenshots/admin-categories.png) |
| Review and approve/reject **KYB** submissions. | Visually edit every transactional email — **bilingual**, live preview, reset‑to‑default. | Full CRUD for categories & subcategories with ordering, icons and imagery. |

---

## About

**Top10 Qatar** — designed & developed end‑to‑end (backend, three front‑end portals, integrations, and DevOps).

**Usman Ghani**
[LinkedIn](https://www.linkedin.com/in/usman-ghani-763468255/) · [Craftedbyusman@gmail.com](mailto:Craftedbyusman@gmail.com)

Built for Qatar. Source code is the property of the client and is not distributed.

<div align="center">

*This README is a product showcase. It contains no source code, secrets, or private data.*

</div>
